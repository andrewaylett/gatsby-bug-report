Running `npm install` in this repo builds an inconsistent dependency tree:

```
andrewaylett@ANDRAYLE01M:~/tmp/gatsby$ npm ls gatsby
gtest@1.0.0 /Users/andrewaylett/tmp/gatsby
└─┬ UNMET PEER DEPENDENCY gatsby@2.22.13
  └─┬ gatsby-admin@0.1.54
    └── UNMET PEER DEPENDENCY gatsby@2.22.13  deduped

npm ERR! peer dep missing: gatsby@2.6.0, required by gatsby-interface@0.0.163
```
