# yarn workspace + rocket-punch sample

This sample is provide how to test your rocket-punch project with workspace. it will help you when you want to check your packages on isolated environments like monorepo.

This is based on a simple logic. it build the target project to the `/packages` directory on this project. And, yarn use the `/packages` directory as a workspace.

This sample uses only `yarn workspace`. But, I think it can use Lerna too in same logic.

1. `yarn import:rocket-scripts`: build `rocket-scripts` packages to `packages/` directory
2. `yarn web:start`: run start script of the samples