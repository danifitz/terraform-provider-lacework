## v0.17.0 (April 05, 2022)

## Features
* feat(AwsEksAudit): Add support for AwsEksAudit apiv2 cloud account integration (#292) (Ross)([4db5abe](https://github.com/lacework/terraform-provider-lacework/commit/4db5abeed889ac73df1066da27c9eedf50447da2))
* feat: add validation to ecr 'limit_num_imgs' (#283) (Darren)([a437790](https://github.com/lacework/terraform-provider-lacework/commit/a437790cf55d93ada23960066d1ed2197ee5fcac))
## Bug Fixes
* fix(docs): Fix aws eks audit log docs (#297) (Ross)([f9ab5cd](https://github.com/lacework/terraform-provider-lacework/commit/f9ab5cd7386c76146122ac15b4932898dad472f6))
* fix: migrate agent access token data source to use v2 api (#288) (Darren)([71cd925](https://github.com/lacework/terraform-provider-lacework/commit/71cd92593098f9b8c2cf3b79d27d25b302c1f15a))
## Documentation Updates
* docs: fix TF registry documentation tree (Salim Afiune Maya)([39cf2d7](https://github.com/lacework/terraform-provider-lacework/commit/39cf2d78d5bc51557de7c5a3054ba276f4e2a723))
* docs: fix typo (#282) (Darren)([deea6dd](https://github.com/lacework/terraform-provider-lacework/commit/deea6dd90d47c82765a0f40320be322783c071ae))
## Other Changes
* chore: update deps (#294) (Darren)([b6f3297](https://github.com/lacework/terraform-provider-lacework/commit/b6f32971e44d74b361c5688077054b6fdbd9c907))
* chore: update go version to 1.18 (#287) (Darren)([4618e3b](https://github.com/lacework/terraform-provider-lacework/commit/4618e3b02f97b15627ddb281c36f5293e0797528))
* chore: deprecate CLI Wiki (Salim Afiune Maya)([156ccaa](https://github.com/lacework/terraform-provider-lacework/commit/156ccaa48fc7fca13f127361934f79dc8eb4d6d7))
* chore: comment out error check in rollback test (#284) (Salim Afiune)([eaed849](https://github.com/lacework/terraform-provider-lacework/commit/eaed849420e5d71664572a5e862c002952b71fd1))
* build(deps): bump github.com/stretchr/testify from 1.7.0 to 1.7.1 (#290) (dependabot[bot])([25059b5](https://github.com/lacework/terraform-provider-lacework/commit/25059b579a33ac0db74a714f843cd7b28f271f80))
* build(deps): bump github.com/gruntwork-io/terratest (#285) (dependabot[bot])([1e8ca59](https://github.com/lacework/terraform-provider-lacework/commit/1e8ca590f6b96691458c391b6b15986be0af4a6d))
* ci: add make cmd for output go tests in junit format (#293) (Darren)([eec76b2](https://github.com/lacework/terraform-provider-lacework/commit/eec76b2b3ef4d0c66baa469d6288c6daec075da8))
* ci: version bump to v0.16.1-dev (Lacework)([3f7eca5](https://github.com/lacework/terraform-provider-lacework/commit/3f7eca57944a51c9f4805fc40a52f06fae92ac19))

## v0.16.0 (March 02, 2022)

## Features
* feat: new lacework_query resource (#266) (Darren)([37377bb](https://github.com/lacework/terraform-provider-lacework/commit/37377bb8d1fb994da331d7bed8571fdce8c4ec7d))
* feat: new lacework_policy resource (#267) (Darren)([ab3efd8](https://github.com/lacework/terraform-provider-lacework/commit/ab3efd8d5cb973dde3036ce2105e0338e86b6ba0))
* feat: add registry notifications to docker v2 resource (#265) (Darren)([1650b9f](https://github.com/lacework/terraform-provider-lacework/commit/1650b9f801be012d89be05d424285cc8d1f1307c))
## Refactor
* refactor: encourage the use of anonymous queries (#280) (Salim Afiune)([b7c2d4c](https://github.com/lacework/terraform-provider-lacework/commit/b7c2d4ce9637606154293bf34101a78c078c4dc7))
* refactor: remove evaluator_id from policy and query resources (#278) (Salim Afiune)([953300a](https://github.com/lacework/terraform-provider-lacework/commit/953300a340879e3648c31180cba9e372047cc091))
## Bug Fixes
* fix: prevent updating evaluator_id on existing queries (#276) (Darren)([85dee76](https://github.com/lacework/terraform-provider-lacework/commit/85dee768fad25e73e0871d0eb80bece916cce134))
## Documentation Updates
* docs: update query and policy resources (#275) (Darren)([b85d686](https://github.com/lacework/terraform-provider-lacework/commit/b85d686d7c35db25ecb03a8422c8397587deef09))
## Other Changes
* build(deps): bump github.com/gruntwork-io/terratest (#277) (dependabot[bot])([1444587](https://github.com/lacework/terraform-provider-lacework/commit/1444587d0ae8b16130015270ebd0b78ad614e3e4))
* build(deps): bump github.com/gruntwork-io/terratest (#271) (dependabot[bot])([edb3af8](https://github.com/lacework/terraform-provider-lacework/commit/edb3af87f74f21d32183eac24c82166a22ac8c18))
* build(deps): bump github.com/gruntwork-io/terratest (#262) (dependabot[bot])([30df648](https://github.com/lacework/terraform-provider-lacework/commit/30df648c42cadffbeaa777e285a9ea39034cbe85))
* ci: version bump to v0.15.1-dev (Lacework)([07ced51](https://github.com/lacework/terraform-provider-lacework/commit/07ced513d675b1493593d6b2df71b0dbfe1c400e))
* test(team_members): use lwdomain to get correct account name (#272) (Darren)([e120def](https://github.com/lacework/terraform-provider-lacework/commit/e120def7f14f533b867fe904610c906ec5168d1e))
* test: skip org test for lw account resource group (#261) (Salim Afiune)([061ada9](https://github.com/lacework/terraform-provider-lacework/commit/061ada9f9c0ecf4821ab1dd9dc7633a9a88db06f))

## v0.15.0 (January 28, 2022)

## Features
* feat(resource): New lacework_vulnerability_exception_container (#253) (Darren)([6903c79](https://github.com/lacework/terraform-provider-lacework/commit/6903c79e6270f5b1dc1e5a06499f4804a3f49ba3))
* feat(resource): New lacework_vulnerability_exception_host (#248) (Darren)([afa657a](https://github.com/lacework/terraform-provider-lacework/commit/afa657aaea7bc17e75d2da61920bf39935fda616))
## Refactor
* refactor: remove expiration time (#254) (Darren)([6bbc742](https://github.com/lacework/terraform-provider-lacework/commit/6bbc7427cee5946a2288369d129250d5f9088abf))
## Documentation Updates
* docs: fix PR template document (#255) (Darren)([bfad072](https://github.com/lacework/terraform-provider-lacework/commit/bfad0729b364ec49fae8b3dc916f4998e52bae24))
* docs: update 'aws' s3/cloudwatch to 'amazon' in documentation (#256) (Darren)([1a3bece](https://github.com/lacework/terraform-provider-lacework/commit/1a3bece85234560450e382ba4f2a5e01492959ef))
## Other Changes
* build(deps): bump github.com/gruntwork-io/terratest (#246) (dependabot[bot])([94ff17f](https://github.com/lacework/terraform-provider-lacework/commit/94ff17f1292c4e4348a70340985b118d9f4888da))
* build(deps): bump github.com/hashicorp/terraform-plugin-sdk/v2 (#251) (dependabot[bot])([8a9dbca](https://github.com/lacework/terraform-provider-lacework/commit/8a9dbcacfe38e26395d915f2f75220e7e8ffda92))
* ci: version bump to v0.14.1-dev (Lacework)([9e9b210](https://github.com/lacework/terraform-provider-lacework/commit/9e9b2109371bb95c508823ec907910c596cf918d))

## v0.14.0 (December 17, 2021)

## Features
* feat: new lacework_team_member resource (#245) (vatasha)([cb4e69a](https://github.com/lacework/terraform-provider-lacework/commit/cb4e69a4ceb3138d9874589b934d502ecfd3f776))
## Refactor
* refactor: enable non-OS Package Support by default (#249) (robewedd)([7c85cbb](https://github.com/lacework/terraform-provider-lacework/commit/7c85cbbd029ac7e88b3cc6184b9a60d6b252372d))
## Bug Fixes
* fix: remove apiIntgKey from resourceLaceworkAlertChannelPagerDutyRead (#247) (Darren)([ad170ef](https://github.com/lacework/terraform-provider-lacework/commit/ad170efcd17995b8c9957631ae947913dc259ffb))
## Other Changes
* ci: version bump to v0.13.1-dev (Salim Afiune Maya)([e5800e0](https://github.com/lacework/terraform-provider-lacework/commit/e5800e0bac24598319d95945321d7e424a7adfff))
* test: Use v2 endpoints in tests (#244) (Darren)([ba89973](https://github.com/lacework/terraform-provider-lacework/commit/ba899737c17d37ce180b24799836caf21c8c362d))

## v0.13.0 (December 06, 2021)

## Features
* feat(resource): New lacework_report_rule (#237) (Darren)([c2928b6](https://github.com/lacework/terraform-provider-lacework/commit/c2928b612dc7e1db2c676bbd9abcf4f2dce7348e))
## Documentation Updates
* docs: mention new GAR and GCR Modules (#229) (Salim Afiune)([30d1c0a](https://github.com/lacework/terraform-provider-lacework/commit/30d1c0a8b5e305ccf27ffc8e31f9b541ad78033a))
* docs: Add environment variables for Windows (#228) (Salim Afiune)([bd4ee0c](https://github.com/lacework/terraform-provider-lacework/commit/bd4ee0cdd86da76582fd870aa3fc2346c22b30d4))
## Other Changes
* chore: run make go-vendor (#241) (Darren)([3dd3649](https://github.com/lacework/terraform-provider-lacework/commit/3dd364912e64c9fc44242ccbf97030ff382535a4))
* ci: run vendor commands after dep update (#227) (Salim Afiune)([8b18fb8](https://github.com/lacework/terraform-provider-lacework/commit/8b18fb8837345234bd074579592c5c64741fe771))
* ci: version bump to v0.12.3-dev (Lacework)([528641b](https://github.com/lacework/terraform-provider-lacework/commit/528641ba9dbd7dd23a1c506bb427c829ec0deff1))
* test: disable failing alert rule tests (#240) (Darren)([4247ec9](https://github.com/lacework/terraform-provider-lacework/commit/4247ec97aead69d5ac4fe5e2f2ece61c1dfa6f67))
* test: create unique names for resource groups integration tests (#239) (Darren)([ed382b1](https://github.com/lacework/terraform-provider-lacework/commit/ed382b1e3ad1a394c7349e043a5c694012540657))
* test: fix alert-rule tests (#236) (Darren)([c92b8da](https://github.com/lacework/terraform-provider-lacework/commit/c92b8da3cf0b0b5f80a8c46859f76ebd71c65394))
* test: fix s3 alert channel integration test (#224) (vatasha)([5f2cad5](https://github.com/lacework/terraform-provider-lacework/commit/5f2cad56af47926305085846c8c5fabf0b5b7405))

## v0.12.2 (November 10, 2021)

## Bug Fixes
* fix: Deprecate channels attribute in favor of alert_channels (#225) (Darren)([ba30502](https://github.com/lacework/terraform-provider-lacework/commit/ba305020a31cf486a4baa1bf7079b65b446822b4))
* fix: Suppress diff on sensitive values (#221) (Darren)([4a569cd](https://github.com/lacework/terraform-provider-lacework/commit/4a569cd485534d54ce4938e283ad267e9252fe4e))
## Other Changes
* style: fix linting and run it in CI(#222) (Darren)([725649a](https://github.com/lacework/terraform-provider-lacework/commit/725649ac626f52bfc1036475a37d8616c864808f))
* ci: version bump to v0.12.2-dev (Lacework)([cc7609b](https://github.com/lacework/terraform-provider-lacework/commit/cc7609bcc7aece7f4e28f4192c54206ba72132a8))

## v0.12.1 (October 29, 2021)

## Documentation Updates
* docs: Fix alert rule doc summary (#218) (Darren)([e662841](https://github.com/lacework/terraform-provider-lacework/commit/e662841024f340ae4b8d3ee4e607dcd8ad104834))
* docs: Fix alert rule page name (#216) (Darren)([d6f1c3b](https://github.com/lacework/terraform-provider-lacework/commit/d6f1c3bc03e425a6a1565758e73df92667a8c948))
## Other Changes
* ci: improve unit and integration test output (#217) (Salim Afiune)([518b106](https://github.com/lacework/terraform-provider-lacework/commit/518b106f558ebf725e8a5297889d07ae0cd98cab))
* ci: version bump to v0.12.1-dev (Lacework)([4eefa67](https://github.com/lacework/terraform-provider-lacework/commit/4eefa67191d958448e31016bc7bacbb106662876))

## v0.12.0 (October 29, 2021)

## Features
* feat(resource): New lacework_alert_rule (#211) (Darren)([c62e1e1](https://github.com/lacework/terraform-provider-lacework/commit/c62e1e17d684222333ea9c986cb71f7f1ee6c586))
## Bug Fixes
* fix: Migrate Jira Cloud and Jira Server to API v2 (#212) (vatasha)([2382376](https://github.com/lacework/terraform-provider-lacework/commit/2382376940504453576ab1298f21c3e45021289c))
* fix: Migrate IbmQRadar alert channel(v2) (#208) (Darren)([2699390](https://github.com/lacework/terraform-provider-lacework/commit/2699390cfd2eb11b7e638edc1d69ac7982698f7f))
* fix: Migrate PagerDuty alert channel(v2) (#209) (Darren)([29057fc](https://github.com/lacework/terraform-provider-lacework/commit/29057fc71c9eb90af223c6fea740978c5feed318))
* fix: Migrate NewRelic Insights alert channel(v2) (#210) (Darren)([553d395](https://github.com/lacework/terraform-provider-lacework/commit/553d395863f8171d6da23add44993984da305e02))
* fix: Migrate ServiceNow alert channel(v2) (#206) (Darren)([09a413e](https://github.com/lacework/terraform-provider-lacework/commit/09a413ea6757f07662d26af8262d2290858df28e))
* fix: Migrate Splunk alert channel(v2) (#205) (Darren)([7cc2d5e](https://github.com/lacework/terraform-provider-lacework/commit/7cc2d5e59d17bc1381ed8c227b48ce776ab4c474))
* fix: Migrate GCP Pub Sub alert channel to API v2 (#207) (vatasha)([cd3da9a](https://github.com/lacework/terraform-provider-lacework/commit/cd3da9a31c58f247d35382288af50bb35d86ab6c))
## Documentation Updates
* docs: fix webhook alert channel example (#204) (Salim Afiune)([fba343b](https://github.com/lacework/terraform-provider-lacework/commit/fba343bb8d8d62f2b2e6abf4655bda69855c8d83))
## Other Changes
* build(deps): bump github.com/gruntwork-io/terratest (#196) (dependabot[bot])([6b94df3](https://github.com/lacework/terraform-provider-lacework/commit/6b94df3d8bdb9eb79a41d10f85ef4911c14a4e71))
* ci: fix release pipeline (#214) (Salim Afiune)([bde019d](https://github.com/lacework/terraform-provider-lacework/commit/bde019d4dfa7cb98717d7179487080cb4a576cee))
* ci: version bump to v0.11.3-dev (Lacework)([7551e99](https://github.com/lacework/terraform-provider-lacework/commit/7551e99525ca9395ebedb53dc5e1a6a67625ba02))
* test: fix tests for alert_rule resource (#213) (Salim Afiune)([0f7aa5b](https://github.com/lacework/terraform-provider-lacework/commit/0f7aa5b513e95081e9e875fc5871440462e8ab1c))

## v0.11.2 (October 12, 2021)

## Bug Fixes
* fix: migrate Webhook alert channel(v2) (#188) (Darren)([a27565c](https://github.com/lacework/terraform-provider-lacework/commit/a27565c7a94a6faac34f1389b56d79a34dbd3a29))
* fix: migrate VictorOps alert channel(v2) (#192) (Darren)([517e587](https://github.com/lacework/terraform-provider-lacework/commit/517e58742b1371fe6406c24b66431793ab107b99))
* fix: migrate Microsoft Teams Alert Channels to API v2 (Salim Afiune Maya)([36a78e3](https://github.com/lacework/terraform-provider-lacework/commit/36a78e3473aa3f92a1acc20bc7c00347f87a361b))
* fix: migrate Cisco webex alert channel to API v2 (#193) (vatasha)([66e8251](https://github.com/lacework/terraform-provider-lacework/commit/66e8251d8fc252ee7313703bb4a6fde030cca912))
* fix: remove alert channel properly if test fails (#199) (Salim Afiune)([9e13d58](https://github.com/lacework/terraform-provider-lacework/commit/9e13d58b3af1bf1e5fc66575747c86b58142aaca))
## Other Changes
* chore(deps): update lacework/go-sdk from main (Salim Afiune Maya)([5d277f9](https://github.com/lacework/terraform-provider-lacework/commit/5d277f9c87b727c865feee54c6eedd90f6c99c46))
* ci: fix release pipeline (#202) (Salim Afiune)([a37168a](https://github.com/lacework/terraform-provider-lacework/commit/a37168a1949c1c0c912ec58696c3d3ad23dd6809))
* ci: version bump to v0.11.2-dev (Lacework)([7de4f58](https://github.com/lacework/terraform-provider-lacework/commit/7de4f580e8a43900b3b6f5afc2fe51b49e2d6a5a))
* test: fix tf output values (#198) (Darren)([a4af709](https://github.com/lacework/terraform-provider-lacework/commit/a4af709c3eabe6471bc3f9e0258a30201231ad82))

## v0.11.1 (October 11, 2021)

## Bug Fixes
* fix: increase timeout from 60 to 125 seconds (#194) (Salim Afiune)([ff3819e](https://github.com/lacework/terraform-provider-lacework/commit/ff3819e782167d3a7d987b71018124c2ddedf6ec))
* fix: Migrate Datadog alert channel to API v2 (#189) (vatasha)([fd38f37](https://github.com/lacework/terraform-provider-lacework/commit/fd38f37ca5e3851a08c7d2bd522cdaf5e3d202c5))
* fix: migrate AWS Cloudwatch alert channel to API v2 (#186) (vatasha)([eeb55a7](https://github.com/lacework/terraform-provider-lacework/commit/eeb55a7000e214374abcb1bf930ee724ba588a84))
## Other Changes
* chore(deps): update lacework/go-sdk from main (Salim Afiune Maya)([37245e8](https://github.com/lacework/terraform-provider-lacework/commit/37245e8e5d0ccc44007f38e69335263887c45f92))
* build(deps): bump github.com/hashicorp/terraform-plugin-sdk/v2 (#176) (dependabot[bot])([5800a22](https://github.com/lacework/terraform-provider-lacework/commit/5800a228802f076a4dd584e2022d3bf56a874cae))
* build(deps): bump github.com/gruntwork-io/terratest (#187) (dependabot[bot])([994389b](https://github.com/lacework/terraform-provider-lacework/commit/994389b0cbbdc1032f2322cf3cfb89e7a3b20444))
* ci: fix downgrading go packages (Salim Afiune Maya)([6eb22dc](https://github.com/lacework/terraform-provider-lacework/commit/6eb22dc1adaf1d2f31f1d2987cd3b0af43f14fed))
* ci: version bump to v0.11.1-dev (Lacework)([6d86c83](https://github.com/lacework/terraform-provider-lacework/commit/6d86c837086919b3d823993396647055dfd8f50b))

## v0.11.0 (October 01, 2021)

## Features
* feat: Add new field non_os_package_support to ECR resource (#175) (Darren)([f150be8](https://github.com/lacework/terraform-provider-lacework/commit/f150be8ad4163ace9acefa3244145aaed22f7c75))
* feat: Add new field non_os_package_support to GHCR resource (#178) (Darren)([e72b5eb](https://github.com/lacework/terraform-provider-lacework/commit/e72b5eb702385103a9384dc10ec37255a9d98168))
* feat: Add new field non_os_package_support to GAR resource (#179) (Darren)([27b6c70](https://github.com/lacework/terraform-provider-lacework/commit/27b6c70bdddf154f8171e5bf71d929bcea015ca4))
## Documentation Updates
* docs: update multiple aliases for sub-accounts (#172) (robewedd)([0763028](https://github.com/lacework/terraform-provider-lacework/commit/0763028b8b4d4a5df29ab339003ba8ba5a680d91))
## Other Changes
* ci: fix release pipeline by running make prepare (#183) (Salim Afiune)([fb4d3db](https://github.com/lacework/terraform-provider-lacework/commit/fb4d3db24cab8a94e8e8ccaf8086dd44bae3667d))
* ci: version bump to v0.10.1-dev (Lacework)([9645ee1](https://github.com/lacework/terraform-provider-lacework/commit/9645ee118106c2358658c955bc50f892cabb0153))
* test: fix integration tests (#180) (Darren)([1eb35e9](https://github.com/lacework/terraform-provider-lacework/commit/1eb35e9fee926dab0caa25e9a55bae95a3a47076))

## v0.10.0 (September 27, 2021)

## Features
* feat: New Lw Account Resource Group Terraform Resource (#171) (Darren)([8425534](https://github.com/lacework/terraform-provider-lacework/commit/84255348e6e68986ccdf773ce73219990032dac5))
* feat: New Container Resource Group Terraform Resource (#170) (Darren)([ffc35cf](https://github.com/lacework/terraform-provider-lacework/commit/ffc35cf73537b0968619831e873d92d0ca6df4da))
* feat: New Machine Resource Group Terraform Resource (#169) (Darren)([4433d9a](https://github.com/lacework/terraform-provider-lacework/commit/4433d9a10367c49b412a399d5358f96bb95b51f5))
## Refactor
* refactor: switch over to use APIv2 by default (#173) (Salim Afiune)([6ebd5fc](https://github.com/lacework/terraform-provider-lacework/commit/6ebd5fc0b3ebcc75fa00986633dfab66a35da1e4))
## Documentation Updates
* docs: Add contributing documentation (#165) (Darren)([55a4408](https://github.com/lacework/terraform-provider-lacework/commit/55a44080a0f2901500f5d791be357a7b163019b6))
## Other Changes
* ci: version bump to v0.9.3-dev (Lacework)([f619f25](https://github.com/lacework/terraform-provider-lacework/commit/f619f2572e3812b6db6257ffafebe8d4c7f4ec5f))

## v0.9.2 (September 23, 2021)

## Bug Fixes
* fix: Fix return empty array when casting limit_by fields (#167) (Darren)([329a00c](https://github.com/lacework/terraform-provider-lacework/commit/329a00cc21e3b2729e933df3fa271ad4a4b8fa29))
## Other Changes
* build(deps): bump github.com/gruntwork-io/terratest (#164) (dependabot[bot])([2d9be48](https://github.com/lacework/terraform-provider-lacework/commit/2d9be48831618f6cbba6a49be3c0e3f04e2f8eb6))
* ci: version bump to v0.9.2-dev (Lacework)([80e0cb8](https://github.com/lacework/terraform-provider-lacework/commit/80e0cb830d18801399381adf39d29d0893a8cc45))

## v0.9.1 (September 13, 2021)

## Documentation Updates
* docs: standardize mention of 'ids' (#162) (Salim Afiune)([8591935](https://github.com/lacework/terraform-provider-lacework/commit/8591935b8372dec0cdcd93575074b62356f48841))
* docs: fix html markdown indentation (#161) (Darren)([a8e735a](https://github.com/lacework/terraform-provider-lacework/commit/a8e735a741795744281f04611cfe69e7ab9e25cb))
## Other Changes
* ci: version bump to v0.9.1-dev (Lacework)([ec0b0b7](https://github.com/lacework/terraform-provider-lacework/commit/ec0b0b7cadd8be729ee167443da34de237f40c6f))

## v0.9.0 (September 10, 2021)

## Features
* feat(resource): New lacework_resource_group_azure (#158) (Darren)([6ab2f0c](https://github.com/lacework/terraform-provider-lacework/commit/6ab2f0c75b50e533f987bd31e51ce90ef052d503))
* feat(resource): New lacework_resource_group_gcp (#156) (Darren)([d88a7b9](https://github.com/lacework/terraform-provider-lacework/commit/d88a7b9671dc759c45e56ac2877694dfead7e278))
* feat: gracefully handle account config <ACCOUNT>.lacework.net (#157) (Salim Afiune)([cb32670](https://github.com/lacework/terraform-provider-lacework/commit/cb326706d479f5f405dd30c6414ed271e5f38bad))
* feat: Add Non-OS Package support for GCR, DockerV2, and DockerHub (#152) (Andre Elizondo)([96b4df8](https://github.com/lacework/terraform-provider-lacework/commit/96b4df89fcb52b1cffe6457e5db3df85e219a994))
* feat(resource): New lacework_resource_group_aws (#155) (Darren)([ca4eb3d](https://github.com/lacework/terraform-provider-lacework/commit/ca4eb3d3556b7dfad07ec749296cc67d76ac8be5))
* feat: new Github Container Registry (GHCR) resource (#143) (Darren)([7301f74](https://github.com/lacework/terraform-provider-lacework/commit/7301f7461d332d50184868d0ed6450b12d0a5bbb))
## Bug Fixes
* fix: enable parsing internal accounts (#159) (Salim Afiune)([bb72fb4](https://github.com/lacework/terraform-provider-lacework/commit/bb72fb410b7a4ed5ef1ae2851fcbd0bea17d825b))
## Other Changes
* build(deps): bump github.com/hashicorp/terraform-plugin-sdk/v2 (#154) (dependabot[bot])([0e749a3](https://github.com/lacework/terraform-provider-lacework/commit/0e749a3e4b89c3f61ec5ea14df1649bade666e3a))
* build(deps): bump github.com/gruntwork-io/terratest (#151) (dependabot[bot])([3a8eaed](https://github.com/lacework/terraform-provider-lacework/commit/3a8eaed311a38b42e64d6b3050bd19bd6c605b62))
* ci: version bump to v0.8.2-dev (Lacework)([b998522](https://github.com/lacework/terraform-provider-lacework/commit/b998522ae2ed362f64ed53736999b8fd4a6f1187))

## v0.8.1 (August 18, 2021)

## Bug Fixes
* fix: migrate AWS S3 Alert Channels to API v2 (Salim Afiune Maya)([6fa97ac](https://github.com/lacework/terraform-provider-lacework/commit/6fa97ac001549861526e90dbcf788ae6dab91c9d))
* fix: migrate Slack Alert Channels to use API v2 (Salim Afiune Maya)([d84cc51](https://github.com/lacework/terraform-provider-lacework/commit/d84cc51a1f72e5bd7575f32b1609a1d4766284b0))
## Documentation Updates
* docs: improve documentation for org account_mappings (#146) (Salim Afiune)([edbc4b7](https://github.com/lacework/terraform-provider-lacework/commit/edbc4b7ab0704bb05dd048ce936fe71fec2a6356))
## Other Changes
* chore: fix Go deps (#149) (Salim Afiune)([db496ee](https://github.com/lacework/terraform-provider-lacework/commit/db496eef7423a101b1c58521e97f81a5ba8bd14e))
* chore(deps): update github.com/lacework/go-sdk (Salim Afiune Maya)([a5f3fbe](https://github.com/lacework/terraform-provider-lacework/commit/a5f3fbe28f511cf1e69e92154b2cb785b40afe30))
* build(deps): bump github.com/gruntwork-io/terratest (#141) (dependabot[bot])([d2d7f2a](https://github.com/lacework/terraform-provider-lacework/commit/d2d7f2a71516cca785fe32b9fcb23070a4a8108c))
* ci: version bump to v0.8.1-dev (Lacework)([5041c63](https://github.com/lacework/terraform-provider-lacework/commit/5041c63f63a74125e7b3c456758d2a1c34ba2bce))

## v0.8.0 (August 06, 2021)

## Features
* feat: Test Alert Channels during TF Create (#133) (Darren)([3df183d](https://github.com/lacework/terraform-provider-lacework/commit/3df183d4f377e2673e9992763ee054da5239ff29))
* feat: new Google Artifact Registry (GAR) resource (#135) (Salim Afiune)([39e0a2a](https://github.com/lacework/terraform-provider-lacework/commit/39e0a2a168e334933ddc6d562f6aaa0c4dfb12cc))
## Refactor
* refactor: test Alert Channels on create and modify (#138) (Salim Afiune)([d58888a](https://github.com/lacework/terraform-provider-lacework/commit/d58888ac7c72c9b6372cb296350c645e93ada5e6))
## Bug Fixes
* fix(lint): missing declaration or govcloud_ct resource (Salim Afiune Maya)([5653228](https://github.com/lacework/terraform-provider-lacework/commit/565322829be14fcf5374beb7b27e120b843b88b6))
* fix(importer): use new Get() v2 func (Salim Afiune Maya)([cd58f1e](https://github.com/lacework/terraform-provider-lacework/commit/cd58f1ecc1becd12b111ae9198c955e8e84e0e86))
## Other Changes
* chore(deps): update github.com/lacework/go-sdk to v0.12.0 (Salim Afiune Maya)([76fa9e7](https://github.com/lacework/terraform-provider-lacework/commit/76fa9e7220aec7b5a00c5ca9e917f987c590559e))
* chore: fixed deps by running make go-vendor (#136) (Salim Afiune)([e359b88](https://github.com/lacework/terraform-provider-lacework/commit/e359b8818db20cffb47b5de114abbc887e94214b))
* build(deps): bump github.com/gruntwork-io/terratest (#130) (dependabot[bot])([4a47a07](https://github.com/lacework/terraform-provider-lacework/commit/4a47a07ab56772064b543ce5d6b13479ced979f3))
* ci: sign lacework-releng commits (#132) (Salim Afiune)([495a264](https://github.com/lacework/terraform-provider-lacework/commit/495a264b4b772ae8d73f0b5184a08cef9b41ead5))
* ci: make clean-test directive (#131) (Salim Afiune)([8d1c9af](https://github.com/lacework/terraform-provider-lacework/commit/8d1c9afa44c9e95e3843756620a5ec5245bff791))
* ci: clean left over files during integration test (#129) (Salim Afiune)([d777278](https://github.com/lacework/terraform-provider-lacework/commit/d77727841592c032c9bf855ed9e9ad6be1c0cab9))

## v0.7.0 (July 27, 2021)

## Features
* feat: new lacework_alert_channel_email resource (Salim Afiune Maya)([0cdb690](https://github.com/lacework/terraform-provider-lacework/commit/0cdb690f7188aac8af9fea7741b7df6509f9badb))
## Bug Fixes
* fix: drifts with lacework_alert_channel_datadog (Salim Afiune Maya)([be38f69](https://github.com/lacework/terraform-provider-lacework/commit/be38f69dfc16f12e0afad782397288310efb37d2))
## Documentation Updates
* docs: update lacework_alert_channel_datadog resource (Salim Afiune Maya)([99cedc7](https://github.com/lacework/terraform-provider-lacework/commit/99cedc701f9f7715c38a243e694b756253634c9c))
* docs: new lacework_alert_channel_email resource (Salim Afiune Maya)([844065a](https://github.com/lacework/terraform-provider-lacework/commit/844065a87a7d7aa96fd0c23427399dc40197366d))
## Other Changes
* chore(deps): update github.com/lacework/go-sdk to v0.11.0 (#126) (Salim Afiune)([5dbefc4](https://github.com/lacework/terraform-provider-lacework/commit/5dbefc44acba06c70902f5e1775af31b1413e022))
* chore(deps): update github.com/lacework/go-sdk (Salim Afiune Maya)([e282b3e](https://github.com/lacework/terraform-provider-lacework/commit/e282b3ea850a0b5b3aebe333e9032a159122998e))
* ci: fix dependencies (#127) (Salim Afiune)([9cbef84](https://github.com/lacework/terraform-provider-lacework/commit/9cbef84ed82dd54fa68e9b8a9675ed0276ede025))
* ci: fix integration tests (Salim Afiune Maya)([9a6f1e2](https://github.com/lacework/terraform-provider-lacework/commit/9a6f1e2764d10e489fd65a160ad940048932bea2))
* test: e2e testing with terratest (#121) (Darren)([8bc0bd9](https://github.com/lacework/terraform-provider-lacework/commit/8bc0bd9e6b970d2a071698f08d0c0a1f61d2fba7))

## v0.6.0 (July 21, 2021)

## Features
* feat: add provider organization argument to access org data sets (Salim Afiune Maya)([5aa0968](https://github.com/lacework/terraform-provider-lacework/commit/5aa096816bdd03c1ac9386df6a8ff8b5a6374c78))
* feat: add support for multiple tags and labels (#114) (Salim Afiune)([5cf4100](https://github.com/lacework/terraform-provider-lacework/commit/5cf41004b97820bdba90bd263a932daf17e4f724))
* feat: add subaccount arg for org admins (#112) (Salim Afiune)([1d6d7c1](https://github.com/lacework/terraform-provider-lacework/commit/1d6d7c1fc0e36f3179d2b7b428475819290c69dc))
## Refactor
* refactor: use V2 CloudAccounts for integration_aws_ct resource (Salim Afiune Maya)([0c1cc05](https://github.com/lacework/terraform-provider-lacework/commit/0c1cc05b1c29c5abc81a872ba2441f51652cb50d))
## Other Changes
* chore(deps): update github.com/lacework/go-sdk (Salim Afiune Maya)([e4aa1da](https://github.com/lacework/terraform-provider-lacework/commit/e4aa1daf365a433795b0d2eccb6fd0db7ea07b66))
* build(deps): bump github.com/lacework/go-sdk to v0.10.1 (#122) (Salim Afiune)([0d158ce](https://github.com/lacework/terraform-provider-lacework/commit/0d158cedfc9fa966c3939360c2c06c1c2e0a2b69))
* build(deps): bump github.com/hashicorp/terraform-plugin-sdk/v2 (#120) (dependabot[bot])([c1201ba](https://github.com/lacework/terraform-provider-lacework/commit/c1201ba44201f031470507ee6ccf1fab7c487b1a))
* build(deps): bump github.com/lacework/go-sdk from 0.8.0 to 0.9.1 (#117) (dependabot[bot])([23bb9ce](https://github.com/lacework/terraform-provider-lacework/commit/23bb9ce2cdb9615b1d93fc143cb51574aee4be57))
* ci: pin Go tooling to specific versions (#115) (Salim Afiune)([f3db1cc](https://github.com/lacework/terraform-provider-lacework/commit/f3db1cc3b628e56df4a9f857c3a12b86a75f61fe))

## v0.5.0 (May 27, 2021)

## Features
* feat: New AWS CouldTrail for AWS GovCloud resource (#108) (Darren)([17ff48f](https://github.com/lacework/terraform-provider-lacework/commit/17ff48fcdc982497391b6d6f48c186def3c19185))
* feat: New AWS Config for AWS GovCloud resource (#107) (Darren)([d5e0d2e](https://github.com/lacework/terraform-provider-lacework/commit/d5e0d2e0d4e04e77d8c1237d65d90f1446d29be0))
## Documentation Updates
* docs: update GovCloud registry documentation (#109) (Salim Afiune)([1efa3a8](https://github.com/lacework/terraform-provider-lacework/commit/1efa3a8563364806a8a1f5f320f0556348c6a3b8))
## Other Changes
* ci: fix prepare-release job (#110) (Salim Afiune)([c69c3ec](https://github.com/lacework/terraform-provider-lacework/commit/c69c3ec2644a12e0cb06e7bbb02880c16d85f1e4))

## v0.4.1 (May 18, 2021)

## Other Changes
* build: Update go version to 1.16 (#102) (Darren)([a38f559](https://github.com/lacework/terraform-provider-lacework/commit/a38f55961c89bf61a02c1c1547058fe79bafce45))
* ci: fix go deps (#104) (Darren)([3e557ae](https://github.com/lacework/terraform-provider-lacework/commit/3e557ae8cdafe30ed203734eb8bed9fb03000daa))

## v0.4.0 (May 12, 2021)

## Features
* feat: understand Lacework CLI config v2 (Salim Afiune Maya)([49ba175](https://github.com/lacework/terraform-provider-lacework/commit/49ba175a3ba1b8d06cea387460e2b5c715360935))
## Other Changes
* chore(deps): update github.com/lacework/go-sdk (Salim Afiune Maya)([ac6f892](https://github.com/lacework/terraform-provider-lacework/commit/ac6f892e1de412c01c5bebc1476aac424a74facc))
* build(deps): bump github.com/hashicorp/terraform-plugin-sdk/v2 (#96) (dependabot[bot])([84796e9](https://github.com/lacework/terraform-provider-lacework/commit/84796e9e6041dd73b282a8a721f3da60a76868a7))
* ci: run make prepare (#100) (Salim Afiune)([349d26f](https://github.com/lacework/terraform-provider-lacework/commit/349d26f4949a4aae32f411e7cb7810262bb1cd9c))
* ci: remove CircleCI completely (Salim Afiune Maya)([1fd808a](https://github.com/lacework/terraform-provider-lacework/commit/1fd808aa30f76d0a6d3f2671d2d531fad0582a11))
* ci: update release.sh script to work with CodeFresh (Salim Afiune Maya)([bec5242](https://github.com/lacework/terraform-provider-lacework/commit/bec52425b537a377228528fbb9729d45d08f9ed5))

## v0.3.2 (April 28, 2021)

## Other Changes
* build(deps): bump github.com/lacework/go-sdk from 0.4.0 to 0.6.0 (#95) (dependabot[bot])([b66ceca](https://github.com/lacework/terraform-provider-lacework/commit/b66ceca787313251040d1ae1508c3057116d67fe))
* build(deps): bump github.com/lacework/go-sdk from 0.2.22 to 0.4.0 (#94) (dependabot[bot])([d7c4852](https://github.com/lacework/terraform-provider-lacework/commit/d7c4852927bab0e152b614a9f0a427f4f7889ecf))

## v0.3.1 (March 16, 2021)

## Documentation Updates
* docs(website): fix ECR Module example (#88) (Salim Afiune)([f0a02f2](https://github.com/lacework/terraform-provider-lacework/commit/f0a02f2587a451ae1efad3040d8389f4265ea9d5))

## v0.3.0 (March 16, 2021)

## Features
* feat: lacework_integration_ecr support for IAM Roles (Salim Afiune Maya)([42bfbae](https://github.com/lacework/terraform-provider-lacework/commit/42bfbae107390e959a6684e6322e25ba37e42777))
## Bug Fixes
* fix: lacework_integration_ecr from SCHEMA changes (Salim Afiune Maya)([5a52b98](https://github.com/lacework/terraform-provider-lacework/commit/5a52b98823d1fb1c8942d4c9c8bbaafa952e4eab))
## Documentation Updates
* docs: update ECR argument descriptions (Salim Afiune Maya)([dea6d49](https://github.com/lacework/terraform-provider-lacework/commit/dea6d49019047eb925b2440c0cad1cf46e2c71f0))
* docs(website): update lacework_integration_ecr resource (Salim Afiune Maya)([3e07cd4](https://github.com/lacework/terraform-provider-lacework/commit/3e07cd47b469189e159bdca2c7514b52d6bbddd3))
## Other Changes
* chore(deps): update github.com/lacework/go-sdk (Salim Afiune Maya)([987e527](https://github.com/lacework/terraform-provider-lacework/commit/987e527b8263a519c32c8ca215b8e50cec8cbb30))
* ci: increase timeout of the build step to 30m (Salim Afiune Maya)([b86e6c7](https://github.com/lacework/terraform-provider-lacework/commit/b86e6c7c9e313165a8050020995145488e057c7d))

## v0.2.14 (March 08, 2021)

## Features
* feat: retry mechanism for all cloud resources (#81) (Salim Afiune)([61893af](https://github.com/lacework/terraform-provider-lacework/commit/61893afaedeeb407e5b9f20ef7678b64c37965f4))
* feat: Add support for ServiceNow Alert custom JSON template (#78) (Darren)([a315965](https://github.com/lacework/terraform-provider-lacework/commit/a3159658bda69fc7b54bde758734af51151a6e0a))
## Documentation Updates
* docs(website): add missing retries argument (#83) (Salim Afiune)([0df8c10](https://github.com/lacework/terraform-provider-lacework/commit/0df8c10da7f108bf5c5d669a7eada3906add7391))
* docs: Add custom_template_file field to Service Now docs (Darren Murray)([428aaad](https://github.com/lacework/terraform-provider-lacework/commit/428aaad94aa2210243d43e65a32a4ab2981d8608))
## Other Changes
* chore: Update go-sdk dependencies (Darren Murray)([d0ebfc5](https://github.com/lacework/terraform-provider-lacework/commit/d0ebfc580025e03c03190325edd2ce9cdea1995e))
* chore: Update terraform-plugin-sdk to v2 (#79) (Darren)([ec8299f](https://github.com/lacework/terraform-provider-lacework/commit/ec8299fcee941efdc0020dae78889ad7656c2752))
* build(deps): bump github.com/hashicorp/terraform-plugin-sdk/v2 (#80) (dependabot[bot])([d3f6fd7](https://github.com/lacework/terraform-provider-lacework/commit/d3f6fd71bbf8dbdc9c0026c5e2dcaba7a42e2017))
* build(deps): bump github.com/stretchr/testify from 1.6.1 to 1.7.0 (#75) (dependabot[bot])([70204ea](https://github.com/lacework/terraform-provider-lacework/commit/70204eaf6aa64bd9e76799f8a03c3110c637ff2f))
* ci: delete 'master' branch (#84) (Salim Afiune)([8012b0b](https://github.com/lacework/terraform-provider-lacework/commit/8012b0b49bb6acf7743abdcc1614e332a6dda14c))

## v0.2.13 (February 19, 2021)

## Features
* feat: new IBM QRadar alert channel resource (#76) (Darren)([25e6594](https://github.com/lacework/terraform-provider-lacework/commit/25e65940b55ada83430ccada210ef1e10eb9a87b))
* feat: New Relic Insights alert channel resource (#73) (Darren)([5d7877a](https://github.com/lacework/terraform-provider-lacework/commit/5d7877a9da5155cde1da58de00cbc37cb789f4e9))
* feat: New Victor Ops alert channel resource (#71) (Darren)([641f7cd](https://github.com/lacework/terraform-provider-lacework/commit/641f7cda144eb919abefb6c7b49b93e95384e47c))
* feat: New Cisco Webex alert channel resource (#69) (Darren)([f6e9f8d](https://github.com/lacework/terraform-provider-lacework/commit/f6e9f8d16a026185d142b13546dff8c7f1f286fb))
* feat: new Microsoft Teams alert channel resource (#68) (Darren)([5e4f21f](https://github.com/lacework/terraform-provider-lacework/commit/5e4f21f90fa9a5624bcfc5bb87cffec087f45aa0))
## Documentation Updates
* doc: create service accounts for GCR integration (#74) (Salim Afiune)([be8fb7f](https://github.com/lacework/terraform-provider-lacework/commit/be8fb7fd8eabca92dcefa2eac3ccaab30fdb5deb))
* docs: fix closing curly brace in code snippet for alert channel s3 data export (#70) (Scott Ford)([68c0de6](https://github.com/lacework/terraform-provider-lacework/commit/68c0de6589612cd89454116a46287c3606ba2324))

## v0.2.12 (February 05, 2021)

## Features
* feat: new Datadog alert channel resource (#66) (Darren)([ec90fc4](https://github.com/lacework/terraform-provider-lacework/commit/ec90fc4d98104cb6940d202a33acbf878d4fc83c))

## v0.2.11 (January 28, 2021)

## Features
* feat: new ServiceNow alert channel resource (#63) (Darren)([568a097](https://github.com/lacework/terraform-provider-lacework/commit/568a097b20f1a503361e383645f8e0f8b17db5e1))
## Bug Fixes
* fix: Add issue_grouping field to gcp pub sub (#62) (Darren)([2b64473](https://github.com/lacework/terraform-provider-lacework/commit/2b6447341fe3d7e963ebb0d2a251f62f13608b03))

## v0.2.10 (January 22, 2021)

## Features
* feat: new lacework_alert_channel_gcp_pub_sub resource (#58) (Darren)([a15e6db](https://github.com/lacework/terraform-provider-lacework/commit/a15e6db2f79f00bd5b2bf47c0b35b365d94a87fb))
## Documentation Updates
* docs: fix typo in aws_ct website resource (#60) (Salim Afiune)([815b09b](https://github.com/lacework/terraform-provider-lacework/commit/815b09b7c3ae4d32daa5b71303325c4af0ff7324))

## v0.2.9 (January 15, 2021)

## Features
* feat: new lacework_alert_channel_splunk resource (#56) (Darren)([b1cd97b](https://github.com/lacework/terraform-provider-lacework/commit/b1cd97be62106bdc465bc30b585fe5f10aaae1a8))

## v0.2.8 (January 05, 2021)

## Features
* feat: new lacework_alert_channel_aws_s3 resource (#52) (Darren)([45e39b2](https://github.com/lacework/terraform-provider-lacework/commit/45e39b20acf8ab7f9090b4de230388c20ce3be51))
## Documentation Updates
* docs: update gcp docs for proper render (Salim Afiune Maya)([159595c](https://github.com/lacework/terraform-provider-lacework/commit/159595c01a7bec557c02d561ce670e198b35892b))
* docs: adding more documentation about GCP resources (#53) (Salim Afiune)([ca42d69](https://github.com/lacework/terraform-provider-lacework/commit/ca42d691807ffc1941f48f5c1e77136c34289e13))
## Other Changes
* ci: send slack notifications to team alias ⭐ (Salim Afiune Maya)([887e173](https://github.com/lacework/terraform-provider-lacework/commit/887e17300bd4bdf3863d754e04157d98d060ea2c))

## v0.2.7 (December 17, 2020)

## Features
* feat(resource): add Webhook integration (#49) (Darren)([6f16fc3](https://github.com/lacework/terraform-provider-lacework/commit/6f16fc33e5e8a732540a855b9517d71252bc253e))
## Other Changes
* chore(deps): update go-sdk to remove automatic trigger (#50) (Salim Afiune)([f7af173](https://github.com/lacework/terraform-provider-lacework/commit/f7af1736c0b8ddc9b757bcb73e669783fb2b9409))
* build: upgrade Go version to 1.15 (#48) (Darren)([65cc622](https://github.com/lacework/terraform-provider-lacework/commit/65cc622beabb042a656a22b4a4ef39f930624740))

## v0.2.6 (December 09, 2020)

## Features
* feat(data-source): new lacework_agent_access_token (Salim Afiune Maya)([6283e63](https://github.com/lacework/terraform-provider-lacework/commit/6283e63a3b29df85525cac3044767edf07a97f58))
* feat(resource): new lacework_agent_access_token (#45) (Salim Afiune)([de8b2cc](https://github.com/lacework/terraform-provider-lacework/commit/de8b2cc5c9727a30cd7915e3f3c0032d8b34771d))
* feat(resource): AWS consolidated CloudTrail support (Salim Afiune Maya)([b232e16](https://github.com/lacework/terraform-provider-lacework/commit/b232e163e612b0790b27493df74eb0ac79a840ce))
## Bug Fixes
* fix(docker): avoid loading non-existing password (Salim Afiune Maya)([5ea1e5d](https://github.com/lacework/terraform-provider-lacework/commit/5ea1e5d6d18db86c72baff9ed40151475964d269))
* fix: only encode mapping account when there is one (Salim Afiune Maya)([aedbee8](https://github.com/lacework/terraform-provider-lacework/commit/aedbee8cdf8e2021ecdd14f4daa64795271eb7af))
## Other Changes
* chore(deps): update github.com/lacework/go-sdk (Salim Afiune Maya)([ad616a6](https://github.com/lacework/terraform-provider-lacework/commit/ad616a6ef57eb4b19581d5284a660fb1dfe383f5))
* ci: improve release notes generation (Salim Afiune Maya)([11e4604](https://github.com/lacework/terraform-provider-lacework/commit/11e4604e4c6d6919c8f3f005f198e531773f5a0b))

## v0.2.5 (October 13, 2020)

## Features
* feat: trigger initial compliance report automatically (#39) (Salim Afiune)([a9f4dae](https://github.com/lacework/terraform-provider-lacework/commit/a9f4dae0e98a600fa9bdff23c78c578a97cee6d7))
## Other Changes
* ci: zip binaries without bin/ (#38) (Salim Afiune)([2d57b92](https://github.com/lacework/terraform-provider-lacework/commit/2d57b92bbf7f514ed9c11d10a47855d095625fcb))
* ci: add date to CHANGELOG.md (#37) (Salim Afiune)([509e4db](https://github.com/lacework/terraform-provider-lacework/commit/509e4dbd0daa88a63666be1c974554ad14e0b9ce))

## 0.2.4 (September 11, 2020)

## New Resources

Management of Container Registry integrations.
* `lacework_integration_docker_hub`: Docker Hub integration
* `lacework_integration_docker_v2`: Docker V2 Registry integration
* `lacework_integration_ecr`: Amazon Container Registry (ECR) integration
* `lacework_integration_gcr`: Google Container Registry (GCR) integration

## Other Changes
* docs(website): update all integration names (Salim Afiune Maya)([13d5259](https://github.com/terraform-providers/terraform-provider-lacework/commit/13d525987ddba9841eb2781b31ca8284911a72f1))
* docs(website): change provider sidebar by grouping (Salim Afiune Maya)([3ca830f](https://github.com/terraform-providers/terraform-provider-lacework/commit/3ca830f04e0fe99bceef169d0b0c5240df8d74dc))
* docs: update Lacework CLI markdown link (Salim Afiune Maya)([94d7ea8](https://github.com/terraform-providers/terraform-provider-lacework/commit/94d7ea852342c1ef4927cd64e154178b3e1edfa0))
* chore: use integration ENUM in log messages (Salim Afiune Maya)([c98ed22](https://github.com/terraform-providers/terraform-provider-lacework/commit/c98ed226a1e60a0ae05a8aef0dde1b0b74c393d0))
* chore: ran terraform fmt for all examples/ (Salim Afiune Maya)([7e5dd1b](https://github.com/terraform-providers/terraform-provider-lacework/commit/7e5dd1b5ccd4a1533d4418f1c0490467990b7972))
* fix(azure): suppress client_secret diff to avoid updates (#25) (Salim Afiune)([6fe5dc5](https://github.com/terraform-providers/terraform-provider-lacework/commit/6fe5dc5d0051cc13e2d00492b607db72fb905b9e))

## 0.2.3 (August 27, 2020)

Both, `lacework_alert_channel_jira_cloud` and `lacework_alert_channel_jira_server` have now
a new optional argument named `custom_template_file` to specify a Custom Template file in JSON
format to populate fields in the new Jira issues.

## 0.2.2 (August 14, 2020)

## New Resources

Management of alert channel integrations:
* `lacework_alert_channel_jira_cloud`: Create and manage Jira Cloud Alert Channel integrations
* `lacework_alert_channel_jira_server`: Create and manage Jira Server Alert Channel integrations

## 0.2.1 (July 24, 2020)

## Bug Fixes
* fix(gcp): detect a change of credentials [#14](https://github.com/terraform-providers/terraform-provider-lacework/pull/14)

## 0.2.0 (July 23, 2020)

## Improvements

Support of additional methods to configure the Lacework provider:
* Static credentials
* Environment variables
* Configuration file

## New Resources

Management of alert channel integrations:
* `lacework_alert_channel_aws_cloudwatch`: Forward alerts to an AWS CloudWatch event bus
* `lacework_alert_channel_pagerduty`: Forward alerts to PagerDuty
* `lacework_alert_channel_slack`: Forward alerts to a Slack channel

## Bug Fixes

* Unable to read inputs from provider [#6](https://github.com/terraform-providers/terraform-provider-lacework/issues/6)
* Avoid updating GCP resources on second `terraform apply` [#4](https://github.com/terraform-providers/terraform-provider-lacework/issues/4)

# 0.1.1 (July 09, 2020)

## Improvements
* Add `User-Agent` header for Lacework API backend metrics

# 0.1.0 (June 02, 2020)

## New Resources

Management of external integrations.
* `lacework_integration_aws_cfg`: AWS configuration integration
* `lacework_integration_aws_ct`:  AWS CloudTrail integration
* `lacework_integration_azure_cfg`: Azure configuratio integration
* `lacework_integration_azure_al`: Azure Activity Log integration
* `lacework_integration_gcp_cfg`: GCP configuration integration
* `lacework_integration_gcp_at`: GCP Audit Log integration

Data source to integrate with the Lacework platform.
* `lacework_api_token`: generates a new Lacework API token

### Importers
All resources have the ability to be imported, for existing
Lacework integrations use the import command:
```bash
$ terraform import lacework_integration_aws_cfg.name <INT_GUID>
```
