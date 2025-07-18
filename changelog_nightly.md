## Congatudo nightly (2025-07-19T03:43:21.134Z)
### Breaking Changes

- **mqtt**: Remove deprecated schema property from HA vacuum entity autodiscovery data [`f7f8a5e`](https://github.com/congatudo/Congatudo/commit/f7f8a5e8f28a8f2b7cf8842a07ddc9eac5305136)

### Features

- **ui**: Trim host field inputs [`f3b2dae`](https://github.com/congatudo/Congatudo/commit/f3b2daee0d85c0643463a052208bccc28b732d12)
- **mqtt**: Publish Dock Status to MQTT [`aa1ea95`](https://github.com/congatudo/Congatudo/commit/aa1ea95fa1d375652ef98a9dd572c3a3f41f67be)
- Display the actual CPU usage instead of the system load [`600378c`](https://github.com/congatudo/Congatudo/commit/600378c23f39eb2ba0b041c7a23cd1cbe7968f1d)
- **ui**: Draw half-transparent path in virtual restrictions edit map to make placing restrictions correctly easier [`4cde17e`](https://github.com/congatudo/Congatudo/commit/4cde17e36f7b4f273b10493fe997774319baa881)
- **ui**: HiDPI support for the map renderer [`33df6b3`](https://github.com/congatudo/Congatudo/commit/33df6b30ea385db03d81244c83744260eee5caf2)
- **ui**: Better feedback for the dock controls [`ebe3dcf`](https://github.com/congatudo/Congatudo/commit/ebe3dcfc897c06f556fc445a14d2743a4a1199ff)
- **mqtt**: optionally expose KeyLockCapability [`a9e5751`](https://github.com/congatudo/Congatudo/commit/a9e5751fb85df6e9d688e49575e2f3426b969d9c)
- **ui**: loading animation cleanup [`e92489b`](https://github.com/congatudo/Congatudo/commit/e92489b4fada31c23df90d4c1cdebc1b21fdc876)
- **ui**: refactor, redesign and rearrange controls a bit [`1ad1b4b`](https://github.com/congatudo/Congatudo/commit/1ad1b4b95f0d39e4526f053d578c63bf5724d9e8)
- **ui**: Change desktop UI breakpoint from min 600px to min 750px width [`03c1af4`](https://github.com/congatudo/Congatudo/commit/03c1af40a040c7e151092f0c503bd33d0d82a01a)
- **ui**: Custom icons for Fan speeds, Water grades and Operation modes [`31e786a`](https://github.com/congatudo/Congatudo/commit/31e786a71e7db9bb8d4d3bf18e2f0d8d5b21cd73)

### Fixes

- **mqtt**: Fix Home Assistant object_id generation [`ca95146`](https://github.com/congatudo/Congatudo/commit/ca95146ca51e7912f3d1f898a5a7b8210e51b1ad)
- A config reset should not reset the robot config [`04af155`](https://github.com/congatudo/Congatudo/commit/04af155b2f6f0cec832f49cd2b461f204dca2ff0)
- **ui**: Fix cutting line being invisible when using the light theme [`904a70d`](https://github.com/congatudo/Congatudo/commit/904a70d108f27ecfb99f8571d0ec3ca63baaf6c4)
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

### Refactoring

- Remove unnecessary second call to process.memoryUsage.rss() every 2.5s [`794c964`](https://github.com/congatudo/Congatudo/commit/794c964ee994bcc248db71bb5060e3eb39174952)

### Chores

- Merge pull request #130 from congatudo/dependabot/github_actions/docker/setup-buildx-action-3 [`2f8830a`](https://github.com/congatudo/Congatudo/commit/2f8830a2be66c3c715c14150913fb2eed4a4a379)
- Merge pull request #144 from congatudo/dependabot/github_actions/docker/setup-qemu-action-3.6.0 [`cd3f25d`](https://github.com/congatudo/Congatudo/commit/cd3f25dfcf7ba65af933631b81bfd2dc14a46c64)
- Merge pull request #136 from congatudo/dependabot/github_actions/lycheeverse/lychee-action-2.3.0 [`d71b35c`](https://github.com/congatudo/Congatudo/commit/d71b35c0fc72a517246b2e2ef57f22a15d9e6068)
- Merge pull request #142 from congatudo/dependabot/github_actions/docker/build-push-action-6.15.0 [`69e69c5`](https://github.com/congatudo/Congatudo/commit/69e69c55d38fb90844c13bc010e6e1b2c74ce3f4)
- Merge pull request #143 from congatudo/dependabot/github_actions/actions/cache-4.2.2 [`eb9f708`](https://github.com/congatudo/Congatudo/commit/eb9f7084bfdf3e5708062ef8cc035d2604091452)
- more link fixes [`914e260`](https://github.com/congatudo/Congatudo/commit/914e26090c6f0ada616d7757ec1b4fb9e8d6fadd)
- Merge pull request #124 from congatudo/dependabot/github_actions/docker/login-action-3.3.0 [`1a13f35`](https://github.com/congatudo/Congatudo/commit/1a13f354b41b72550377bce70f10475414de1465)
- Merge pull request #125 from congatudo/dependabot/github_actions/peter-evans/create-issue-from-file-5.0.1 [`119628e`](https://github.com/congatudo/Congatudo/commit/119628e5ba54594ba17a2487a3ab433152ae66b5)
- Merge pull request #126 from congatudo/dependabot/github_actions/docker/build-push-action-6.10.0 [`7f68bf6`](https://github.com/congatudo/Congatudo/commit/7f68bf6d43429bda0d7e6acb72f63adcc38ec167)
- Merge pull request #128 from congatudo/dependabot/github_actions/lycheeverse/lychee-action-2.2.0 [`57c69eb`](https://github.com/congatudo/Congatudo/commit/57c69ebfad6f55e481522fa86c1fd6e3e2ca6031)
- Merge pull request #127 from congatudo/dependabot/github_actions/docker/setup-qemu-action-3.2.0 [`2d4a38f`](https://github.com/congatudo/Congatudo/commit/2d4a38fdc89919fedf988d4bbe75667f2d1a911d)
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
