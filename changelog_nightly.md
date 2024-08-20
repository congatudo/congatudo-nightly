## Congatudo nightly (2024-08-20T02:53:53.336Z)
### Breaking Changes

- **mqtt**: Remove deprecated schema property from HA vacuum entity autodiscovery data [`f7f8a5e`](https://github.com/congatudo/Congatudo/commit/f7f8a5e8f28a8f2b7cf8842a07ddc9eac5305136)

### Features

- **ui**: HiDPI support for the map renderer [`33df6b3`](https://github.com/congatudo/Congatudo/commit/33df6b30ea385db03d81244c83744260eee5caf2)
- **ui**: Better feedback for the dock controls [`ebe3dcf`](https://github.com/congatudo/Congatudo/commit/ebe3dcfc897c06f556fc445a14d2743a4a1199ff)
- **mqtt**: optionally expose KeyLockCapability [`a9e5751`](https://github.com/congatudo/Congatudo/commit/a9e5751fb85df6e9d688e49575e2f3426b969d9c)
- **ui**: loading animation cleanup [`e92489b`](https://github.com/congatudo/Congatudo/commit/e92489b4fada31c23df90d4c1cdebc1b21fdc876)
- **ui**: refactor, redesign and rearrange controls a bit [`1ad1b4b`](https://github.com/congatudo/Congatudo/commit/1ad1b4b95f0d39e4526f053d578c63bf5724d9e8)
- **ui**: Change desktop UI breakpoint from min 600px to min 750px width [`03c1af4`](https://github.com/congatudo/Congatudo/commit/03c1af40a040c7e151092f0c503bd33d0d82a01a)
- **ui**: Custom icons for Fan speeds, Water grades and Operation modes [`31e786a`](https://github.com/congatudo/Congatudo/commit/31e786a71e7db9bb8d4d3bf18e2f0d8d5b21cd73)

### Fixes

- remove trailing spaces [`53328d9`](https://github.com/congatudo/Congatudo/commit/53328d93cf7074bfe426246a0fc33d065005b426)
- **ui**: Extending HTML elements is not supported by safari [`27647f6`](https://github.com/congatudo/Congatudo/commit/27647f6fbd63fe77b30450a6c2851af1a1f8b24a)
- **ui**: fix some hiDPI related issues [`324d78c`](https://github.com/congatudo/Congatudo/commit/324d78c0f96517369780219026eb1772ad2febbf)
- zone management section [`a50b950`](https://github.com/congatudo/Congatudo/commit/a50b950a848af39e1c3bf38429b77d798ef14bdc)
- **ui**: Draw stroke before fill for map structures that have text to fix rendering on firefox mobile [`0cd7f46`](https://github.com/congatudo/Congatudo/commit/0cd7f46903e8b87dcd802386e53d64d3c9e01c44)
- **ui**: Don't display preset value until it is actually committed [`79233c3`](https://github.com/congatudo/Congatudo/commit/79233c3b44bf5f68b0cd0a40100e53ee5de6f99b)
- **mqtt**: Always refresh gettable handles after setting [`351dcf6`](https://github.com/congatudo/Congatudo/commit/351dcf674667410e217c75658fb3cec1697bf50b)
- **MockRobot**: Remove turbo water grade [`5dd265e`](https://github.com/congatudo/Congatudo/commit/5dd265e54ab7c23c3e4f460b10bdcfd71a2ed2fe)
- **timers**: wait a few seconds after executing pre_actions to give the firmware some time [`fe80456`](https://github.com/congatudo/Congatudo/commit/fe80456972209736150334c93fb4dc5fca162226)
- Don't crash the process if we're not able to persist the config [`22d08c9`](https://github.com/congatudo/Congatudo/commit/22d08c9cb6b68b1e3dd6b1d6ba7847c24f692344)
- **ui**: Fix missing controls card content indentation [`297d12b`](https://github.com/congatudo/Congatudo/commit/297d12b41f6357f7eaebfead283dc494f134a6ae)
- **mqtt**: bump to mqttjs v5.5.5 to fix some keep-alive related issues [`8e4a7b5`](https://github.com/congatudo/Congatudo/commit/8e4a7b54f6fc2ec9ccadd003b494097ede8524b7)

### Chores

- random workflow hours to avoid errors [`61b94f9`](https://github.com/congatudo/Congatudo/commit/61b94f93b9ac3a003f4bd65a43067a7df214a5ec)
- upgraded mqtt and fixed bug [`993eea1`](https://github.com/congatudo/Congatudo/commit/993eea1dee520aa84d0284a8af30ce85c3d52e96)
- delete old files [`6ddb42f`](https://github.com/congatudo/Congatudo/commit/6ddb42fea0bd7d0ef547002d26ab5464f3bb834b)
- Merge pull request #107 from congatudo/dependabot/bundler/docs/nokogiri-1.16.5 [`a2e4358`](https://github.com/congatudo/Congatudo/commit/a2e43583569fecd19d51ead1a085ebcc98347017)
- Merge pull request #108 from congatudo/dependabot/bundler/docs/rexml-3.2.8 [`683254f`](https://github.com/congatudo/Congatudo/commit/683254fceda69a2b770d520a2d8d5ef3d7e455fd)
- Merge pull request #113 from congatudo/dependabot/npm_and_yarn/braces-3.0.3 [`84e53f4`](https://github.com/congatudo/Congatudo/commit/84e53f4a81ce1ed52b7182319405eadf0c4d5397)
- misc cleanup [`c826c9d`](https://github.com/congatudo/Congatudo/commit/c826c9de9243270c7c5ba27831802e4ccdb0e35a)
- **docs**: fixed donate link again [`1456b9e`](https://github.com/congatudo/Congatudo/commit/1456b9eccda88e39aaf1684333d3d51f34fd4f55)
- **docs**: fixed donate link [`853fbe4`](https://github.com/congatudo/Congatudo/commit/853fbe4400376bb80bf254e7607a318e51c6f11f)
- Merge pull request #105 from congatudo/dependabot/bundler/docs/nokogiri-1.16.4 [`94831c8`](https://github.com/congatudo/Congatudo/commit/94831c8506f16fc7f5191768dfeb04ddd68f3e31)
- Merge pull request #104 from congatudo/dependabot/npm_and_yarn/backend/axios-0.28.0 [`0806a09`](https://github.com/congatudo/Congatudo/commit/0806a09f913e0a8f0527d5c31e1b6e058d668bcb)
- **node**: update deps [`894bc72`](https://github.com/congatudo/Congatudo/commit/894bc727c755a810cc01fed36b632d24b52da245)
- updated github actions to node 20 [`9d4ee80`](https://github.com/congatudo/Congatudo/commit/9d4ee809ca0c1cbb640d54dd0c92b02eaad8788e)
