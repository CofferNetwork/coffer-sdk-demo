#

## npm package with org scope

1. make sure no mirror in `~/.npmrc`
2. make sure package name starts with `@coffer-network/`
3. login npmjs and auth device

```bash
# this will open browser, and you need to login
npm login

# this will open browser, and you need to authorize
npm adduser
```

4. publish the code

```bash
# publish to public repo
npm publish --access public
```
