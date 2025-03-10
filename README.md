<div align="center">
  <a href="https://aztec.network">
    <img src="https://github.com/AztecProtocol/aztec-packages/blob/master/docs/static/img/aztec-logo.9cde8ae1.svg" alt="Aztec Protocol Logo" width="300">
  </a>
</div>

# The deploy issue
node --import tsx scripts/deploy.ts
node:internal/modules/esm/resolve:854
  throw new ERR_MODULE_NOT_FOUND(packageName, fileURLToPath(base), null);
        ^

Error [ERR_MODULE_NOT_FOUND]: Cannot find package 'tsx' imported from /home/<user>/Documents/Code/Aztec/aztec-starter/
    at packageResolve (node:internal/modules/esm/resolve:854:9)
    at moduleResolve (node:internal/modules/esm/resolve:927:18)
    at defaultResolve (node:internal/modules/esm/resolve:1169:11)
    at ModuleLoader.defaultResolve (node:internal/modules/esm/loader:542:12)
    at ModuleLoader.resolve (node:internal/modules/esm/loader:510:25)
    at ModuleLoader.getModuleJob (node:internal/modules/esm/loader:239:38)
    at ModuleLoader.import (node:internal/modules/esm/loader:472:34)
    at asyncRunEntryPointWithESMLoader (node:internal/modules/run_main:117:36)
    at runEntryPointWithESMLoader (node:internal/modules/run_main:146:19)
    at Function.executeUserEntryPoint [as runMain] (node:internal/modules/run_main:165:5) {
  code: 'ERR_MODULE_NOT_FOUND'
}

Node.js v20.18.1