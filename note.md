pnpx codemod pnpm/catalog命令会将工作区中package.json的版本协议全部替换为catalog协议

pnpm --filter @packages/utils add dayjs
pnpm -F @packages/utils add dayjs会在特定目录安装包，不会安装在根目录下