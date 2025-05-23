## API Report File for "@backstage-community/plugin-scaffolder-backend-module-blackduck"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { BackendFeature } from '@backstage/backend-plugin-api';
import { BlackDuckConfig } from '@backstage-community/plugin-blackduck-node';
import { JsonObject } from '@backstage/types/index';
import { LoggerService } from '@backstage/backend-plugin-api';
import { TemplateAction } from '@backstage/plugin-scaffolder-node';

// @public (undocumented)
export function createBlackduckProjectAction(
  blackDuckConfig: BlackDuckConfig,
  logger: LoggerService,
): TemplateAction<
  {
    projectName: string;
    projectVersion?: string | undefined;
    versionPhase?: string | undefined;
    versionDistribution?: string | undefined;
    instanceName?: string | undefined;
  },
  JsonObject,
  'v1'
>;

// @public (undocumented)
const scaffolderModuleBlackduckModule: BackendFeature;
export default scaffolderModuleBlackduckModule;

// (No @packageDocumentation comment for this package)
```
