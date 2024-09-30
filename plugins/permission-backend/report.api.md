## API Report File for "@backstage/plugin-permission-backend"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { AuthService } from '@backstage/backend-plugin-api';
import { DiscoveryService } from '@backstage/backend-plugin-api';
import express from 'express';
import { HttpAuthService } from '@backstage/backend-plugin-api';
import { IdentityApi } from '@backstage/plugin-auth-node';
import { LoggerService } from '@backstage/backend-plugin-api';
import { PermissionPolicy } from '@backstage/plugin-permission-node';
import { RootConfigService } from '@backstage/backend-plugin-api';
import { UserInfoService } from '@backstage/backend-plugin-api';

// @public @deprecated
export function createRouter(options: RouterOptions): Promise<express.Router>;

// @public @deprecated
export interface RouterOptions {
  // (undocumented)
  auth?: AuthService;
  // (undocumented)
  config: RootConfigService;
  // (undocumented)
  discovery: DiscoveryService;
  // (undocumented)
  httpAuth?: HttpAuthService;
  // (undocumented)
  identity?: IdentityApi;
  // (undocumented)
  logger: LoggerService;
  // (undocumented)
  policy: PermissionPolicy;
  // (undocumented)
  userInfo?: UserInfoService;
}

// Warnings were encountered during analysis:
//
// src/service/router.d.ts:13:5 - (ae-undocumented) Missing documentation for "logger".
// src/service/router.d.ts:14:5 - (ae-undocumented) Missing documentation for "discovery".
// src/service/router.d.ts:15:5 - (ae-undocumented) Missing documentation for "policy".
// src/service/router.d.ts:16:5 - (ae-undocumented) Missing documentation for "identity".
// src/service/router.d.ts:17:5 - (ae-undocumented) Missing documentation for "config".
// src/service/router.d.ts:18:5 - (ae-undocumented) Missing documentation for "auth".
// src/service/router.d.ts:19:5 - (ae-undocumented) Missing documentation for "httpAuth".
// src/service/router.d.ts:20:5 - (ae-undocumented) Missing documentation for "userInfo".
```