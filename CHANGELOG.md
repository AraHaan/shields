# Changelog

Note: this changelog is for the shields.io server. The changelog for the badge-maker NPM package is at https://github.com/badges/shields/blob/master/badge-maker/CHANGELOG.md

---

## server-2021-08-01

- update auto close action for dependabot native [#6834](https://github.com/badges/shields/issues/6834)
- use v5 API for [AUR] badges [#6836](https://github.com/badges/shields/issues/6836)
- tests: add live Sonar tests with >=6.6 API changes [#6817](https://github.com/badges/shields/issues/6817)
- fix: authenticate weblate requests [#6790](https://github.com/badges/shields/issues/6790)
- chore: exclude services and tests from docs [#6791](https://github.com/badges/shields/issues/6791)
- [Sonar] Fix invalid fetch query to sonarqube >=6.6 [#6636](https://github.com/badges/shields/issues/6636)
- added a correct the path to the sponsers logo [#6813](https://github.com/badges/shields/issues/6813)
- tests: fix scrutinizerbuild service test [#6785](https://github.com/badges/shields/issues/6785)
- tests: fix Docker Version test for user repo [#6783](https://github.com/badges/shields/issues/6783)
- tests: fix codacy service tests [#6781](https://github.com/badges/shields/issues/6781)
- chore: switch to c8 for code coverage [#6778](https://github.com/badges/shields/issues/6778)
- Delegate discord logo to simple-icons, which matches the current branding [#6764](https://github.com/badges/shields/issues/6764)
- chore: refactor weblate code [#6765](https://github.com/badges/shields/issues/6765)
- Fix [CodeClimateCoverage] test [#6759](https://github.com/badges/shields/issues/6759)
- Fix [JenkinsTests] test [#6758](https://github.com/badges/shields/issues/6758)
- Re-apply 'Migrate request to got (part 1)' [#6755](https://github.com/badges/shields/issues/6755)
- Fix UptimeRobot status endpoint [#6757](https://github.com/badges/shields/issues/6757)
- Delete old deprecated badges [#6756](https://github.com/badges/shields/issues/6756)
- fix: weblate badges to better fit repo guidelines [Weblate] [#6712](https://github.com/badges/shields/issues/6712)
- Delegate related projects to awesome-badges list [#6746](https://github.com/badges/shields/issues/6746)
- Replace opn-cli with open-cli [#6747](https://github.com/badges/shields/issues/6747)
- Verify that Node 14 is installed in development [#6748](https://github.com/badges/shields/issues/6748)
- Migrate from CommonJS to ESM [#6651](https://github.com/badges/shields/issues/6651)
- Add Wikiapiary Extension Badge [WikiapiaryInstalls] [#6678](https://github.com/badges/shields/issues/6678)
- deprecate [beerpay] [#6708](https://github.com/badges/shields/issues/6708)
- deprecate [microbadger] [#6709](https://github.com/badges/shields/issues/6709)
- fix [github] commit since tests [#6705](https://github.com/badges/shields/issues/6705)
- [npmsioscore] Support npm score [#6630](https://github.com/badges/shields/issues/6630)
- Add [Weblate] badges [#6677](https://github.com/badges/shields/issues/6677)
- Changelog for Release server-2021-07-01 [#6687](https://github.com/badges/shields/issues/6687)
- improve [MavenCentral], [MavenMetadata], and [GradlePluginPortal] [#6628](https://github.com/badges/shields/issues/6628)
- docs: broken links and typos [#6676](https://github.com/badges/shields/issues/6676)
- test: add generic metric helper [#6684](https://github.com/badges/shields/issues/6684)
- convert bug report issue template to issue form [#6681](https://github.com/badges/shields/issues/6681)
- fix: fix regex to match [codecov]'s flags [#6655](https://github.com/badges/shields/issues/6655)
- Run on node 14 in production, drop node 10 support for badge-maker and update test matrix [#6652](https://github.com/badges/shields/issues/6652)
- fix usage style [#6638](https://github.com/badges/shields/issues/6638)
- Build(deps-dev): bump webextension-store-meta from 1.0.3 to 1.0.4 [#6631](https://github.com/badges/shields/issues/6631)
- update simple-icons to v5 with by-name lookup backwards compatibility [#6591](https://github.com/badges/shields/issues/6591)
- [GradlePluginPortal] add gradle plugin portal [#6449](https://github.com/badges/shields/issues/6449)
- badge-maker 3.3.1 release [#6568](https://github.com/badges/shields/issues/6568)
- convert [discord] to use static properties [#6566](https://github.com/badges/shields/issues/6566)
- upgrade some vulnerable packages [#6569](https://github.com/badges/shields/issues/6569)
- increase max-age for download and social badges [#6567](https://github.com/badges/shields/issues/6567)
- run package tests on node 16, drop node 10 testing [#6570](https://github.com/badges/shields/issues/6570)
- Changelog for Release server-2021-06-01 [#6565](https://github.com/badges/shields/issues/6565)
- Changed creating badges to open a new Window/Tab [#6536](https://github.com/badges/shields/issues/6536)
- Make for-the-badge letter spacing more predictable, and rewrite layout logic [#5754](https://github.com/badges/shields/issues/5754)
- fix: bower version tests [#6533](https://github.com/badges/shields/issues/6533)
- fix MyGet tenant-based service tests and examples [#6531](https://github.com/badges/shields/issues/6531)
- Fix [Cran] devtools license [#6515](https://github.com/badges/shields/issues/6515)
- deprecate DockerBuild service [#6529](https://github.com/badges/shields/issues/6529)
- increase [David] service test timeouts [#5966](https://github.com/badges/shields/issues/5966)
- Remove rate limiting functionality [#6513](https://github.com/badges/shields/issues/6513)
- fix: correct GitHubSponsors example [#6512](https://github.com/badges/shields/issues/6512)
- Increase server request rate limits [#6511](https://github.com/badges/shields/issues/6511)
- [GitHub] Move to 'funding' category [#5846](https://github.com/badges/shields/issues/5846)
- Add GitHub discussions total badge [GithubTotalDiscussions] [#6472](https://github.com/badges/shields/issues/6472)
- Modify github action helper to autoclose typescript-eslint scoped bumps [#6468](https://github.com/badges/shields/issues/6468)
- Add optional query parameter (include_prereleases) to [GemVersion] [#6451](https://github.com/badges/shields/issues/6451)
- Add [PingPong] Service [#6327](https://github.com/badges/shields/issues/6327)
- Fix Symfony branches for [TravisPHPVersion] [#6452](https://github.com/badges/shields/issues/6452)
- Specification: Add better alt-text [#6448](https://github.com/badges/shields/issues/6448)
- Changelog for Release server-2021-05-01 [#6447](https://github.com/badges/shields/issues/6447)
- Fix [Symfony] tests again [#6424](https://github.com/badges/shields/issues/6424)
- Deprecate [Bintray] service [#6423](https://github.com/badges/shields/issues/6423)
- Delete outdated rewriting-services.md [#6391](https://github.com/badges/shields/issues/6391)
- Delete outdated users.md [#6390](https://github.com/badges/shields/issues/6390)
- use \r\n linebreaks when writing raw HTTP [#6386](https://github.com/badges/shields/issues/6386)
- return a 408 Request Timeout response for timed out requests [#6371](https://github.com/badges/shields/issues/6371)
- Support git hash in [nexus] SNAPSHOT version [#6369](https://github.com/badges/shields/issues/6369)
- add setting which allows us to set a timeout on HTTP requests [#6364](https://github.com/badges/shields/issues/6364)
- Replace 4183C4 with blue [#6366](https://github.com/badges/shields/issues/6366)
- [Youtube] Added channel view count and subscriber count badges [#6333](https://github.com/badges/shields/issues/6333)
- Fix Netlify badge by adding new color schema [#6340](https://github.com/badges/shields/issues/6340)
- [REUSE] Add service badges [#6330](https://github.com/badges/shields/issues/6330)
- Changelog for Release server-2021-04-01 [#6338](https://github.com/badges/shields/issues/6338)
- Upgrade to gatsby 3 [#6331](https://github.com/badges/shields/issues/6331)
- Fix raster example [#6306](https://github.com/badges/shields/issues/6306)
- Address compliance issues with YouTube API Services Terms and Policies [#6304](https://github.com/badges/shields/issues/6304)
- Fix [Symfony] tests [#6305](https://github.com/badges/shields/issues/6305)
- Update number of badges served each month [#6278](https://github.com/badges/shields/issues/6278)
- Revert request --> got migration (for now) [#6277](https://github.com/badges/shields/issues/6277)
- Use NPM packages to provide fonts instead of Google Fonts [#6274](https://github.com/badges/shields/issues/6274)
- Add docs for all types of releases [#6210](https://github.com/badges/shields/issues/6210)
- Prevent duplication of parameters in badge examples [#6272](https://github.com/badges/shields/issues/6272)
- refresh self-hosting docs [#6273](https://github.com/badges/shields/issues/6273)
- allow missing 'goal' key in [liberapay] badges [#6258](https://github.com/badges/shields/issues/6258)
- use got to push influx metrics [#6257](https://github.com/badges/shields/issues/6257)
- send custom user agent when using got [#6256](https://github.com/badges/shields/issues/6256)
- Migrate request to got (part 1 of many) [#6160](https://github.com/badges/shields/issues/6160)
- remove script for adding/removing heroku dynos [#6234](https://github.com/badges/shields/issues/6234)
- Changelog for Release server-2021-03-01 [#6233](https://github.com/badges/shields/issues/6233)
- ensure redirect target path is correctly encoded [#6229](https://github.com/badges/shields/issues/6229)
- [SecurityHeaders] Added a possibility for no follow redirects [#6212](https://github.com/badges/shields/issues/6212)
- catch URL parse error in [endpoint] badge [#6214](https://github.com/badges/shields/issues/6214)
- Make [Coveralls] examples consistent with regards to VCS parameter [#6181](https://github.com/badges/shields/issues/6181)
- [Homebrew] Add homebrew downloads badge [#6209](https://github.com/badges/shields/issues/6209)
- update [pkgreview] url [#6189](https://github.com/badges/shields/issues/6189)
- Make [Twitch] a social badge [#6183](https://github.com/badges/shields/issues/6183)
- Narrow down [PyPi] regex expressions [#6184](https://github.com/badges/shields/issues/6184)
- update [flathub] error handling [#6185](https://github.com/badges/shields/issues/6185)
- Add [Testspace] badges [#6162](https://github.com/badges/shields/issues/6162)
- Allow links only for social badges, affects [GitHubMilestone Dependabot] [#6159](https://github.com/badges/shields/issues/6159)
- Improve changelog entries [#6157](https://github.com/badges/shields/issues/6157)
- Update Contributing documentation on PRs/service tests & amending history [#6128](https://github.com/badges/shields/issues/6128)
- add script for adding/removing heroku dynos [#6131](https://github.com/badges/shields/issues/6131)
- Dependency updates

## server-2021-07-01

- improve [MavenCentral], [MavenMetadata], and [GradlePluginPortal] [#6628](https://github.com/badges/shields/issues/6628)
- fix: fix regex to match [codecov]'s flags [#6655](https://github.com/badges/shields/issues/6655)
- fix usage style [#6638](https://github.com/badges/shields/issues/6638)
- update simple-icons to v5 with by-name lookup backwards compatibility [#6591](https://github.com/badges/shields/issues/6591)
- [GradlePluginPortal] add gradle plugin portal [#6449](https://github.com/badges/shields/issues/6449)
- upgrade some vulnerable packages [#6569](https://github.com/badges/shields/issues/6569)
- increase max-age for download and social badges [#6567](https://github.com/badges/shields/issues/6567)
- Dependency updates

## server-2021-06-01

- Changed creating badges to open a new Window/Tab [#6536](https://github.com/badges/shields/issues/6536)
- Make for-the-badge letter spacing more predictable, and rewrite layout logic [#5754](https://github.com/badges/shields/issues/5754)
- deprecate DockerBuild service [#6529](https://github.com/badges/shields/issues/6529)
- Remove rate limiting functionality [#6513](https://github.com/badges/shields/issues/6513)
- [GitHub] Move to 'funding' category [#5846](https://github.com/badges/shields/issues/5846)
- Add GitHub discussions total badge [GithubTotalDiscussions] [#6472](https://github.com/badges/shields/issues/6472)
- Add optional query parameter (include_prereleases) to [GemVersion] [#6451](https://github.com/badges/shields/issues/6451)
- Add [PingPong] Service [#6327](https://github.com/badges/shields/issues/6327)
- Dependency updates

## server-2021-05-01

- Add setting which allows setting a timeout on HTTP requests
  This is configured with the new `REQUEST_TIMEOUT_SECONDS` setting. If a request takes longer
  than this number of seconds a `408 Request Timeout` response will be returned.
- Deprecate [Bintray] service [#6423](https://github.com/badges/shields/issues/6423)
- Support git hash in [nexus] SNAPSHOT version [#6369](https://github.com/badges/shields/issues/6369)
- Replace 4183C4 with blue [#6366](https://github.com/badges/shields/issues/6366)
- [Youtube] Added channel view count and subscriber count badges [#6333](https://github.com/badges/shields/issues/6333)
- Fix Netlify badge by adding new color schema [#6340](https://github.com/badges/shields/issues/6340)
- [REUSE] Add service badges [#6330](https://github.com/badges/shields/issues/6330)
- Dependency updates

## server-2021-04-01

- Use NPM packages to provide fonts instead of Google Fonts [#6274](https://github.com/badges/shields/issues/6274)
- Prevent duplication of parameters in badge examples [#6272](https://github.com/badges/shields/issues/6272)
- Add docs for all types of releases [#6210](https://github.com/badges/shields/issues/6210)
- refresh self-hosting docs [#6273](https://github.com/badges/shields/issues/6273)
- allow missing 'goal' key in [liberapay] badges [#6258](https://github.com/badges/shields/issues/6258)
- use got to push influx metrics [#6257](https://github.com/badges/shields/issues/6257)
- Dependency updates

## server-2021-03-01

- ensure redirect target path is correctly encoded [#6229](https://github.com/badges/shields/issues/6229)
- [SecurityHeaders] Added a possibility for no follow redirects [#6212](https://github.com/badges/shields/issues/6212)
- catch URL parse error in [endpoint] badge [#6214](https://github.com/badges/shields/issues/6214)
- [Homebrew] Add homebrew downloads badge [#6209](https://github.com/badges/shields/issues/6209)
- update [pkgreview] url [#6189](https://github.com/badges/shields/issues/6189)
- Make [Twitch] a social badge [#6183](https://github.com/badges/shields/issues/6183)
- update [flathub] error handling [#6185](https://github.com/badges/shields/issues/6185)
- Add [Testspace] badges [#6162](https://github.com/badges/shields/issues/6162)
- Dependency updates

## server-2021-02-01

- Docs.rs badge (#6098)
- Fix feedz service in case the package page gets paginated (#6101)
- [Bitbucket] Server Adding Auth Tokens and Resolving Pull Request api … (#6076)
- Dependency updates

## server-2021-01-18

- Gotta start somewhere
