# Changelog

All notable changes to this project will be documented in this file. See
[standard-version](https://github.com/conventional-changelog/standard-version) for commit
guidelines.

## 4.0.0 (2024-02-01)

### ⚠ BREAKING CHANGES

- Requires changing build scripts to include css-loader when using indivitual components
- left and right changed into prepend and append. See docs.
- Prop `rightAlignment` is now just `right`, aligning with `b-dropdown.`s props

- Minor fixes

- Missing period in selector

- Fixed missing closing ]

- Minor adjustments

### Features

- **`b-overlay`:** new component `b-overlay`
  ([#4907](https://github.com/bootstrap-vue/bootstrap-vue/issues/4907))
  ([134d64d](https://github.com/bootstrap-vue/bootstrap-vue/commit/134d64d073bb64fecd74ffc521476bfd97a99fc0))
- **b-aspect:** new custom component `<b-aspect>`
  ([#5008](https://github.com/bootstrap-vue/bootstrap-vue/issues/5008))
  ([662c8e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/662c8e0709c8c73fb2119976d1906943cfe6daad))
- **b-avatar:** add `alt` prop for adding alt attribute to image and icon avatars (closes
  [#4990](https://github.com/bootstrap-vue/bootstrap-vue/issues/4990))
  ([#4991](https://github.com/bootstrap-vue/bootstrap-vue/issues/4991))
  ([d1474f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/d1474f28729e4e13ad97b75a87d56f85543d4c96))
- **b-avatar:** add size classes for `sm` and `lg` sizes (closes
  [#5592](https://github.com/bootstrap-vue/bootstrap-vue/issues/5592))
  ([#5768](https://github.com/bootstrap-vue/bootstrap-vue/issues/5768))
  ([942bf31](https://github.com/bootstrap-vue/bootstrap-vue/commit/942bf31546179abce8f0bb8252f8716c85c6de86))
- **b-avatar:** and support for badges on avatars
  ([#5124](https://github.com/bootstrap-vue/bootstrap-vue/issues/5124))
  ([a2e465b](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2e465b6457cabb88e42bcefd86a86e36c4602de))
- **b-avatar:** if img `src` fails to load, show icon or text or fallback icon
  ([#5064](https://github.com/bootstrap-vue/bootstrap-vue/issues/5064))
  ([5fc5771](https://github.com/bootstrap-vue/bootstrap-vue/commit/5fc5771deaffb5f0d4c14a5f2e93d86f2c0d3871))
- **b-avatar:** if img `src` fails to load, then show icon, text or fallback icon
  ([#5079](https://github.com/bootstrap-vue/bootstrap-vue/issues/5079))
  ([ed6704d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed6704d0971ade485393b7f711f05d93ca42ebc3))
- **b-avatar:** if variant is empty string, then remove spacing around image (closes
  [#5154](https://github.com/bootstrap-vue/bootstrap-vue/issues/5154))
  ([#5156](https://github.com/bootstrap-vue/bootstrap-vue/issues/5156))
  ([7ff87fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ff87fc560a2ad005bdca394cccf1fafa9d5e696))
- **b-avatar-group:** new helper component b-avatar-group
  ([#5272](https://github.com/bootstrap-vue/bootstrap-vue/issues/5272))
  ([c84faae](https://github.com/bootstrap-vue/bootstrap-vue/commit/c84faaebe18bbf652583d6c302447e931a4ab741))
- **b-button-close:** add `content` prop
  ([#4574](https://github.com/bootstrap-vue/bootstrap-vue/issues/4574))
  ([7379c6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7379c6dd0bac76307720645080741b3b0ed7ed99))
- **b-calendar:** add `nav-button-variant` prop (closes
  [#5702](https://github.com/bootstrap-vue/bootstrap-vue/issues/5702))
  ([#5705](https://github.com/bootstrap-vue/bootstrap-vue/issues/5705))
  ([aa291fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/aa291fce6df52df4d2396b9499c964ce0ac5962b))
- **b-calendar:** add `no-key-nav` property (closes
  [#5861](https://github.com/bootstrap-vue/bootstrap-vue/issues/5861))
  ([#5883](https://github.com/bootstrap-vue/bootstrap-vue/issues/5883))
  ([955ad63](https://github.com/bootstrap-vue/bootstrap-vue/commit/955ad631698f82a83de214ce9cd37271367d8c45))
- **b-calendar, b-form-datepicker:** add optional decade navigation buttons (addresses
  [#4976](https://github.com/bootstrap-vue/bootstrap-vue/issues/4976))
  ([#5112](https://github.com/bootstrap-vue/bootstrap-vue/issues/5112))
  ([b1f74a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/b1f74a84f4021022e606360ee6824c6645b6fbd0))
- **b-calendar, b-form-datepicker:** add prop `weekday-header-format` to specify weekday header
  length (closes [#5171](https://github.com/bootstrap-vue/bootstrap-vue/issues/5171))
  ([#5175](https://github.com/bootstrap-vue/bootstrap-vue/issues/5175))
  ([8241644](https://github.com/bootstrap-vue/bootstrap-vue/commit/8241644477b174042bb163ba1741c3066165d9f9))
- **b-calendar, b-form-datepicker:** add scoped slots for date navigation buttons (closes
  [#5117](https://github.com/bootstrap-vue/bootstrap-vue/issues/5117))
  ([#5147](https://github.com/bootstrap-vue/bootstrap-vue/issues/5147))
  ([5f69864](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f69864497a13a9b18a96b508af6b9ba89a43add))
- **b-calendar, b-form-datepicker:** allow customization of in-component displayed date format
  (closes [#4797](https://github.com/bootstrap-vue/bootstrap-vue/issues/4797))
  ([#4835](https://github.com/bootstrap-vue/bootstrap-vue/issues/4835))
  ([85c7e75](https://github.com/bootstrap-vue/bootstrap-vue/commit/85c7e759bc78d2ffb5b026cb5ee484b2567136aa))
- **b-calendar, b-form-datepicker:** new components `b-calendar` and `b-form-datepicker` (closes
  [#3676](https://github.com/bootstrap-vue/bootstrap-vue/issues/3676),
  [#1428](https://github.com/bootstrap-vue/bootstrap-vue/issues/1428))
  ([#4712](https://github.com/bootstrap-vue/bootstrap-vue/issues/4712))
  ([af0ded0](https://github.com/bootstrap-vue/bootstrap-vue/commit/af0ded0a3bdc9d69653e9c55f874d550e4909662))
- **b-calendar, b-form-datepicker:** relax `YYYY-MM-DD` string parsing (closes
  [#5232](https://github.com/bootstrap-vue/bootstrap-vue/issues/5232))
  ([#5242](https://github.com/bootstrap-vue/bootstrap-vue/issues/5242))
  ([f362802](https://github.com/bootstrap-vue/bootstrap-vue/commit/f362802b2794f0e5d294bbb004d91ccd623a1e25))
- **b-carousel:** add prop `no-wrap` for disabling wrapping to start/end (closes
  [#3902](https://github.com/bootstrap-vue/bootstrap-vue/issues/3902))
  ([#3905](https://github.com/bootstrap-vue/bootstrap-vue/issues/3905))
  ([2c8bd23](https://github.com/bootstrap-vue/bootstrap-vue/commit/2c8bd23f6702b455f0686da6e97b9edae182ed5c))
- **b-collapse:** add new prop `appear` to animate an initially visible collapse
  ([#4317](https://github.com/bootstrap-vue/bootstrap-vue/issues/4317))
  ([136a72b](https://github.com/bootstrap-vue/bootstrap-vue/commit/136a72b0352d4bb1339ab31f791087cbcda42fa5))
- **b-collapse:** add optional scoping to default slot
  ([#4405](https://github.com/bootstrap-vue/bootstrap-vue/issues/4405))
  ([8e95bac](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e95bacf9d00562f2676689d067ae0db009cbbb6))
- **b-drodpown-item-button, b-drodpown-item-button:** add `button-class` and `link-class` prop
  ([#5014](https://github.com/bootstrap-vue/bootstrap-vue/issues/5014))
  ([b39d31c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b39d31cede76b594b5608fa472d53e3dac525e2b))
- **b-dropdown:** add `block` support to toggle button (closes
  [#4266](https://github.com/bootstrap-vue/bootstrap-vue/issues/4266))
  ([#4269](https://github.com/bootstrap-vue/bootstrap-vue/issues/4269))
  ([30029e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/30029e3b01d16178cc1c43b0294ffa4ed4966574))
- **b-dropdown:** add `toggle-attrs` prop (closes
  [#3694](https://github.com/bootstrap-vue/bootstrap-vue/issues/3694))
  ([#6339](https://github.com/bootstrap-vue/bootstrap-vue/issues/6339))
  ([6cfcbb3](https://github.com/bootstrap-vue/bootstrap-vue/commit/6cfcbb300877e7e1fc03e847c540c6f2c8b0742b))
- **b-dropdown:** add splitClass property to dropdown component
  ([#4394](https://github.com/bootstrap-vue/bootstrap-vue/issues/4394))
  ([a5f342e](https://github.com/bootstrap-vue/bootstrap-vue/commit/a5f342e0e4de2186259e36e42cecda8c20e1c8ab))
- **b-dropdown-form:** add formClass prop for adding classes to the form element (closes
  [#4474](https://github.com/bootstrap-vue/bootstrap-vue/issues/4474))
  ([#4475](https://github.com/bootstrap-vue/bootstrap-vue/issues/4475))
  ([eef4200](https://github.com/bootstrap-vue/bootstrap-vue/commit/eef4200976f7921b1bb03f50c0ece8ee7c41ed0e))
- **b-form-datepicker:** add `button-content` optionally scoped slot for icon
  ([#4795](https://github.com/bootstrap-vue/bootstrap-vue/issues/4795))
  ([7a00910](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a0091099025d8bdcf953b00d8619726b54fa937))
- **b-form-datepicker:** add calendar-width prop (closes
  [#4817](https://github.com/bootstrap-vue/bootstrap-vue/issues/4817))
  ([#4822](https://github.com/bootstrap-vue/bootstrap-vue/issues/4822))
  ([91b77bc](https://github.com/bootstrap-vue/bootstrap-vue/commit/91b77bc9a6b1a4796698ce3185c0b354156ce563))
- **b-form-datepicker:** add pass through prop `date-info-fn` (closes
  [#4826](https://github.com/bootstrap-vue/bootstrap-vue/issues/4826))
  ([#5150](https://github.com/bootstrap-vue/bootstrap-vue/issues/5150))
  ([bf35f80](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf35f80d1c4619cf4494dc8a6256d093140d4052))
- **b-form-datepicker, b-form-timepicker:** add support for icon button only mode (closes
  [#4888](https://github.com/bootstrap-vue/bootstrap-vue/issues/4888))
  ([#4915](https://github.com/bootstrap-vue/bootstrap-vue/issues/4915))
  ([13660c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/13660c3ad02f6c692d306ec95f0d2b19212f9423))
- **b-form-datepicker, b-form-timepicker:** emit `shown` and `hidden` events
  ([#5004](https://github.com/bootstrap-vue/bootstrap-vue/issues/5004))
  ([eb259b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/eb259b998dfd3e88a1b04ed8d3f4c97560f69dbb))
- **b-form-file:** improved drag and drop handling (closes
  [#3673](https://github.com/bootstrap-vue/bootstrap-vue/issues/3673))
  ([#5727](https://github.com/bootstrap-vue/bootstrap-vue/issues/5727))
  ([3b12a73](https://github.com/bootstrap-vue/bootstrap-vue/commit/3b12a73d3856a0b14f630d45d236570698b75e50))
- **b-form-group:** add `content-cols` props and scoped `default` slot (closes
  [#6095](https://github.com/bootstrap-vue/bootstrap-vue/issues/6095),
  [#6118](https://github.com/bootstrap-vue/bootstrap-vue/issues/6118))
  ([#6178](https://github.com/bootstrap-vue/bootstrap-vue/issues/6178))
  ([fab6dc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab6dc57e974f14b7fb50f6f413f3fa9a4504290))
- **b-form-group:** allow setting label cols props to `auto` (closes
  [#4217](https://github.com/bootstrap-vue/bootstrap-vue/issues/4217))
  ([#4218](https://github.com/bootstrap-vue/bootstrap-vue/issues/4218))
  ([21a822b](https://github.com/bootstrap-vue/bootstrap-vue/commit/21a822b9416f996cccf828e65dc029eba849277b))
- **b-form-input, b-form-textarea:** add `lazy` modifier prop to update v-model on change/blur event
  ([#4169](https://github.com/bootstrap-vue/bootstrap-vue/issues/4169))
  ([55787dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/55787ddea56c96f6271bb9f832d33887a35919f4))
- **b-form-input, b-form-textarea:** add `v-model` debouncing feature, and deprecate `<b-table>`
  prop `filter-debounce` (closes
  [#4150](https://github.com/bootstrap-vue/bootstrap-vue/issues/4150))
  ([#4314](https://github.com/bootstrap-vue/bootstrap-vue/issues/4314))
  ([3ecdfa2](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ecdfa2a4cd24f5001c30cf7281964451848e87d))
- **b-form-rating:** add `show-value-max` prop to show possible max rating when `show-value` is
  `true` ([#5200](https://github.com/bootstrap-vue/bootstrap-vue/issues/5200))
  ([e9d54e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9d54e6c6a736b2a4f9dbf232dd2b20afa0e990c))
- **b-form-rating:** new `b-form-rating` custom component
  ([#5132](https://github.com/bootstrap-vue/bootstrap-vue/issues/5132))
  ([30ad7fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/30ad7fe746cd6187311c86319abf6e9519b81f15))
- **b-form-select:** add group/tree support and dedicated option and option-group components (closes
  [#3222](https://github.com/bootstrap-vue/bootstrap-vue/issues/3222))
  ([#4267](https://github.com/bootstrap-vue/bootstrap-vue/issues/4267))
  ([f1ed017](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1ed0177c20f9d7e7e340a8815d1b6bc66f7cb76))
- **b-form-select:** support paths for `valueField`, `textField`, `htmlField` and `disabledField`
  props ([#4386](https://github.com/bootstrap-vue/bootstrap-vue/issues/4386))
  ([ed3b736](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed3b7360af415dc3cc56f0b6662c9d48cc165781))
- **b-form-spinbutton:** new form control component `b-form-spinbutton`
  ([#4744](https://github.com/bootstrap-vue/bootstrap-vue/issues/4744))
  ([da5e473](https://github.com/bootstrap-vue/bootstrap-vue/commit/da5e473bee8866f2940e027e5e7e87e3a2ff8f11))
- **b-form-tags:** add `feedback-aria-live` prop
  ([#6347](https://github.com/bootstrap-vue/bootstrap-vue/issues/6347))
  ([5332970](https://github.com/bootstrap-vue/bootstrap-vue/commit/533297054ce98e879071b35da11a3dd5927beafe))
- **b-form-tags:** add `ignoreInputFocusSelector` prop to make input focus behavior configurable
  (closes [#5425](https://github.com/bootstrap-vue/bootstrap-vue/issues/5425))
  ([#5429](https://github.com/bootstrap-vue/bootstrap-vue/issues/5429))
  ([26d5953](https://github.com/bootstrap-vue/bootstrap-vue/commit/26d5953f834684d36b0af99da912dba08fd37bd8))
- **b-form-tags:** add `no-tags-remove` prop (closes
  [#6162](https://github.com/bootstrap-vue/bootstrap-vue/issues/6162))
  ([#6163](https://github.com/bootstrap-vue/bootstrap-vue/issues/6163))
  ([92de1f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/92de1f9f7772c595afcd16d25d8f71b54a2e077b))
- **b-form-tags:** add `reset` method
  ([#6104](https://github.com/bootstrap-vue/bootstrap-vue/issues/6104))
  ([d610291](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6102913a5f9a3295f646fad50ba58ffc31533e8))
- **b-form-tags:** adds `focusin` & `focusout` to wrapper and prevents firing multiple
  `focus`/`blur` events ([#6395](https://github.com/bootstrap-vue/bootstrap-vue/issues/6395))
  ([44e558f](https://github.com/bootstrap-vue/bootstrap-vue/commit/44e558f73c2ae0d4daafbdbc2616002c7c7a763f))
- **b-form-tags:** new option to specify input type (closes
  [#4644](https://github.com/bootstrap-vue/bootstrap-vue/issues/4644))
  ([#4645](https://github.com/bootstrap-vue/bootstrap-vue/issues/4645))
  ([b899fac](https://github.com/bootstrap-vue/bootstrap-vue/commit/b899faceb4c1fd8562454fa93432e70d7113401b))
- **b-form-tags:** new tagged input component
  ([#4409](https://github.com/bootstrap-vue/bootstrap-vue/issues/4409))
  ([00eb9d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/00eb9d9fd460adca8227b3b344284b5cc49a734f))
- **b-img-lazy:** switch IntersectionObserver to use private `v-b-visible` directive
  ([#3977](https://github.com/bootstrap-vue/bootstrap-vue/issues/3977))
  ([249ccfa](https://github.com/bootstrap-vue/bootstrap-vue/commit/249ccfa9fe7477dc094c5a48b8b9c3a64d23c455))
- **b-img, b-img-lazy:** add support for `srcset` and `sizes` props (closes
  [#4348](https://github.com/bootstrap-vue/bootstrap-vue/issues/4348))
  ([#4350](https://github.com/bootstrap-vue/bootstrap-vue/issues/4350))
  ([f419cb4](https://github.com/bootstrap-vue/bootstrap-vue/commit/f419cb4b63611adbc0e955a81dc9c9b1df4ed7bf))
- **b-link:** add support 3rd party router links such as Gridsome's `<g-link>` (closes
  [#2627](https://github.com/bootstrap-vue/bootstrap-vue/issues/2627))
  ([#5358](https://github.com/bootstrap-vue/bootstrap-vue/issues/5358))
  ([6d29e1c](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d29e1cff6c4fd42b3f60f86bd017d8601de3956))
- **b-link:** support `exact-path` and `exact-path-active-class` props for router link (fixes
  [#6434](https://github.com/bootstrap-vue/bootstrap-vue/issues/6434))
  ([#6811](https://github.com/bootstrap-vue/bootstrap-vue/issues/6811))
  ([576e67b](https://github.com/bootstrap-vue/bootstrap-vue/commit/576e67b3af434037a5ee17533a232465527d5edd))
- add `headerTag` and `footerTag` props to all componets with header and footer
  ([#6375](https://github.com/bootstrap-vue/bootstrap-vue/issues/6375))
  ([c6dd70a](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6dd70a787cdc711b3ce539a65f6aac273749874))
- **b-avatar:** new b-avatar component
  ([#4974](https://github.com/bootstrap-vue/bootstrap-vue/issues/4974))
  ([b2325a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/b2325a3f87a58207603be0bad41afb3059a575a1))
- **b-calendar, b-for-datepicker:** add new `initial-date` prop, and constrain today/current month
  buttons between `min` and `max` (closes
  [#4899](https://github.com/bootstrap-vue/bootstrap-vue/issues/4899))
  ([#4906](https://github.com/bootstrap-vue/bootstrap-vue/issues/4906))
  ([1d957eb](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d957ebd78a8693e91a8116d12c28fe24bd7c19c))
- **b-form-spinbutton:** add slots for increment and decrement button content (closes
  [#4958](https://github.com/bootstrap-vue/bootstrap-vue/issues/4958))
  ([#4963](https://github.com/bootstrap-vue/bootstrap-vue/issues/4963))
  ([5684405](https://github.com/bootstrap-vue/bootstrap-vue/commit/5684405197c8dd03b0711b0efc11ab6d76fb7714))
- **b-icon:** add proper `title` support (closes
  [#5711](https://github.com/bootstrap-vue/bootstrap-vue/issues/5711))
  ([#5724](https://github.com/bootstrap-vue/bootstrap-vue/issues/5724))
  ([3756b2c](https://github.com/bootstrap-vue/bootstrap-vue/commit/3756b2c0e07fc85f73769ea312ede8917d1e1de5))
- **b-media:** improve aside right handling
  ([#5965](https://github.com/bootstrap-vue/bootstrap-vue/issues/5965))
  ([49a3f00](https://github.com/bootstrap-vue/bootstrap-vue/commit/49a3f00420bf9958deda3a6be0ccb76cc3ea06ba))
- **b-modal:** add `ignore-enforce-focus-selector` prop (closes
  [#4537](https://github.com/bootstrap-vue/bootstrap-vue/issues/4537))
  ([#4702](https://github.com/bootstrap-vue/bootstrap-vue/issues/4702))
  ([c3ac992](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3ac99283927b5261d1df05d3c479c534011d7c5))
- **b-modal:** add scoped style support when portalled (non-static modal)
  ([#3962](https://github.com/bootstrap-vue/bootstrap-vue/issues/3962))
  ([77ad6b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/77ad6b92e5cc11454fee8fa6c86eccb8b8abcd6f))
- **b-nav:** add card header support
  ([#3883](https://github.com/bootstrap-vue/bootstrap-vue/issues/3883))
  ([4046a53](https://github.com/bootstrap-vue/bootstrap-vue/commit/4046a5307733ede9c21091600d4ba19e4bfcdf8f))
- **b-nav-item-dropdown:** add `boundary` prop, applicable when not in `b-navbar` (closes
  [#4684](https://github.com/bootstrap-vue/bootstrap-vue/issues/4684))
  ([#4691](https://github.com/bootstrap-vue/bootstrap-vue/issues/4691))
  ([3a50ad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a50ad85e85e1c6dc55a36665062180687078708))
- **b-nav-item-dropdown:** improve default handling of dropdown toggle link (closes
  [#3942](https://github.com/bootstrap-vue/bootstrap-vue/issues/3942))
  ([#5344](https://github.com/bootstrap-vue/bootstrap-vue/issues/5344))
  ([62c6105](https://github.com/bootstrap-vue/bootstrap-vue/commit/62c6105e25bc4590f9e2fa92069b77ccbc17fac6))
- **b-navbar-toggle:** add `disabled` prop
  ([#5397](https://github.com/bootstrap-vue/bootstrap-vue/issues/5397))
  ([0b7082b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b7082b792ee49847ba7c99c61758c0d9fd6d222))
- **b-navbar-toggle:** make default slot scoped
  ([#4995](https://github.com/bootstrap-vue/bootstrap-vue/issues/4995))
  ([144d45f](https://github.com/bootstrap-vue/bootstrap-vue/commit/144d45fb0e4d66bbf243b4a4df39d7f3b9b5c7cc))
- **b-overlay:** add support for overlay `click` event (closes
  [#5243](https://github.com/bootstrap-vue/bootstrap-vue/issues/5243))
  ([#5248](https://github.com/bootstrap-vue/bootstrap-vue/issues/5248))
  ([582560f](https://github.com/bootstrap-vue/bootstrap-vue/commit/582560ff97690ab1e5c1f609d76804b7b3daa104))
- **b-pagination:** if number of pages changes, try and keep current page active (closes
  [#3716](https://github.com/bootstrap-vue/bootstrap-vue/issues/3716))
  ([#3990](https://github.com/bootstrap-vue/bootstrap-vue/issues/3990))
  ([ae8ce78](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae8ce78f019a06b381a12a57d1c2e3ae8e6fe15e))
- **b-pagination, b-pagination-nav:** add `pills` style option
  ([#4236](https://github.com/bootstrap-vue/bootstrap-vue/issues/4236))
  ([605d4c4](https://github.com/bootstrap-vue/bootstrap-vue/commit/605d4c4692ef2dc961d29f4508edf7a9fc2f9b9c))
- **b-pagination, b-pagination-nav:** add page button class props and option to show first/last page
  numbers (closes [#4597](https://github.com/bootstrap-vue/bootstrap-vue/issues/4597),
  [#4533](https://github.com/bootstrap-vue/bootstrap-vue/issues/4533))
  ([#4622](https://github.com/bootstrap-vue/bootstrap-vue/issues/4622))
  ([3a3ee1d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a3ee1dc9312a1a8c530a5ea42d1d239d5a24351))
- **b-pagination, b-pagination-nav:** improve aria accessibility (closes:
  [#4811](https://github.com/bootstrap-vue/bootstrap-vue/issues/4811),
  [#4160](https://github.com/bootstrap-vue/bootstrap-vue/issues/4160))
  ([#4810](https://github.com/bootstrap-vue/bootstrap-vue/issues/4810))
  ([7ee4baa](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ee4baa9a843411cd30a3ee499fc7272b7cf48f2))
- **b-pagination/b-pagination-nav:** allow page change to be prevented (closes
  [#5679](https://github.com/bootstrap-vue/bootstrap-vue/issues/5679))
  ([#5755](https://github.com/bootstrap-vue/bootstrap-vue/issues/5755))
  ([7e18c61](https://github.com/bootstrap-vue/bootstrap-vue/commit/7e18c615fec871fb99a947ca5e247bcef04b7c6f))
- **b-row:** add Bootstrap v4.4 row columns support
  ([#4439](https://github.com/bootstrap-vue/bootstrap-vue/issues/4439))
  ([833b028](https://github.com/bootstrap-vue/bootstrap-vue/commit/833b028a2d6101d01b7012a7378359db1c801695))
- **b-sidebar:** add `header` slot
  ([#6179](https://github.com/bootstrap-vue/bootstrap-vue/issues/6179))
  ([341b7f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/341b7f07943d6079d2bf5d6ab88bbcc50f91d0c5))
- **b-sidebar:** add `noEnforceFocus` prop (closes
  [#5707](https://github.com/bootstrap-vue/bootstrap-vue/issues/5707))
  ([#5734](https://github.com/bootstrap-vue/bootstrap-vue/issues/5734))
  ([c11c237](https://github.com/bootstrap-vue/bootstrap-vue/commit/c11c237143230f533404af75933d86a2de7bfb56))
- **b-sidebar:** add optional backdrop support
  ([#5182](https://github.com/bootstrap-vue/bootstrap-vue/issues/5182))
  ([c6375e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6375e5513cb0ec33a9bc9fc894a123d74cf7768))
- **b-sidebar:** add prop `backdrop-variant`
  ([#5411](https://github.com/bootstrap-vue/bootstrap-vue/issues/5411))
  ([4b0c163](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b0c163156b6ac5be6c1b0a2801d7c169c87cb49))
- **b-sidebar:** new custom component `<b-sidebar>` (closes
  [#3324](https://github.com/bootstrap-vue/bootstrap-vue/issues/3324),
  [#3210](https://github.com/bootstrap-vue/bootstrap-vue/issues/3210),
  [#1702](https://github.com/bootstrap-vue/bootstrap-vue/issues/1702))
  ([#5021](https://github.com/bootstrap-vue/bootstrap-vue/issues/5021))
  ([a77866f](https://github.com/bootstrap-vue/bootstrap-vue/commit/a77866f6d032f1a5a22be2d12d60be507825769c))
- **b-skeleton:** add skeleton components (closes
  [#5413](https://github.com/bootstrap-vue/bootstrap-vue/issues/5413))
  ([#5575](https://github.com/bootstrap-vue/bootstrap-vue/issues/5575))
  ([31c06b5](https://github.com/bootstrap-vue/bootstrap-vue/commit/31c06b5fa697b5f13cc888a1d72effae21eb5e73))
- **b-table:** add `filter-debounce` prop for debouncing filter updates
  ([#3891](https://github.com/bootstrap-vue/bootstrap-vue/issues/3891))
  ([03536a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/03536a504208f094f205a5a2f1ab64ccbb4dbccf))
- **b-table:** add `selectAllRows()` and `clearSelected()` to thead/tfoot slot scopes (addresses
  [#3901](https://github.com/bootstrap-vue/bootstrap-vue/issues/3901))
  ([#3907](https://github.com/bootstrap-vue/bootstrap-vue/issues/3907))
  ([86c53dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/86c53dd83da9c292904e2f489b310cc59a1f31a1))
- **b-table:** add `selectRow()` and `unselectRow()` methods to cell and row-details slot scopes,
  and new prop `no-select-on-click`
  ([#4283](https://github.com/bootstrap-vue/bootstrap-vue/issues/4283))
  ([64b881f](https://github.com/bootstrap-vue/bootstrap-vue/commit/64b881fe2fa19c65a806af85b83504290277557c))
- **b-table:** add `sortKey` option for `no-local-sorting` events
  ([#5746](https://github.com/bootstrap-vue/bootstrap-vue/issues/5746))
  ([f847dae](https://github.com/bootstrap-vue/bootstrap-vue/commit/f847daeb797b84ed80b49a31294a5088fc32b59d))
- **b-table:** allow field definition properties `filterByFormatted` and `sortByFormatted` accept a
  formatter function reference (closes
  [#3892](https://github.com/bootstrap-vue/bootstrap-vue/issues/3892))
  ([#3898](https://github.com/bootstrap-vue/bootstrap-vue/issues/3898))
  ([5492b38](https://github.com/bootstrap-vue/bootstrap-vue/commit/5492b38a71d9a36314f801a40c026f0ef108cd05))
- **b-table:** better sort labeling for screen readers (closes
  [#4487](https://github.com/bootstrap-vue/bootstrap-vue/issues/4487))
  ([#4488](https://github.com/bootstrap-vue/bootstrap-vue/issues/4488))
  ([d4e66fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4e66fa48fdd1cd7fd4b93907fe999de3fc577f8))
- **b-table:** default the row select feature `selected-variant` to the `active` variant
  ([#4128](https://github.com/bootstrap-vue/bootstrap-vue/issues/4128))
  ([af372b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/af372b006e08a98fd9e53891c940b458a97e8996))
- **b-table:** new sorting icons using SVG, plus option to place icon on left of header cell (closes
  [#3687](https://github.com/bootstrap-vue/bootstrap-vue/issues/3687),
  [#3696](https://github.com/bootstrap-vue/bootstrap-vue/issues/3696),
  [#3918](https://github.com/bootstrap-vue/bootstrap-vue/issues/3918),
  [#3966](https://github.com/bootstrap-vue/bootstrap-vue/issues/3966))
  ([#3968](https://github.com/bootstrap-vue/bootstrap-vue/issues/3968))
  ([c4442f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4442f4c41231b6c5514e8ff37002088a1d15f9d))
- **b-table, b-table-lite:** add in head/foot row variant prop (addresses
  [#4215](https://github.com/bootstrap-vue/bootstrap-vue/issues/4215))
  ([#4216](https://github.com/bootstrap-vue/bootstrap-vue/issues/4216))
  ([b222c7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b222c7c01434ef073c54c55f7044c7ce0b9e4325))
- **b-table, b-table-lite:** add new scoped slot `custom-foot` to allow user to create their own
  table footer (closes [#3960](https://github.com/bootstrap-vue/bootstrap-vue/issues/3960))
  ([#4027](https://github.com/bootstrap-vue/bootstrap-vue/issues/4027))
  ([cbeeef9](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbeeef95609e9fa1a85626066b5d812db3c708bc))
- **b-table, b-table-lite:** add prop `details-td-class` for applying classes to the details row
  `<td>` ([#4276](https://github.com/bootstrap-vue/bootstrap-vue/issues/4276))
  ([702a1ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/702a1ef152d0a064dcf7dfaaa55168d2e1b82a50))
- **b-table, b-table-lite:** new `tbody-tr-attr` prop for arbitrary row attributes (closes
  [#1864](https://github.com/bootstrap-vue/bootstrap-vue/issues/1864))
  ([#4481](https://github.com/bootstrap-vue/bootstrap-vue/issues/4481))
  ([4acf6ed](https://github.com/bootstrap-vue/bootstrap-vue/commit/4acf6ed863dd5edd85897a01b099c42322097d1b))
- **b-table, b-table-lite:** switch slot name syntax to use round brackets instead of square
  brackets ([#3986](https://github.com/bootstrap-vue/bootstrap-vue/issues/3986))
  ([fca7bd5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fca7bd54c17f42ee5361cf5bf6395f3bb205c333))
- **b-table, b-table-lite:** use `aria-details` rather than `aria-describedby` when details row
  showing (addresses [#3801](https://github.com/bootstrap-vue/bootstrap-vue/issues/3801))
  ([#3992](https://github.com/bootstrap-vue/bootstrap-vue/issues/3992))
  ([f6f73c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6f73c7ac8f4a54196be5f0ee08c99c76e8f8b13))
- **b-tabs:** add ability to provide custom tab button attributes (closes:
  [#4803](https://github.com/bootstrap-vue/bootstrap-vue/issues/4803))
  ([#4806](https://github.com/bootstrap-vue/bootstrap-vue/issues/4806))
  ([c541d3d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c541d3d89ae88f3193305b61ae8ddc735aa6ec03))
- **b-tabs:** emit cancelable BvEvent before changing tabs via new `activate-tab` event (closes
  [#4273](https://github.com/bootstrap-vue/bootstrap-vue/issues/4273))
  ([#4274](https://github.com/bootstrap-vue/bootstrap-vue/issues/4274))
  ([9b195dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b195dd63f75fe3aa3565a2b37448a3e9b8140ca))
- **b-tags:** add `limit` prop ([#5543](https://github.com/bootstrap-vue/bootstrap-vue/issues/5543))
  ([caa0f1a](https://github.com/bootstrap-vue/bootstrap-vue/commit/caa0f1a2e6d96637c216eb306c77a67254af1caf))
- **b-time, b-form-timepicker:** new components `b-time` and `b-form-timepicker`
  ([#4783](https://github.com/bootstrap-vue/bootstrap-vue/issues/4783))
  ([417ef8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/417ef8f2165e68d182e942219d847511b0fd6e9c))
- **b-tooltip:** add `noninteractive` prop (closes
  [#4556](https://github.com/bootstrap-vue/bootstrap-vue/issues/4556))
  ([#4563](https://github.com/bootstrap-vue/bootstrap-vue/issues/4563))
  ([b3ad726](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3ad7264d9b10fb1b8dfba70c62eed11a56519d6))
- **chore:** configure pre-commit hook (fixes
  [#4532](https://github.com/bootstrap-vue/bootstrap-vue/issues/4532))
  ([#4552](https://github.com/bootstrap-vue/bootstrap-vue/issues/4552))
  ([1bf9e59](https://github.com/bootstrap-vue/bootstrap-vue/commit/1bf9e59e8888a7a2cd6f135665103419f603a32d))
- **config:** improved defaults handling (closes
  [#4507](https://github.com/bootstrap-vue/bootstrap-vue/issues/4507),
  [#5138](https://github.com/bootstrap-vue/bootstrap-vue/issues/5138),
  [#5291](https://github.com/bootstrap-vue/bootstrap-vue/issues/5291),
  [#5459](https://github.com/bootstrap-vue/bootstrap-vue/issues/5459),
  [#5958](https://github.com/bootstrap-vue/bootstrap-vue/issues/5958))
  ([#5981](https://github.com/bootstrap-vue/bootstrap-vue/issues/5981))
  ([7ea0cc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ea0cc4a16d27b179eca47d351eaa9fe6fdfd56e))
- **docs:** add prop descriptions to component reference tables (closes
  [#3647](https://github.com/bootstrap-vue/bootstrap-vue/issues/3647))
  ([#4161](https://github.com/bootstrap-vue/bootstrap-vue/issues/4161))
  ([fdd2a83](https://github.com/bootstrap-vue/bootstrap-vue/commit/fdd2a837de3173f28b96ad4c92cf458fc0f39816))
- **docs:** auto-detect settings props in component reference
  ([#5761](https://github.com/bootstrap-vue/bootstrap-vue/issues/5761))
  ([0ddb2e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0ddb2e051c0ce42bdd599415ba93e82e1a6584f1))
- **docs:** improve form validation examples
  ([#4584](https://github.com/bootstrap-vue/bootstrap-vue/issues/4584))
  ([aca4a5c](https://github.com/bootstrap-vue/bootstrap-vue/commit/aca4a5c8f9a9ed0d7526de396ff072f0c1f4ebdf))
- **docs:** make more concise and explain how to hide `b-toast` title
  ([#4542](https://github.com/bootstrap-vue/bootstrap-vue/issues/4542))
  ([e013dc6](https://github.com/bootstrap-vue/bootstrap-vue/commit/e013dc6d711980b6efb3cb1d0804f039c7e8224d))
- **docs:** move `@nuxtjs/google-analytics` to `buildModules`
  ([#4299](https://github.com/bootstrap-vue/bootstrap-vue/issues/4299))
  ([407c6e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/407c6e3a1035787326531348d9c7cee8ea4cea19))
- **dropdown:** add `role=presentation` to `<li>` elements for improved a11y
  ([#3996](https://github.com/bootstrap-vue/bootstrap-vue/issues/3996))
  ([464d257](https://github.com/bootstrap-vue/bootstrap-vue/commit/464d257f709c856ab04ff237a178b83e1776e9b6))
- **icons:** add stacking support
  ([#4658](https://github.com/bootstrap-vue/bootstrap-vue/issues/4658))
  ([b185cdb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b185cdb686ddddcde1b98585b1fbc48859fc541a))
- **icons:** optional icon components
  ([#4489](https://github.com/bootstrap-vue/bootstrap-vue/issues/4489))
  ([d2bef17](https://github.com/bootstrap-vue/bootstrap-vue/commit/d2bef1715636fcb83de6d51808683e6feda671d0))
- **icons:** upgrade to Bootstrap Icons 1.0.0-alpha4
  ([#5420](https://github.com/bootstrap-vue/bootstrap-vue/issues/5420))
  ([3208309](https://github.com/bootstrap-vue/bootstrap-vue/commit/3208309c649b4cce73c68643d7c911237a713ebc))
- **modal:** add prop for auto focusing one of the built in-buttons once `shown` (closes
  [#3945](https://github.com/bootstrap-vue/bootstrap-vue/issues/3945))
  ([#3979](https://github.com/bootstrap-vue/bootstrap-vue/issues/3979))
  ([6f2827e](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f2827e2e70683bbd8cb48e45a8daa4171cb43e2))
- **refactor:** code enhancements for easier Vue 3 migration (closes
  [#6124](https://github.com/bootstrap-vue/bootstrap-vue/issues/6124),
  [#6139](https://github.com/bootstrap-vue/bootstrap-vue/issues/6139))
  ([#6141](https://github.com/bootstrap-vue/bootstrap-vue/issues/6141))
  ([5bf6733](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bf6733595091cc204d3acc0641f8f0301bcbe9c))
- update `core-js` to v3 ([#5894](https://github.com/bootstrap-vue/bootstrap-vue/issues/5894))
  ([aeed981](https://github.com/bootstrap-vue/bootstrap-vue/commit/aeed9812afe770b6561c9513709e4be852250022))
- **docs:** launch themes page with first BootstrapVue theme
  ([#5549](https://github.com/bootstrap-vue/bootstrap-vue/issues/5549))
  ([ec51ef0](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec51ef062f7ed39339cde59b2d9d4cee40347dcc))
- update Bootstrap to v4.5 ([#5395](https://github.com/bootstrap-vue/bootstrap-vue/issues/5395))
  ([ba7a55e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ba7a55ea094049fd1e3ae492a5a95196252b1da9))
- **custom components:** avoid using padding/margin utility classes where possible (closes
  [#5117](https://github.com/bootstrap-vue/bootstrap-vue/issues/5117))
  ([#5121](https://github.com/bootstrap-vue/bootstrap-vue/issues/5121))
  ([8c6cfe0](https://github.com/bootstrap-vue/bootstrap-vue/commit/8c6cfe0af919a4e54667bcb4b29d2ba6b6576b67))
- **icons:** new `throb` and `fade` animations
  ([#5122](https://github.com/bootstrap-vue/bootstrap-vue/issues/5122))
  ([bc0117c](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc0117cc794c948b202daf2e17f22eb4c36235cc))
- **table:** add `no-border-collapse` prop and SCSS
  ([#3987](https://github.com/bootstrap-vue/bootstrap-vue/issues/3987))
  ([253b4f6](https://github.com/bootstrap-vue/bootstrap-vue/commit/253b4f6e0c20027b40d10e316d49a14f3e860c5d))
- **toast:** add support for scoped styles
  ([#3963](https://github.com/bootstrap-vue/bootstrap-vue/issues/3963))
  ([ca1b5de](https://github.com/bootstrap-vue/bootstrap-vue/commit/ca1b5debca5966ea032c805d544aa9274ae6ed42))
- **tooltip, popover:** overall code refactor for better reactivity and performance (fixes:
  [#1990](https://github.com/bootstrap-vue/bootstrap-vue/issues/1990),
  [#2937](https://github.com/bootstrap-vue/bootstrap-vue/issues/2937),
  [#3480](https://github.com/bootstrap-vue/bootstrap-vue/issues/3480),
  [#3717](https://github.com/bootstrap-vue/bootstrap-vue/issues/3717),
  [#3854](https://github.com/bootstrap-vue/bootstrap-vue/issues/3854), closes
  [#3451](https://github.com/bootstrap-vue/bootstrap-vue/issues/3451))
  ([#3908](https://github.com/bootstrap-vue/bootstrap-vue/issues/3908))
  ([eebab43](https://github.com/bootstrap-vue/bootstrap-vue/commit/eebab437b03528dd7fe2a2cc84e3b9cbfb336c58))
- **types:** create declarations for `<b-calendar>` and `<b-time>` context event objects (closes
  [#5366](https://github.com/bootstrap-vue/bootstrap-vue/issues/5366))
  ([#5374](https://github.com/bootstrap-vue/bootstrap-vue/issues/5374))
  ([8f3ca30](https://github.com/bootstrap-vue/bootstrap-vue/commit/8f3ca30e4d51b5e97f9c4f301c31254a8b060980))
- **v-b-hover:** new directive for reacting to hover changes
  ([#4771](https://github.com/bootstrap-vue/bootstrap-vue/issues/4771))
  ([b7adc6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/b7adc6dc726f75c0578b3de5208f112bef58b4ad))
- **v-b-toggle:** check for target ID via `href` if a link
  ([#5398](https://github.com/bootstrap-vue/bootstrap-vue/issues/5398))
  ([33e39b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/33e39b007225ba86a0c84a66e3ee60b9d2f01fed))
- support `<nuxt-link>`'s `prefetch` property (closes
  [#5125](https://github.com/bootstrap-vue/bootstrap-vue/issues/5125))
  ([#5355](https://github.com/bootstrap-vue/bootstrap-vue/issues/5355))
  ([b9416cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9416cb3824d680e297347af61a934b1536224de))
- **v-b-toggle:** support specifying target ID via directive argument, and array of target IDs via
  directive value (closes [#4834](https://github.com/bootstrap-vue/bootstrap-vue/issues/4834))
  ([#5336](https://github.com/bootstrap-vue/bootstrap-vue/issues/5336))
  ([260ef72](https://github.com/bootstrap-vue/bootstrap-vue/commit/260ef7259e46d343823767374322db0ae3a74803))
- upgrade to bootstrap icons alpha 3
  ([#4966](https://github.com/bootstrap-vue/bootstrap-vue/issues/4966))
  ([d481365](https://github.com/bootstrap-vue/bootstrap-vue/commit/d481365c9f8014e1573026881c3588f2d51999ee))
- **v-b-visible:** make `v-b-visible` directive available for public use
  ([#4318](https://github.com/bootstrap-vue/bootstrap-vue/issues/4318))
  ([5fa7e22](https://github.com/bootstrap-vue/bootstrap-vue/commit/5fa7e22cc3cca6295d226037f880074cfe841b2c))
- auto-generate file `web-types.json` for WebStorm, and files `vetur-tags.json` and
  `vetur-attributes.json` for Vetur (closes
  [#4107](https://github.com/bootstrap-vue/bootstrap-vue/issues/4107))
  ([#4110](https://github.com/bootstrap-vue/bootstrap-vue/issues/4110))
  ([1a3e6a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/1a3e6a56759bee9cc11d4405a4708dbba826fa51))
- improve `CONTRIBUTING.md` ([#4260](https://github.com/bootstrap-vue/bootstrap-vue/issues/4260))
  ([25dacb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/25dacb5ba1923c72e28c590e3b1e80192ad36e1b))
- use `emitOnRoot()` whereever possible and remove unused chainable support
  ([#5030](https://github.com/bootstrap-vue/bootstrap-vue/issues/5030))
  ([74aade1](https://github.com/bootstrap-vue/bootstrap-vue/commit/74aade19b3fe49934769111d251c5039106643bf))
- **alert:** remove need for custom CSS for fade transition
  ([#2925](https://github.com/bootstrap-vue/bootstrap-vue/issues/2925))
  ([0910b22](https://github.com/bootstrap-vue/bootstrap-vue/commit/0910b228aa0e2e527a20b80b7eca9d3463b76cfa))
- **b-container:** add support for bootstrap v4.4.x new responsive containers
  ([0e318f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e318f4755e65eb569dcc579938d0d72c02abd62))
- **b-dropdown:** new `split-button-type` prop to specify split button type (closes
  [#3694](https://github.com/bootstrap-vue/bootstrap-vue/issues/3694))
  ([#3695](https://github.com/bootstrap-vue/bootstrap-vue/issues/3695))
  ([1157589](https://github.com/bootstrap-vue/bootstrap-vue/commit/1157589fa4fad9e636e94862a196121d9054c8c1))
- **b-dropdown:** remove deprecated slot `text`
  ([#3868](https://github.com/bootstrap-vue/bootstrap-vue/issues/3868))
  ([29eb8b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/29eb8b1879462ce2dee8192c2ef203fb348baeac))
- **b-dropdown & b-nav-item-dropdown:** pass optional scope to default slot & fixes keyboard nav
  with dropdown forms ([#3242](https://github.com/bootstrap-vue/bootstrap-vue/issues/3242))
  ([3d1d777](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d1d7775dbf4846a0339021e75bcbb1c88267e5f))
- **b-dropdown, b-nav-item-dropdown:** add new lazy prop (addresses
  [#3634](https://github.com/bootstrap-vue/bootstrap-vue/issues/3634))
  ([#3639](https://github.com/bootstrap-vue/bootstrap-vue/issues/3639))
  ([f742a8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/f742a8a912a41b4b151ff1a7033e95fcaea05767))
- **b-form-file, b-form-checkbox, b-form-radio:** make input element inherit non-prop attributes
  (addresses [#3752](https://github.com/bootstrap-vue/bootstrap-vue/issues/3752))
  ([#3754](https://github.com/bootstrap-vue/bootstrap-vue/issues/3754))
  ([722f9db](https://github.com/bootstrap-vue/bootstrap-vue/commit/722f9db371634d5185db0f7fef99cc1c735b6e8d))
- **b-form-group:** remove deprecated prop `horizontal` and `breakpoint`
  ([#3879](https://github.com/bootstrap-vue/bootstrap-vue/issues/3879))
  ([b301822](https://github.com/bootstrap-vue/bootstrap-vue/commit/b301822902d30c77d06a3bfef7c5a580484cc4ed))
- **b-img-lazy:** add support for IntersectionObserver (closes
  [#3276](https://github.com/bootstrap-vue/bootstrap-vue/issues/3276))
  ([#3279](https://github.com/bootstrap-vue/bootstrap-vue/issues/3279))
  ([5cf71cf](https://github.com/bootstrap-vue/bootstrap-vue/commit/5cf71cf6017f6dce517dfd7ee587dc8f7e53a19e))
- **b-modal:** for accessibility, read only modal title and not whole header + additional A11Y
  options (addresses [#3712](https://github.com/bootstrap-vue/bootstrap-vue/issues/3712))
  ([#3715](https://github.com/bootstrap-vue/bootstrap-vue/issues/3715))
  ([1ce8c6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/1ce8c6d5ccfc6e0be93761daa428c01c61b81f62))
- **b-modal:** improved portaling - retaining parent-child hierarchy (addresses
  [#3312](https://github.com/bootstrap-vue/bootstrap-vue/issues/3312))
  ([#3326](https://github.com/bootstrap-vue/bootstrap-vue/issues/3326))
  ([3728892](https://github.com/bootstrap-vue/bootstrap-vue/commit/3728892207e4c0e8571e4014244623dc8447042c))
- **b-nav, b-nav-item-dropdown:** remove deprecated slot and props
  ([#3867](https://github.com/bootstrap-vue/bootstrap-vue/issues/3867))
  ([21fab35](https://github.com/bootstrap-vue/bootstrap-vue/commit/21fab353f2bbaa4a5698bc646bfb99213117a916))
- **b-table:** allow users to specify top-level keys to be ignored or included when filtering, plus
  add option to filter based on formatted value (closes
  [#3749](https://github.com/bootstrap-vue/bootstrap-vue/issues/3749))
  ([#3786](https://github.com/bootstrap-vue/bootstrap-vue/issues/3786))
  ([142b31b](https://github.com/bootstrap-vue/bootstrap-vue/commit/142b31bf4dec89cc3dcd935bf8b8ba6cbac1ba26))
- **b-table:** make sorting by formated value opt-in per field + add TypeScript declarations for
  locale options ([#3778](https://github.com/bootstrap-vue/bootstrap-vue/issues/3778))
  ([9716850](https://github.com/bootstrap-vue/bootstrap-vue/commit/971685060aaced1463e14cf6447021490a6d51ba))
- **b-table:** programmatic row selection (closes
  [#3064](https://github.com/bootstrap-vue/bootstrap-vue/issues/3064),
  [#3370](https://github.com/bootstrap-vue/bootstrap-vue/issues/3370))
  ([#3844](https://github.com/bootstrap-vue/bootstrap-vue/issues/3844))
  ([9a4fe24](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a4fe24a609e52b8811e9c4e224df06135978b05))
- **b-table:** sort fields that have a formatter function + support `localCompare` options (closes
  [#3178](https://github.com/bootstrap-vue/bootstrap-vue/issues/3178),
  [#1173](https://github.com/bootstrap-vue/bootstrap-vue/issues/1173))
  ([#3585](https://github.com/bootstrap-vue/bootstrap-vue/issues/3585))
  ([c0ca1fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0ca1fdc65b096653f985614befeabedc0078e15))
- **b-table-lite:** new `<b-table-lite>` light-weight table component
  ([#3447](https://github.com/bootstrap-vue/bootstrap-vue/issues/3447))
  ([0477941](https://github.com/bootstrap-vue/bootstrap-vue/commit/0477941e6a35729030b24c635436e9e23f51d644))
- **b-table-simple:** new `<table>` wrapper component that allows users to render their own
  `<thead>`, `<tfoot>`, `<body>`
  ([#3799](https://github.com/bootstrap-vue/bootstrap-vue/issues/3799))
  ([998bd4f](https://github.com/bootstrap-vue/bootstrap-vue/commit/998bd4f133f4bddf7738bdccd54c1ed78c3eb0f1))
- **b-table, b-table-lite:** new field scoped slot naming convention + new fallback scoped slots,
  deprecated old field slot convention (closes
  [#3731](https://github.com/bootstrap-vue/bootstrap-vue/issues/3731))
  ([#3741](https://github.com/bootstrap-vue/bootstrap-vue/issues/3741))
  ([f53360d](https://github.com/bootstrap-vue/bootstrap-vue/commit/f53360d5e6b06e2462f2fba296e3cdc6a31180dc))
- **b-table, b-table-lite:** place `<tfoot>` after `<tbody>` element per HTML5 spec
  ([#3807](https://github.com/bootstrap-vue/bootstrap-vue/issues/3807))
  ([e885d6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e885d6dcd76531a3ac7dbc0b48d97469bdee8dd3))
- **b-tabs:** emit `changed` event whenever tabs added, removed or re-ordered (closes
  [#3575](https://github.com/bootstrap-vue/bootstrap-vue/issues/3575))
  ([#3577](https://github.com/bootstrap-vue/bootstrap-vue/issues/3577))
  ([841419a](https://github.com/bootstrap-vue/bootstrap-vue/commit/841419af00fbc15975ea234a37883b5af66582d9))
- **b-tooltip, b-popover:** add `fallback-placement` prop (closes
  [#3348](https://github.com/bootstrap-vue/bootstrap-vue/issues/3348))
  ([#3349](https://github.com/bootstrap-vue/bootstrap-vue/issues/3349))
  ([ab42b4c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab42b4c4f8189570c62d2263aea1d40fe9d2a724))
- **b-tooltip, b-popover:** allow global `delay` customization
  ([#3426](https://github.com/bootstrap-vue/bootstrap-vue/issues/3426))
  ([2aaec76](https://github.com/bootstrap-vue/bootstrap-vue/commit/2aaec76b6bc4a39e9bc8d560f6d2ec4fd2480574))
- **breadcrumb-link:** support html
  ([#2522](https://github.com/bootstrap-vue/bootstrap-vue/issues/2522))
  ([c2ee63e](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2ee63e9ac8f72f6c1d6a81a66b073826b60ad57))
- **build:** remove deprecated `es/` build
  ([#3604](https://github.com/bootstrap-vue/bootstrap-vue/issues/3604))
  ([3828f59](https://github.com/bootstrap-vue/bootstrap-vue/commit/3828f59e4c640571ad86b4d4851d6ac31eaa9466))
- **button:** add new `squared` prop for making buttons with square corners
  ([#3387](https://github.com/bootstrap-vue/bootstrap-vue/issues/3387))
  ([004963d](https://github.com/bootstrap-vue/bootstrap-vue/commit/004963d6215ce2ccc712a3e4e1371a4cb788a2a1))
- **button:** add prop `pill` for pill style buttons
  ([#3214](https://github.com/bootstrap-vue/bootstrap-vue/issues/3214))
  ([c26298b](https://github.com/bootstrap-vue/bootstrap-vue/commit/c26298b154e51648e05d296ac8f03a6d2b544692))
- **BvEvent:** subclass BvEvent as BvModalEvent
  ([#3024](https://github.com/bootstrap-vue/bootstrap-vue/issues/3024))
  ([502eba9](https://github.com/bootstrap-vue/bootstrap-vue/commit/502eba962eb1b57e19e54eb6dc61a6fc4ada3517))
- **card:** new helper sub-components
  ([#2375](https://github.com/bootstrap-vue/bootstrap-vue/issues/2375))
  ([ff25314](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff253141aba892419ed51b62dd2319b99ba74961))
- **card-img-lazy:** new card-img-lazy sub-component
  ([#2647](https://github.com/bootstrap-vue/bootstrap-vue/issues/2647))
  ([d2e1f8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d2e1f8aec683c2349164125a1115ad7e57c192e3))
- **carousel:** add no-hover-pause prop
  ([#2888](https://github.com/bootstrap-vue/bootstrap-vue/issues/2888))
  ([8a503ec](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a503ec243bc7a06fb221681105d7c39d7fe51d2))
- **carousel:** add support for swipe on touch screens
  ([#2409](https://github.com/bootstrap-vue/bootstrap-vue/issues/2409))
  ([46a6763](https://github.com/bootstrap-vue/bootstrap-vue/commit/46a6763f23e83cc9ceca2bfd9566388e019fbb55))
- **carousel:** support crossfade animation
  ([#2406](https://github.com/bootstrap-vue/bootstrap-vue/issues/2406))
  ([15d8a2c](https://github.com/bootstrap-vue/bootstrap-vue/commit/15d8a2c40d397bf90a301653d40c02ee32c76cdd))
- **carousel:** use provide and inject for sub-component communication
  ([#2407](https://github.com/bootstrap-vue/bootstrap-vue/issues/2407))
  ([7f92318](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f92318fb64b7cefc3421f6877a4f6575006ae9e))
- **config:** add option in config to set global tooltip and popover boundary
  ([#3229](https://github.com/bootstrap-vue/bootstrap-vue/issues/3229))
  ([00e4fc9](https://github.com/bootstrap-vue/bootstrap-vue/commit/00e4fc9004bd8d91f8de83e1f1381ddb8950c25c))
- **config:** defaults for all `size` properties (closes
  [#3805](https://github.com/bootstrap-vue/bootstrap-vue/issues/3805))
  ([#3841](https://github.com/bootstrap-vue/bootstrap-vue/issues/3841))
  ([1389efa](https://github.com/bootstrap-vue/bootstrap-vue/commit/1389efaf21ed9870b68734a863a4e82f60d556dd))
- **core:** create configurable base global configuration
  ([#2905](https://github.com/bootstrap-vue/bootstrap-vue/issues/2905))
  ([8018bdf](https://github.com/bootstrap-vue/bootstrap-vue/commit/8018bdf07329e43cb4051ff2a7526176967c610f))
- **docs:** add heading anchor links
  ([#2698](https://github.com/bootstrap-vue/bootstrap-vue/issues/2698))
  ([fd6cbef](https://github.com/bootstrap-vue/bootstrap-vue/commit/fd6cbef6806fc57cd115eeb39df6f14ba5549916))
- **docs:** add home and playground links to sidebar navigation
  ([#3654](https://github.com/bootstrap-vue/bootstrap-vue/issues/3654))
  ([e5eb9fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5eb9fc01a2af362f338d066f7112987ef1b1c02))
- **docs:** algolia powered search
  ([#2952](https://github.com/bootstrap-vue/bootstrap-vue/issues/2952))
  ([0417f7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0417f7bd9ead7c7ba568a24f016db9c282e103d0))
- **docs:** get recommended `Vue.js` and `Bootstrap` version from `package.json`
  ([#2840](https://github.com/bootstrap-vue/bootstrap-vue/issues/2840))
  ([3a6702e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a6702ebbcc1c155d150232d6598300a74445ea9))
- **docs:** Improve code example markup and prettier integration
  ([#2440](https://github.com/bootstrap-vue/bootstrap-vue/issues/2440))
  ([74ad932](https://github.com/bootstrap-vue/bootstrap-vue/commit/74ad932b4f087e3a38035010c4789892b52b327b))
- **docs:** Prettify with `prettier`
  ([#2427](https://github.com/bootstrap-vue/bootstrap-vue/issues/2427))
  ([9463138](https://github.com/bootstrap-vue/bootstrap-vue/commit/94631385301ce07bc657dec6090ac4a8bf4abc17))
- **docs:** remove new/enhances/changed badges
  ([#3870](https://github.com/bootstrap-vue/bootstrap-vue/issues/3870))
  ([d46529c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d46529c3b4fcb5adbe14cd4ec16c7268d23e9585))
- **docs:** updates to the theming reference section
  ([#3790](https://github.com/bootstrap-vue/bootstrap-vue/issues/3790))
  ([e080bf7](https://github.com/bootstrap-vue/bootstrap-vue/commit/e080bf7e3a98378bf66e95d002dd3f9acf5a94f9))
- **docs/playground:** add support for exporting to CodePen and CodeSandbox
  ([#3071](https://github.com/bootstrap-vue/bootstrap-vue/issues/3071))
  ([ccb1614](https://github.com/bootstrap-vue/bootstrap-vue/commit/ccb1614cc7c6a95fc2ae6a9d01b9924bedf2396c))
- **dropdown:** additional semantic markup optimizations for A11Y
  ([#3196](https://github.com/bootstrap-vue/bootstrap-vue/issues/3196))
  ([91d893e](https://github.com/bootstrap-vue/bootstrap-vue/commit/91d893e0b9e4e8b70f19c30e372e2fb6b56c5cbc))
- **dropdown:** support for form controls and free flow text
  ([#2434](https://github.com/bootstrap-vue/bootstrap-vue/issues/2434))
  ([7e8a2d5](https://github.com/bootstrap-vue/bootstrap-vue/commit/7e8a2d5fe365d1ec185feed2f7a49e60238825a4))
- **dropdown:** use provide and inject
  ([#2431](https://github.com/bootstrap-vue/bootstrap-vue/issues/2431))
  ([3df90ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/3df90ea64e5b1bdbfe8a05ece7d588807c359813))
- **dropdown:** use semantic `<ul>` and `<li>` markup (closes
  [#3072](https://github.com/bootstrap-vue/bootstrap-vue/issues/3072))
  ([#3087](https://github.com/bootstrap-vue/bootstrap-vue/issues/3087))
  ([58ad66b](https://github.com/bootstrap-vue/bootstrap-vue/commit/58ad66be27b202310cc0d60a67ddd2d9358cc9d7))
- **es:** revert to tranforming `es/` modules into CJS, and simplify build with top-level named
  import/exports (closes [#3397](https://github.com/bootstrap-vue/bootstrap-vue/issues/3397),
  [#3393](https://github.com/bootstrap-vue/bootstrap-vue/issues/3393),
  [#3323](https://github.com/bootstrap-vue/bootstrap-vue/issues/3323))
  ([#3404](https://github.com/bootstrap-vue/bootstrap-vue/issues/3404))
  ([6c386d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/6c386d3c34cc8d9b63094d147da7edc0ac181370))
- **es build:** don't transpile import/export statements to require/exports, for better tree shaking
  (closes [#3323](https://github.com/bootstrap-vue/bootstrap-vue/issues/3323))
  ([#3358](https://github.com/bootstrap-vue/bootstrap-vue/issues/3358))
  ([3c1866d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c1866db82a36807c7d3593c2932d927d7988bb9))
- **form controls:** add `autofocus` prop
  ([#3341](https://github.com/bootstrap-vue/bootstrap-vue/issues/3341))
  ([e7eb1b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/e7eb1b40d7e295f9bca759a96e0261cb24678b02))
- **form controls:** add support for control sizing of `b-form-file`, `b-form-checkbox`, and
  `b-form-radio` (closes [#3745](https://github.com/bootstrap-vue/bootstrap-vue/issues/3745))
  ([#3794](https://github.com/bootstrap-vue/bootstrap-vue/issues/3794))
  ([18c3957](https://github.com/bootstrap-vue/bootstrap-vue/commit/18c3957486008dad5c39e42f2c321311e8407d81))
- **form-checkbox, form-radio:** add `aria-labelledby` prop (closes:
  [#3139](https://github.com/bootstrap-vue/bootstrap-vue/issues/3139))
  ([#3140](https://github.com/bootstrap-vue/bootstrap-vue/issues/3140))
  ([f82f566](https://github.com/bootstrap-vue/bootstrap-vue/commit/f82f5661bdf900790bc560b9f79a2bfe5a664c63))
- **form-checkbox/radio:** allow no label in plain mode (fixes
  [#2911](https://github.com/bootstrap-vue/bootstrap-vue/issues/2911))
  ([#2912](https://github.com/bootstrap-vue/bootstrap-vue/issues/2912))
  ([6f38d9d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f38d9dc91720b5552ad2596f4b003dfe47cb2ef))
- **form-checkbox/radio:** code improvements, test suites, and docs update (Closes
  [#2718](https://github.com/bootstrap-vue/bootstrap-vue/issues/2718))
  ([#2721](https://github.com/bootstrap-vue/bootstrap-vue/issues/2721))
  ([285a2e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/285a2e1c0ac2ce4ada2c2c3a1ac33366e418bdf8))
- **form-file:** add in prop and scoped slot for formatting selected file names
  ([#2902](https://github.com/bootstrap-vue/bootstrap-vue/issues/2902))
  ([f53b5f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/f53b5f8de2701dab527d82146951b775451257a6))
- **form-group:** make `aria-live` attribute on feedback configurable (closes
  [#3057](https://github.com/bootstrap-vue/bootstrap-vue/issues/3057))
  ([#3058](https://github.com/bootstrap-vue/bootstrap-vue/issues/3058))
  ([6161b8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/6161b8ab44e494600edf828c0dfc966b5e920e27))
- **form-input:** Added support for datalists to text form-inputs
  ([#2781](https://github.com/bootstrap-vue/bootstrap-vue/issues/2781))
  ([0339ad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/0339ad80e4621d6c1eb3eaa250f95ae7e48b746e))
- **form-textarea:** add `noAutoShrink` prop (closes
  [#2664](https://github.com/bootstrap-vue/bootstrap-vue/issues/2664))
  ([#2666](https://github.com/bootstrap-vue/bootstrap-vue/issues/2666))
  ([a29c40c](https://github.com/bootstrap-vue/bootstrap-vue/commit/a29c40c147026c0a5eba35b893caba070bde63a6))
- **forms:** add state prop to invalid and valid feedback + docs update
  ([#2611](https://github.com/bootstrap-vue/bootstrap-vue/issues/2611))
  ([9df8dac](https://github.com/bootstrap-vue/bootstrap-vue/commit/9df8dac375213f68ea1a00e60361a8eb46ab6dc2))
- **forms:** new b-form-datalist helper component
  ([#2899](https://github.com/bootstrap-vue/bootstrap-vue/issues/2899))
  ([e9a8e85](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9a8e8547b1248f01705eaa981ca35afe644bc4a))
- **link:** Add support for nuxt-link
  ([#2384](https://github.com/bootstrap-vue/bootstrap-vue/issues/2384))
  ([4bd462a](https://github.com/bootstrap-vue/bootstrap-vue/commit/4bd462ad97bcb65a694b9d1f6054df378de38ea3))
- **list-group:** support horizontal layout
  ([#2536](https://github.com/bootstrap-vue/bootstrap-vue/issues/2536))
  ([10fa210](https://github.com/bootstrap-vue/bootstrap-vue/commit/10fa21061ea0f84938375cbcf804b4864e6a748b))
- **modal:** Add `dialogClass` prop
  ([#2465](https://github.com/bootstrap-vue/bootstrap-vue/issues/2465))
  ([34ae267](https://github.com/bootstrap-vue/bootstrap-vue/commit/34ae267750d5b56d3385386315a937875149c5b2))
- **modal:** add modal-backdrop slot
  ([#2688](https://github.com/bootstrap-vue/bootstrap-vue/issues/2688))
  ([ce18ffd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce18ffd25ce13a5aeb05b2ca1267fd74a097f16f))
- **modal:** add support for scrollable modal dialog content
  ([#2535](https://github.com/bootstrap-vue/bootstrap-vue/issues/2535))
  ([5c01faf](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c01faff3d0c39293a243f87ad9da6fd7c5bc489))
- **modal:** add toggle method and root event (Closes
  [#2708](https://github.com/bootstrap-vue/bootstrap-vue/issues/2708))
  ([#2709](https://github.com/bootstrap-vue/bootstrap-vue/issues/2709))
  ([f67218e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f67218e7e35773532b4a935980674a1de75d6cc5))
- **modal:** add variant prop for header close button
  ([#2765](https://github.com/bootstrap-vue/bootstrap-vue/issues/2765))
  ([b7e95d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/b7e95d9ee0def0ec3b21eebc52f0cdaf756ccf8c))
- **modal:** auto return focus to trigger elements using document.activeElement if no return focus
  provided ([#3033](https://github.com/bootstrap-vue/bootstrap-vue/issues/3033))
  ([e5c0aa5](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5c0aa571760fe6683af844e90e3549f08fecc4a))
- **modal:** remove BvModalEvent deprecations
  ([#3864](https://github.com/bootstrap-vue/bootstrap-vue/issues/3864))
  ([90c299c](https://github.com/bootstrap-vue/bootstrap-vue/commit/90c299cd169c709ee3b0e7525039ddc974a8f6df))
- **modal:** support for optionally scoped slots and new `Vue.prototype.$bvModal` helper
  ([#3056](https://github.com/bootstrap-vue/bootstrap-vue/issues/3056))
  ([b647830](https://github.com/bootstrap-vue/bootstrap-vue/commit/b647830779954b0155c96a7396bef55872b495f0))
- **modal:** use PortalVue for modal placement
  ([#3157](https://github.com/bootstrap-vue/bootstrap-vue/issues/3157))
  ([6325528](https://github.com/bootstrap-vue/bootstrap-vue/commit/632552853df9016b61ea7f42a3a9733c3ec23446))
- **nuxt:** add `usePretranspiled` option
  ([#3048](https://github.com/bootstrap-vue/bootstrap-vue/issues/3048))
  ([8022481](https://github.com/bootstrap-vue/bootstrap-vue/commit/8022481c302d77aede311c88707fd8742a152eed))
- **nuxt:** handle edge cases where component, directive and plugin names are passed as `camelCase`
  or `kebab-case` ([#3418](https://github.com/bootstrap-vue/bootstrap-vue/issues/3418))
  ([ce3ba73](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce3ba739ae7902302bee1738d2a52cc6a534f868))
- **nuxt:** module improvements
  ([#2593](https://github.com/bootstrap-vue/bootstrap-vue/issues/2593))
  ([0795fea](https://github.com/bootstrap-vue/bootstrap-vue/commit/0795fea3f29ae3a5157af6fdb0e5fd5a7561d4c3))
- **nuxt module:** alias `esm/` and `es/` to `src/` for Nuxt prod mode
  ([#3423](https://github.com/bootstrap-vue/bootstrap-vue/issues/3423))
  ([ae2040b](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae2040b2dfa7eba75d0e6468bf7321b5ac6e8ec5))
- **nuxt module:** optimize imports into single import statements
  ([#3325](https://github.com/bootstrap-vue/bootstrap-vue/issues/3325))
  ([ef71a3b](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef71a3b04746c673c1c4c19efcee9685651b3e1a))
- **nuxt-module:** add tree-shaking support to Nuxt module
  ([#2654](https://github.com/bootstrap-vue/bootstrap-vue/issues/2654))
  ([9aaf32f](https://github.com/bootstrap-vue/bootstrap-vue/commit/9aaf32fca77826d28e239fc599292829a3b46bd2))
- **pagination-nav:** autodetect current page based on $route/URL. Add support array of links
  ([#2836](https://github.com/bootstrap-vue/bootstrap-vue/issues/2836))
  ([65e12f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/65e12f84c1d27443367cc1d6de0459c36fcf68fe))
- **popover/tooltip:** Add `boundaryPadding` prop to override Popper.js default padding
  ([#2475](https://github.com/bootstrap-vue/bootstrap-vue/issues/2475))
  ([c8ad487](https://github.com/bootstrap-vue/bootstrap-vue/commit/c8ad487c1583beead9de4b5af49d4a8a646d1b3f))
- **scrollspy:** support when vue-router is in `hash` based route mode (closes
  [#2722](https://github.com/bootstrap-vue/bootstrap-vue/issues/2722))
  ([#2953](https://github.com/bootstrap-vue/bootstrap-vue/issues/2953))
  ([a713dd4](https://github.com/bootstrap-vue/bootstrap-vue/commit/a713dd48ce5794f311b4f2ec23d51b5fe272e7b9))
- **security:** strip html tags
  ([#2479](https://github.com/bootstrap-vue/bootstrap-vue/issues/2479))
  ([3c6ba3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c6ba3e44de425120990f671436a7b163742b5cb))
- **table:** "Debounce" providerFunction and refresh methods
  ([#2393](https://github.com/bootstrap-vue/bootstrap-vue/issues/2393))
  ([d5f0462](https://github.com/bootstrap-vue/bootstrap-vue/commit/d5f04621a11cfc52c4333b12117272b5e8078654))
- **table:** add basic keyboard nav when table has row-clicked handler or is selctable (closes
  [#2869](https://github.com/bootstrap-vue/bootstrap-vue/issues/2869))
  ([#2870](https://github.com/bootstrap-vue/bootstrap-vue/issues/2870))
  ([ddcd66a](https://github.com/bootstrap-vue/bootstrap-vue/commit/ddcd66a07058d570e98a70557f2eaf871ea44949))
- **table:** add IDs to tbody > tr elements if primary-key provided (closes
  [#2693](https://github.com/bootstrap-vue/bootstrap-vue/issues/2693))
  ([#2694](https://github.com/bootstrap-vue/bootstrap-vue/issues/2694))
  ([3d72404](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d72404832d3ca99aef1d3d66f8107d8b638c631))
- **table:** add new prop `table-class` for applying classes to table root element (closes
  [#3138](https://github.com/bootstrap-vue/bootstrap-vue/issues/3138))
  ([#3148](https://github.com/bootstrap-vue/bootstrap-vue/issues/3148))
  ([5deb5db](https://github.com/bootstrap-vue/bootstrap-vue/commit/5deb5dbf81713c7834a9b1884a42de04280acf6e))
- **table:** add sticky header support (closes
  [#2085](https://github.com/bootstrap-vue/bootstrap-vue/issues/2085))
  ([#3831](https://github.com/bootstrap-vue/bootstrap-vue/issues/3831))
  ([a5f7266](https://github.com/bootstrap-vue/bootstrap-vue/commit/a5f7266589955650df8df628bdfa737d2f1187aa))
- **table:** add support for scoped empty slots
  ([#2641](https://github.com/bootstrap-vue/bootstrap-vue/issues/2641))
  ([7917557](https://github.com/bootstrap-vue/bootstrap-vue/commit/7917557db6b24fd152968bfc93bcda8370421fb5))
- **table:** add support for transitions on tbody element (Closes
  [#1821](https://github.com/bootstrap-vue/bootstrap-vue/issues/1821))
  ([#2450](https://github.com/bootstrap-vue/bootstrap-vue/issues/2450))
  ([91514af](https://github.com/bootstrap-vue/bootstrap-vue/commit/91514af445221286ef0bc55985556d58e3c54fdc))
- **table:** add table row middle click (auxclicked) event
  ([#2425](https://github.com/bootstrap-vue/bootstrap-vue/issues/2425))
  ([23250a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/23250a2ac738c73a38d4834b97756409fe1de549))
- **table:** add TypeScript definitions for table fields
  ([#2867](https://github.com/bootstrap-vue/bootstrap-vue/issues/2867))
  ([436e8c1](https://github.com/bootstrap-vue/bootstrap-vue/commit/436e8c1d4ce9e3eff2053f3a02b834687c8b32b4))
- **table:** added `thead-top` slot to table (closes
  [#2489](https://github.com/bootstrap-vue/bootstrap-vue/issues/2489))
  ([#2653](https://github.com/bootstrap-vue/bootstrap-vue/issues/2653))
  ([fbb549c](https://github.com/bootstrap-vue/bootstrap-vue/commit/fbb549cf6c77f7e60eca3f275c84b49115c90b49))
- **table:** better default rendering of unformatted object values
  ([#2733](https://github.com/bootstrap-vue/bootstrap-vue/issues/2733))
  ([ee84672](https://github.com/bootstrap-vue/bootstrap-vue/commit/ee846721ef30f688a6839e3046a7a705daaead7d))
- **table:** create table child element helper components, plus new `sort-null-last` and
  `table-variant` props. ([#3808](https://github.com/bootstrap-vue/bootstrap-vue/issues/3808))
  ([981114b](https://github.com/bootstrap-vue/bootstrap-vue/commit/981114b5d9bf8a9a31855ff4e27a59efa8818c3f))
- **table:** don't render `thead` or `tfoot` if no detected fields
  ([#3553](https://github.com/bootstrap-vue/bootstrap-vue/issues/3553))
  ([a924889](https://github.com/bootstrap-vue/bootstrap-vue/commit/a924889bd7e53f705c1f61edd5c44618a9aec21d))
- **table:** make some slots available either as scoped or unscoped
  ([#2740](https://github.com/bootstrap-vue/bootstrap-vue/issues/2740))
  ([ab7937e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab7937e04ce6f6c4d146c8374f4bec155bacbc1c))
- **table:** make table sort icons configurable via SCSS variables
  ([#3156](https://github.com/bootstrap-vue/bootstrap-vue/issues/3156))
  ([a72f134](https://github.com/bootstrap-vue/bootstrap-vue/commit/a72f134be9a8e808a16a261b0f1203f8f08d6f6f))
- **table:** remove deprecated slot names, introduce new slot names
  ([#3866](https://github.com/bootstrap-vue/bootstrap-vue/issues/3866))
  ([249efd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/249efd9a61abe129ed429fa5f50a9524589e4ed0))
- **tables:** add support for custom header attributes (closes
  [#2244](https://github.com/bootstrap-vue/bootstrap-vue/issues/2244))
  ([#3876](https://github.com/bootstrap-vue/bootstrap-vue/issues/3876))
  ([8784f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/8784f315f65bbf796dcba1e433427f0159758769))
- **tables:** add support for sticky columns
  ([#3847](https://github.com/bootstrap-vue/bootstrap-vue/issues/3847))
  ([5b5f2b8](https://github.com/bootstrap-vue/bootstrap-vue/commit/5b5f2b8bca2ee5cf95eff1e0457a581f651c9883))
- **tabs:** add `fill`, `justified` and `active-class` props (closes
  [#3053](https://github.com/bootstrap-vue/bootstrap-vue/issues/3053),
  [#2518](https://github.com/bootstrap-vue/bootstrap-vue/issues/2518))
  ([#3061](https://github.com/bootstrap-vue/bootstrap-vue/issues/3061))
  ([b6557ad](https://github.com/bootstrap-vue/bootstrap-vue/commit/b6557ad7edbd8b79b332a12979d00f1df17ee547))
- **tabs:** new named slot `tabs-start` for prepending tab buttons, deprecates `tabs` slot in favour
  of `tabs-end` (closes [#3678](https://github.com/bootstrap-vue/bootstrap-vue/issues/3678))
  ([#3679](https://github.com/bootstrap-vue/bootstrap-vue/issues/3679))
  ([0b5f552](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b5f55229593d286bce17e01caa3141fa8ce6490))
- **tabs:** remove deprecations
  ([#3863](https://github.com/bootstrap-vue/bootstrap-vue/issues/3863))
  ([0edac49](https://github.com/bootstrap-vue/bootstrap-vue/commit/0edac49addf497c9012566c9517c26f2139e0d02))
- **toast:** add Bootstrap v4.3 Toasts
  ([#3093](https://github.com/bootstrap-vue/bootstrap-vue/issues/3093))
  ([c31b4ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/c31b4ffb094f54360fa1b13c45f79005bddb1355))
- **toast:** add SCSS variable for default toast background opacity + standardize a few BootstrapVue
  SCSS variable names ([#3775](https://github.com/bootstrap-vue/bootstrap-vue/issues/3775))
  ([5799075](https://github.com/bootstrap-vue/bootstrap-vue/commit/57990753ef1c1177e29a5d9d1e136ef5b7e5e198))
- **toast:** updates to toaster SCSS and structure and enable hover-pause
  ([#3135](https://github.com/bootstrap-vue/bootstrap-vue/issues/3135))
  ([263f206](https://github.com/bootstrap-vue/bootstrap-vue/commit/263f20629c60dc5ef34de61f66d60c295a5a25c7))
- **tooltip/popover:** remove SCSS deprecations
  ([#3869](https://github.com/bootstrap-vue/bootstrap-vue/issues/3869))
  ([bea49d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/bea49d41a5b3d48856f2170a944a5b1fd9f0ed8b))
- add BOOTSTRAP_VUE_NO_WARN environment variable to hide warnings
  ([#2826](https://github.com/bootstrap-vue/bootstrap-vue/issues/2826))
  ([44d0351](https://github.com/bootstrap-vue/bootstrap-vue/commit/44d03515568ad0ab1dd5e0eb0251d25e72b4da01))
- minor code improvements ([#3682](https://github.com/bootstrap-vue/bootstrap-vue/issues/3682))
  ([2fb5ce8](https://github.com/bootstrap-vue/bootstrap-vue/commit/2fb5ce823a577fcc2414d78bd43ed9e5351cb1c0))
- **table:** don't show empty row slot if table busy and busy slot provided (Closes
  [#2565](https://github.com/bootstrap-vue/bootstrap-vue/issues/2565))
  ([#2572](https://github.com/bootstrap-vue/bootstrap-vue/issues/2572))
  ([6fd31a4](https://github.com/bootstrap-vue/bootstrap-vue/commit/6fd31a495d26f6babbe69b590029816e2db82b5d))
- **table:** new option to disable footer sorting
  ([#2802](https://github.com/bootstrap-vue/bootstrap-vue/issues/2802))
  ([bc443a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc443a3e4499bebfea7e4596c44454dfa9a1f33a))
- **tooltip:** add in SCSS support for specifying tooltip variant background color level
  ([#3653](https://github.com/bootstrap-vue/bootstrap-vue/issues/3653))
  ([d7cb071](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7cb0714d9aaf97ef2bcdd8c2526e93600e0fd12))
- **tooltip, popover:** add support for contextual variants and custom class (closes
  [#1983](https://github.com/bootstrap-vue/bootstrap-vue/issues/1983),
  [#2075](https://github.com/bootstrap-vue/bootstrap-vue/issues/2075))
  ([#3644](https://github.com/bootstrap-vue/bootstrap-vue/issues/3644))
  ([695edae](https://github.com/bootstrap-vue/bootstrap-vue/commit/695edaec5b1739703f2e9cfe7accea8ac7a7faf3))
- **tooltip, popover:** remove need for route watcher
  ([#3583](https://github.com/bootstrap-vue/bootstrap-vue/issues/3583))
  ([98844b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/98844b4feb95236811644e8139294e8272d5e06a))
- **types:** add `noCloseButton` property to `BvToastOptions` type declaration
  ([#3636](https://github.com/bootstrap-vue/bootstrap-vue/issues/3636))
  ([5aa9211](https://github.com/bootstrap-vue/bootstrap-vue/commit/5aa9211be2363997bb2d45c3b2e538d46ee2a2b3))
- add `"source": "src/index.js"` entry in package.json
  ([#3422](https://github.com/bootstrap-vue/bootstrap-vue/issues/3422))
  ([0878ca6](https://github.com/bootstrap-vue/bootstrap-vue/commit/0878ca63ea97f6425b54b9d3263e1fcfafaeb9cc))
- console warn if multiple instances of Vue detected (addresses
  [#3040](https://github.com/bootstrap-vue/bootstrap-vue/issues/3040))
  ([#3220](https://github.com/bootstrap-vue/bootstrap-vue/issues/3220))
  ([41db3e2](https://github.com/bootstrap-vue/bootstrap-vue/commit/41db3e23c40d37ccb807b2fe79fef7832426413c))
- don't warn about multiple Vue instances when testing in JSDOM (closes
  [#3303](https://github.com/bootstrap-vue/bootstrap-vue/issues/3303))
  ([#3315](https://github.com/bootstrap-vue/bootstrap-vue/issues/3315))
  ([0caa29b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0caa29b836f492ba5883f1d80c93c16ac04ed097))
- improved tree-shaking when importing individual components
  ([#3462](https://github.com/bootstrap-vue/bootstrap-vue/issues/3462))
  ([2df1ab9](https://github.com/bootstrap-vue/bootstrap-vue/commit/2df1ab9e1c42af8f630772ad1b5cc7003f8d34f9))
- **toast:** add additional options to global default config (closes
  [#3169](https://github.com/bootstrap-vue/bootstrap-vue/issues/3169))
  ([#3170](https://github.com/bootstrap-vue/bootstrap-vue/issues/3170))
  ([b01e01c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b01e01c1cb370be0a7c5f35cef36825e2ae0d23e))
- **types:** better type declarations (closes
  [#1976](https://github.com/bootstrap-vue/bootstrap-vue/issues/1976))
  ([#3283](https://github.com/bootstrap-vue/bootstrap-vue/issues/3283))
  ([a42abd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/a42abd033361a1e9445c4e9c49bd679858b915b4))
- **types:** create more typescript typings, and simplify component/directive/plugin imports.
  ([#3209](https://github.com/bootstrap-vue/bootstrap-vue/issues/3209))
  ([50bbe6a](https://github.com/bootstrap-vue/bootstrap-vue/commit/50bbe6ad381cb71e2b27d539755fb33022c2ba1e))
- make more component appearance prop defaults globally configurable (closes
  [#3173](https://github.com/bootstrap-vue/bootstrap-vue/issues/3173))
  ([#3175](https://github.com/bootstrap-vue/bootstrap-vue/issues/3175))
  ([f7cf28c](https://github.com/bootstrap-vue/bootstrap-vue/commit/f7cf28c9c1f516e137d5479c8542440512e0a834))
- **util/get, table:** handle edge case where user has dot in actual item data field key (Closes
  [#2762](https://github.com/bootstrap-vue/bootstrap-vue/issues/2762))
  ([#2764](https://github.com/bootstrap-vue/bootstrap-vue/issues/2764))
  ([ee52844](https://github.com/bootstrap-vue/bootstrap-vue/commit/ee52844465da43ed53a3bdf0cc63f1b392b259b0))
- **utils:** es6ify functions wherever possible
  ([#2825](https://github.com/bootstrap-vue/bootstrap-vue/issues/2825))
  ([e8f0ed3](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8f0ed389d9b9d8e1ea0d5fcb6a5c1e91fb94d60))
- **utils/noop:** add `noop()` util
  ([#2892](https://github.com/bootstrap-vue/bootstrap-vue/issues/2892))
  ([61b75dc](https://github.com/bootstrap-vue/bootstrap-vue/commit/61b75dc6ecee8d0d0ee83b68dbb87a88714d0e89))
- **v-b-toggle:** make targets reactive to updates (closes
  [#3165](https://github.com/bootstrap-vue/bootstrap-vue/issues/3165))
  ([#3167](https://github.com/bootstrap-vue/bootstrap-vue/issues/3167))
  ([6eff6d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/6eff6d96b1d03204d25609bd093fc56ea20be14e))
- switch to PascalCase name for all components
  ([#2305](https://github.com/bootstrap-vue/bootstrap-vue/issues/2305))
  ([6179e61](https://github.com/bootstrap-vue/bootstrap-vue/commit/6179e61b1e0b4b6310a79f67075a4fe9790f2750))
- **alert:** Add fade prop ([#1785](https://github.com/bootstrap-vue/bootstrap-vue/issues/1785))
  ([0999b4c](https://github.com/bootstrap-vue/bootstrap-vue/commit/0999b4cc4b4943741aef71367dc354af45decbc0))
- **breadcrumb-link:** support children elements
  ([#1832](https://github.com/bootstrap-vue/bootstrap-vue/issues/1832))
  ([#1833](https://github.com/bootstrap-vue/bootstrap-vue/issues/1833))
  ([42175f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/42175f80047ad7b2ad20ec5de13402d9e01c0dfe))
- **build:** replace uglify-es with terser
  ([#2238](https://github.com/bootstrap-vue/bootstrap-vue/issues/2238))
  ([bd95ad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd95ad83f5265683ad4ea75ffdf592290ed18199))
- **button:** Make button tag configurable
  ([#1929](https://github.com/bootstrap-vue/bootstrap-vue/issues/1929))
  ([afcadd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/afcadd9733daba296949c27eadf80cf924d5f86f))
- **card:** include custom styles for card-img-left and card-img-right
  ([#2292](https://github.com/bootstrap-vue/bootstrap-vue/issues/2292))
  ([a72d494](https://github.com/bootstrap-vue/bootstrap-vue/commit/a72d4949e4b8578601d5620b5d30abaf9b042145))
- **card:** support left and right image placement
  ([#1981](https://github.com/bootstrap-vue/bootstrap-vue/issues/1981))
  ([66194a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/66194a6a3c49d0ceadd90e8a2fda6b9105675236))
- **core:** Add SCSS support (fixes
  [#2201](https://github.com/bootstrap-vue/bootstrap-vue/issues/2201))
  ([#2221](https://github.com/bootstrap-vue/bootstrap-vue/issues/2221))
  ([f8326a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/f8326a2afa4eef6cfc0df00fb32c360543499deb))
- **css:** create SCSS versions of CSS
  ([#2218](https://github.com/bootstrap-vue/bootstrap-vue/issues/2218))
  ([d6ba6db](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6ba6db5fcf91873a48f3357c4e2f322df50bdea))
- **docs:** Allow sub-components to show reference info for slots and events
  ([#2132](https://github.com/bootstrap-vue/bootstrap-vue/issues/2132))
  ([52c960b](https://github.com/bootstrap-vue/bootstrap-vue/commit/52c960bf179bf78ddc4de1b0b326c78d5627173c))
- **docs:** conditionally load babel-standalone only on browsers that need transpilation
  ([#2294](https://github.com/bootstrap-vue/bootstrap-vue/issues/2294))
  ([1578732](https://github.com/bootstrap-vue/bootstrap-vue/commit/1578732fbd69c13b9411e111f8a1e68c8c3075b8))
- **docs:** use babel-standalone in playground/v-play to support IE
  ([#2286](https://github.com/bootstrap-vue/bootstrap-vue/issues/2286))
  ([46f8d4b](https://github.com/bootstrap-vue/bootstrap-vue/commit/46f8d4b14d9b0d6c9eee2aafae605b2654639d1f))
- **dropdown:** add toggleClass prop
  ([#1485](https://github.com/bootstrap-vue/bootstrap-vue/issues/1485))
  ([da16cc0](https://github.com/bootstrap-vue/bootstrap-vue/commit/da16cc0cc10df339550f2fdeb48b85919b78536d))
- **dropdown:** make show/hide events cancelable . also adds toggle event
  ([#1807](https://github.com/bootstrap-vue/bootstrap-vue/issues/1807))
  ([4136bd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/4136bd9e7c1b6469de066771a548fcb8d09588f7))
- **dropdown:** support 'href', 'to' and 'variant' in split button mode (Closes
  [#1960](https://github.com/bootstrap-vue/bootstrap-vue/issues/1960))
  ([#2301](https://github.com/bootstrap-vue/bootstrap-vue/issues/2301))
  ([31b7d19](https://github.com/bootstrap-vue/bootstrap-vue/commit/31b7d1928e8ff8e233559848f9f959b690d29e25))
- **dropdown, nav-item-dropdown:** support menuClass and extraMenuClasses
  ([#1683](https://github.com/bootstrap-vue/bootstrap-vue/issues/1683))
  ([3da5f18](https://github.com/bootstrap-vue/bootstrap-vue/commit/3da5f184f91b928cf34de4d169cf00e56f2dde4d))
- **dropdowns:** add boundary prop for controlling placement constraint
  ([#1440](https://github.com/bootstrap-vue/bootstrap-vue/issues/1440))
  ([01498cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/01498cb4066af0d65512734f531e63b4f39bcb55))
- **dropfoen:** Add `dropright` and `dropleft` direction support
  ([#2117](https://github.com/bootstrap-vue/bootstrap-vue/issues/2117))
  ([e186639](https://github.com/bootstrap-vue/bootstrap-vue/commit/e1866393dcfced84da2525307a317a49dd9e29ff)),
  closes [#2108](https://github.com/bootstrap-vue/bootstrap-vue/issues/2108)
- **form-checkbox:** support custom switch styling
  ([#2293](https://github.com/bootstrap-vue/bootstrap-vue/issues/2293))
  ([3508ea2](https://github.com/bootstrap-vue/bootstrap-vue/commit/3508ea20af413326e21c1b4ec3d0f049e12557ce))
- **form-file:** reset file input when value set to null or empty string
  ([#2170](https://github.com/bootstrap-vue/bootstrap-vue/issues/2170))
  ([ab44375](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab44375a4ac2fd4462652550c12886adca8ca8fe))
- **form-group:** Add multiple breakpoint support for label (Closes
  [#2230](https://github.com/bootstrap-vue/bootstrap-vue/issues/2230))
  ([#2258](https://github.com/bootstrap-vue/bootstrap-vue/issues/2258))
  ([5e453f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e453f9e331705ed0970f0468720495bb9413c8a))
- **form-input:** add step, min and max props for use with number type
  ([40ff380](https://github.com/bootstrap-vue/bootstrap-vue/commit/40ff38063d4cf99aa9f686322a48d729566ca037))
- **form-input:** initial SCSS file
  ([#2217](https://github.com/bootstrap-vue/bootstrap-vue/issues/2217))
  ([923d20b](https://github.com/bootstrap-vue/bootstrap-vue/commit/923d20be0d524a943cd9ee0177c945caaa8d483e))
- **form-input:** support custom-range input + validation and input styles
  ([#2120](https://github.com/bootstrap-vue/bootstrap-vue/issues/2120))
  ([013a737](https://github.com/bootstrap-vue/bootstrap-vue/commit/013a737f4f35d87cbe6b2023ae16f3d12b9cc595))
- **form-input:** Use new form-text mixin and add trim and number modifiers
  ([#2204](https://github.com/bootstrap-vue/bootstrap-vue/issues/2204))
  ([3c9936e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c9936e4cdbfb1fe961c0b34116969cb7439608e))
- **form-radio-check:** migrate to using provide/inject, add inline props
  ([#2241](https://github.com/bootstrap-vue/bootstrap-vue/issues/2241))
  ([c0a68d5](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0a68d5aa3d25f7b010b6641567124651d74b657))
- **form-select:** Expose focus and blur methods (Closes
  [#2237](https://github.com/bootstrap-vue/bootstrap-vue/issues/2237))
  ([#2257](https://github.com/bootstrap-vue/bootstrap-vue/issues/2257))
  ([ded7679](https://github.com/bootstrap-vue/bootstrap-vue/commit/ded7679c16cbe7a4700864a5c3f3da20c84dd0bc))
- **forms:** add form prop to all inputs. fixes
  [#2154](https://github.com/bootstrap-vue/bootstrap-vue/issues/2154)
  ([#2172](https://github.com/bootstrap-vue/bootstrap-vue/issues/2172))
  ([6009d72](https://github.com/bootstrap-vue/bootstrap-vue/commit/6009d723d1c408c0b8b6abc285bc5896cad6daa6))
- **forms:** add support for tooltip-style feedback text
  ([#2188](https://github.com/bootstrap-vue/bootstrap-vue/issues/2188))
  ([5203436](https://github.com/bootstrap-vue/bootstrap-vue/commit/520343685adeddeaa758a01d0e1a5c0aa31d7caf))
- **list-group:** add striped support
  ([#2313](https://github.com/bootstrap-vue/bootstrap-vue/issues/2313))
  ([3491943](https://github.com/bootstrap-vue/bootstrap-vue/commit/34919431a44a37e74708432013eec32488ef9894))
- **modal:** add 'aria-modal="true"' to modal when open.
  ([#2314](https://github.com/bootstrap-vue/bootstrap-vue/issues/2314))
  ([dbf4920](https://github.com/bootstrap-vue/bootstrap-vue/commit/dbf4920339ce01210c9796b7a4e0a1baf1a1b6cc))
- **modal:** add `modalClass` property to `bModal`
  ([#1682](https://github.com/bootstrap-vue/bootstrap-vue/issues/1682))
  ([c7a10ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7a10ef7c076e724709d13c71856fa05d321390c))
- **modal:** Make stackable optional
  ([#2259](https://github.com/bootstrap-vue/bootstrap-vue/issues/2259))
  ([2322044](https://github.com/bootstrap-vue/bootstrap-vue/commit/2322044b84a207e4fc339b006ee5d0a82607e391))
- **modal:** new props for adding classes to header, body and footer
  ([#1462](https://github.com/bootstrap-vue/bootstrap-vue/issues/1462))
  ([bc67a2d](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc67a2d7f3cbf7e115f69fdbe97e6e8b6d4b225a))
- **modal:** Support multiple modals open at once
  ([#2164](https://github.com/bootstrap-vue/bootstrap-vue/issues/2164))
  ([2709902](https://github.com/bootstrap-vue/bootstrap-vue/commit/2709902c28b8347763c8690032fb9a1ecc41ebeb))
- **nav-item-dropdown:** add extra-toggle-classes prop with tests and docs. closes
  [#1550](https://github.com/bootstrap-vue/bootstrap-vue/issues/1550).
  ([#1555](https://github.com/bootstrap-vue/bootstrap-vue/issues/1555))
  ([7967018](https://github.com/bootstrap-vue/bootstrap-vue/commit/7967018990d461b20c9d1fdf175b2eda19f90733))
- **package:** align dependencies to prevent warnings.
  ([#975](https://github.com/bootstrap-vue/bootstrap-vue/issues/975))
  ([b70a9f7](https://github.com/bootstrap-vue/bootstrap-vue/commit/b70a9f70e36db8a35a726b8e3916288e85750042))
- **pagination:** added slots for first, prev, next, last, and ellipsis. Fixes
  [#1870](https://github.com/bootstrap-vue/bootstrap-vue/issues/1870).
  ([#1980](https://github.com/bootstrap-vue/bootstrap-vue/issues/1980))
  ([1b7e7de](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b7e7de928ddcfd68f2d30d19f1e065889d1879c))
- **pkg:** update dependendencies (bootstrap 4.0.0-beta.3)
  ([afb82a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/afb82a8b4d0f7f308af85c3c5c80897cce6ace25))
- **security:** Strip HTML script tags before inserting content into DOM. Fixes
  [#1974](https://github.com/bootstrap-vue/bootstrap-vue/issues/1974),[#1665](https://github.com/bootstrap-vue/bootstrap-vue/issues/1665)
  ([#2129](https://github.com/bootstrap-vue/bootstrap-vue/issues/2129))
  ([6dde0cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/6dde0cba3f89374fea3cb09b8a6b90363bf04243))
- **security:** Strip HTML script tags before inserting content into DOM. Fixes
  [#1974](https://github.com/bootstrap-vue/bootstrap-vue/issues/1974),[#1665](https://github.com/bootstrap-vue/bootstrap-vue/issues/1665)
  ([#2134](https://github.com/bootstrap-vue/bootstrap-vue/issues/2134))
  ([ba6f3f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/ba6f3f8359e257589d744f180312c09bf9f12289)),
  closes [#1931](https://github.com/bootstrap-vue/bootstrap-vue/issues/1931)
- **spinner:** Pre-Release Bootstrap V4.2 spinners
  ([#2306](https://github.com/bootstrap-vue/bootstrap-vue/issues/2306))
  ([bf3994f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf3994ffa37c513535c3c6d724f86acca6bf4b4f))
- **table:** add borderless prop
  ([#2300](https://github.com/bootstrap-vue/bootstrap-vue/issues/2300))
  ([dabe150](https://github.com/bootstrap-vue/bootstrap-vue/commit/dabe15072ff8dccd087f6a0ad3cca06d7ccceac7))
- **table:** add field to the table column data cell slots
  ([#1705](https://github.com/bootstrap-vue/bootstrap-vue/issues/1705))
  ([e013d59](https://github.com/bootstrap-vue/bootstrap-vue/commit/e013d59373a7bbc6576b414b48c29f7f01123827))
- **table:** Add no-sort-reset prop
  ([#1784](https://github.com/bootstrap-vue/bootstrap-vue/issues/1784))
  ([26aaeab](https://github.com/bootstrap-vue/bootstrap-vue/commit/26aaeab1de439491aa4950d642d486d539b10c4e))
- **table:** Add row-unhovered event
  ([#1874](https://github.com/bootstrap-vue/bootstrap-vue/issues/1874))
  ([a87cad1](https://github.com/bootstrap-vue/bootstrap-vue/commit/a87cad14cd1e24af01da1aec2ded118ff36e74f7))
- **table:** Add table-busy slot for loading status. Closes
  [#1859](https://github.com/bootstrap-vue/bootstrap-vue/issues/1859)
  ([#2196](https://github.com/bootstrap-vue/bootstrap-vue/issues/2196))
  ([a654a61](https://github.com/bootstrap-vue/bootstrap-vue/commit/a654a61bac4a9d7444598cb41f5a80fb85e6045b))
- **table:** Add the sort-direction prop
  ([#1783](https://github.com/bootstrap-vue/bootstrap-vue/issues/1783))
  ([#1788](https://github.com/bootstrap-vue/bootstrap-vue/issues/1788))
  ([9e1959d](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e1959d0996f745967c10dfadae1bb8482d63a17))
- **table:** initial SCSS file ([#2216](https://github.com/bootstrap-vue/bootstrap-vue/issues/2216))
  ([db0b483](https://github.com/bootstrap-vue/bootstrap-vue/commit/db0b483f4c08df31fbe7de7507f00e46fac7f734))
- **table:** pass sortDesc to user provided sortCompare routine
  ([#1994](https://github.com/bootstrap-vue/bootstrap-vue/issues/1994))
  ([a8e4103](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8e410366ba38f304c0f88b64ab46a44536bd804))
- **table:** Remove need to add `click.stop` on inputs/links/buttons inside rows
  ([#2214](https://github.com/bootstrap-vue/bootstrap-vue/issues/2214))
  ([7d8662b](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d8662b532e32488a66064904137265ea06bd285))
- **table:** Selectable rows (fixes
  [#1790](https://github.com/bootstrap-vue/bootstrap-vue/issues/1790))
  ([#2260](https://github.com/bootstrap-vue/bootstrap-vue/issues/2260))
  ([5b1cb90](https://github.com/bootstrap-vue/bootstrap-vue/commit/5b1cb905217dd6fb7cea6481e610489d390f5bf9))
- **table:** Split computedItems into multiple functions
  ([#1893](https://github.com/bootstrap-vue/bootstrap-vue/issues/1893))
  ([bb1c550](https://github.com/bootstrap-vue/bootstrap-vue/commit/bb1c55031e18a18b3dd0ca8e429293f40f0ce168))
- **table:** Support contextmenu event binding for table rows
  ([#2064](https://github.com/bootstrap-vue/bootstrap-vue/issues/2064))
  ([1eced46](https://github.com/bootstrap-vue/bootstrap-vue/commit/1eced462339a381cdb6e275c0fece2ba34447b17))
- **table:** support custom attributes per table cell in a column
  ([#1760](https://github.com/bootstrap-vue/bootstrap-vue/issues/1760))
  ([fc083e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc083e563360bc447674953d9c957ede573dd229))
- **table:** support custom classes per table cell in a column
  ([d05d6b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/d05d6b6eb32a14ff4f652915968f2443da6c6b4a))
- **table:** Support sorting on nested object properties
  ([#1868](https://github.com/bootstrap-vue/bootstrap-vue/issues/1868))
  ([b699e4b](https://github.com/bootstrap-vue/bootstrap-vue/commit/b699e4b53e10ef4d6ac612dfa1cfecf86b1327fc))
- **tabs:** add key nav prop like button toolbar has
  ([#1733](https://github.com/bootstrap-vue/bootstrap-vue/issues/1733))
  ([bc3b82b](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc3b82b5808dfd25d91a4777a227a9a2158099f3))
- **tabs/noNavStyle:** added related prop and check
  ([91c7257](https://github.com/bootstrap-vue/bootstrap-vue/commit/91c7257ba43948f3a006e4625a79408cd68de29d))
- add basic typescript declarations
  ([#1721](https://github.com/bootstrap-vue/bootstrap-vue/issues/1721))
  ([3c040f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c040f0356012a642e1a94a240dda8e2462beb10))
- **test:** test against multi versions of vue
  ([25d0b13](https://github.com/bootstrap-vue/bootstrap-vue/commit/25d0b13fc78a24349a9cee5b3916a97bfe71f641))
- upgrade to bootstrap 4.0.0 ([#1507](https://github.com/bootstrap-vue/bootstrap-vue/issues/1507))
  ([1d5b230](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d5b230bd5c91c0948308ee12d7d7be90bd0e1e8))
- **badge:** Support actionable (link) badges
  ([#1226](https://github.com/bootstrap-vue/bootstrap-vue/issues/1226))
  ([ba2b5b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/ba2b5b4dc52fa8fd8ccfce63c0b7626e9fd6977f))
- **card:** add prop body-class
  ([#1250](https://github.com/bootstrap-vue/bootstrap-vue/issues/1250))
  ([23fc3be](https://github.com/bootstrap-vue/bootstrap-vue/commit/23fc3bee4af15b9c107b968434718f57b78834d3))
- **docs:** Add TOC section in right hand column
  ([#1077](https://github.com/bootstrap-vue/bootstrap-vue/issues/1077))
  ([b9d15f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9d15f8323f41d0d00c71d37ffe0eae472349cde))
- **docs:** Better ARIA when changing routes
  ([#1102](https://github.com/bootstrap-vue/bootstrap-vue/issues/1102))
  ([d2c951a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d2c951a7b003d308d14648df573b2a09c548fa8f))
- **docs:** Hide TOC sub-sections when not `active`
  ([9d5a626](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d5a6266715c4e21c0af0e839aaa237af45dfe4c))
- **docs:** Search all keywords
  ([#1105](https://github.com/bootstrap-vue/bootstrap-vue/issues/1105))
  ([3e5b56b](https://github.com/bootstrap-vue/bootstrap-vue/commit/3e5b56b10d2ff65767dedba6be0b461f00a7357a))
- **docs:** search support
  ([7916981](https://github.com/bootstrap-vue/bootstrap-vue/commit/7916981621c9fd84c4bb45ffcc65205efdd13fef))
- **docs:** TOC add scroll into iview support
  ([d72f87a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d72f87a9f286463bb92d46cc3f1ee5139522148a))
- **dropdown:** Optionally hide the dropdown toggle caret
  ([#1197](https://github.com/bootstrap-vue/bootstrap-vue/issues/1197))
  ([960877c](https://github.com/bootstrap-vue/bootstrap-vue/commit/960877c3bbf264631a607677dabeef1fec6cc6cd))
- **dropdowns:** Allow space and cursor down to trigger opening of menus
  ([#1159](https://github.com/bootstrap-vue/bootstrap-vue/issues/1159))
  ([1249f51](https://github.com/bootstrap-vue/bootstrap-vue/commit/1249f51c05769c5d6f661f9a7c0efd401f5f4d3a))
- **eslint:** update settings to remove editor errors
  ([#792](https://github.com/bootstrap-vue/bootstrap-vue/issues/792))
  ([c33d1d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c33d1d40ea9476697a619bd83505a8b36e21c3c9))
- **form-file:** Use `label` as wrapper element + name-spaced custom CSS
  ([#1353](https://github.com/bootstrap-vue/bootstrap-vue/issues/1353))
  ([e2bc891](https://github.com/bootstrap-vue/bootstrap-vue/commit/e2bc891a1cd65703a412643eba60438a2a7b1ee9))
- **form-group:** add valid feedback support
  ([#1360](https://github.com/bootstrap-vue/bootstrap-vue/issues/1360))
  ([7f3535b](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f3535b377a11605453ea17ea393ffcc56436901))
- **form-group:** new label-size prop
  ([b8311e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/b8311e5c6842b3eeeb44e0d898876cdcc6cdab9e))
- **form-group:** new label-size prop
  ([#1422](https://github.com/bootstrap-vue/bootstrap-vue/issues/1422))
  ([dcffb5c](https://github.com/bootstrap-vue/bootstrap-vue/commit/dcffb5cad095d54b8cc6d1ccc26c730defc9a1dd))
- **form-group:** new prop for label-class, deprecate prop feedback in favor of invalid-feedback
  ([#1412](https://github.com/bootstrap-vue/bootstrap-vue/issues/1412))
  ([44f13a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/44f13a5bdcb065168b00fee77b306699456c7ecc))
- **form-group:** new prop for label-class, deprecate prop feedback in favor of invalid-feedback
  ([#1412](https://github.com/bootstrap-vue/bootstrap-vue/issues/1412))
  ([7d61cb4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d61cb4018aae44bf69043e08b71d3aae6e4cabe))
- **form-group:** render label element if prop label-for set + horizontal layout optimizations
  ([#1423](https://github.com/bootstrap-vue/bootstrap-vue/issues/1423))
  ([ce164bf](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce164bf616baca8c22db6e841b376b5fbbb76174))
- **form-group:** set aria-describedby attribute on input if label-for provided
  ([#1431](https://github.com/bootstrap-vue/bootstrap-vue/issues/1431))
  ([6bd12bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/6bd12bb77da7ab27a9f0bc829d30961d644e2eb0))
- **form-group:** Switch to fieldset+legend for better semantic/ARIA markup
  ([#1129](https://github.com/bootstrap-vue/bootstrap-vue/issues/1129))
  ([7a62b75](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a62b75e8319c8052ad9e1521d222b805fe7c785))
- **form-input:** emit input event when lazy-formatter is true
  ([#1086](https://github.com/bootstrap-vue/bootstrap-vue/issues/1086))
  ([016591c](https://github.com/bootstrap-vue/bootstrap-vue/commit/016591c805fadc842df00366e491ad952b3f6cfa))
- **form-radio+form-checkbox:** Prep for BSV4.beta.3 plain checkbox/radio validation styling
  ([#1253](https://github.com/bootstrap-vue/bootstrap-vue/issues/1253))
  ([81989ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/81989abccce5f940e02fec0c26a6eba20c9aa0b1))
- **form-select:** Emit change event on user interaction
  ([3cc0f05](https://github.com/bootstrap-vue/bootstrap-vue/commit/3cc0f05c72b2a073c6a3c5a78ab25262ee32c122))
- **modal:** Add Bootstrap V4 anticipated verticaly centered modal
  ([#1246](https://github.com/bootstrap-vue/bootstrap-vue/issues/1246))
  ([4a8ce2c](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a8ce2c6a6463d2f30c2e93f3e0bff2313afca9e))
- **modal:** fix for overflowing centered modal to scroll
  ([#1363](https://github.com/bootstrap-vue/bootstrap-vue/issues/1363))
  ([3b3ba32](https://github.com/bootstrap-vue/bootstrap-vue/commit/3b3ba3287164194260e11a2bbf641e12922e32d0))
- **nav-item-dropdown:** Add shorter aliases
  ([8986543](https://github.com/bootstrap-vue/bootstrap-vue/commit/89865431e0123586a15c063d38b635110b7aef56))
- **navbar-nav:** New b-navbar-nav component
  ([#1231](https://github.com/bootstrap-vue/bootstrap-vue/issues/1231))
  ([4bdba0e](https://github.com/bootstrap-vue/bootstrap-vue/commit/4bdba0e05a331321c284bf5591620e8d8d25c90d))
- **nuxt:** add bvCSS option. resolves
  [#1351](https://github.com/bootstrap-vue/bootstrap-vue/issues/1351).
  ([3a7517f](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a7517f41e736afdcd218a4f10171993f51dd5e2))
- **package:** add lint by default for tests
  ([f1ca71e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1ca71ebaa4b3e3d381f76513cc0b2b55d8bf8c5))
- **package:** use es build by default
  ([142d517](https://github.com/bootstrap-vue/bootstrap-vue/commit/142d517ecad405c6fcb73c112ba82998ee23d63a))
- **packaging:** add nuxt module
  ([4c58c80](https://github.com/bootstrap-vue/bootstrap-vue/commit/4c58c80e61322cee9cbfa2d37bfe07240ba03d72))
- **pagination:** Better keyboard tab support + focus styling
  ([42b31da](https://github.com/bootstrap-vue/bootstrap-vue/commit/42b31da1a12823d36a562a7640ece1b3a7d36ffd))
- **pagination-nav:** Better tab/focus management
  ([adf8dcc](https://github.com/bootstrap-vue/bootstrap-vue/commit/adf8dcca592558643604e0a4deff8a0e3f340875))
- **pagination+pagination-nav:** disabled styling now works in BS V4.beta.2
  ([#1381](https://github.com/bootstrap-vue/bootstrap-vue/issues/1381))
  ([d51349f](https://github.com/bootstrap-vue/bootstrap-vue/commit/d51349f173515b26283dd910aa02da50c0ac0017))
- **pagination+pagination-nav:** remove need for custom active focus style
  ([#1384](https://github.com/bootstrap-vue/bootstrap-vue/issues/1384))
  ([ecd9b6a](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecd9b6a657e0e126c86437f80f7adf1577975e1d))
- **pagination+pagination-nav:** remove need for custom active focus style
  ([#1384](https://github.com/bootstrap-vue/bootstrap-vue/issues/1384))
  ([1e1b099](https://github.com/bootstrap-vue/bootstrap-vue/commit/1e1b09957682905556021bea8d9053394912dad6))
- **table:** add outlined option
  ([#1355](https://github.com/bootstrap-vue/bootstrap-vue/issues/1355))
  ([7ba183e](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ba183efbbc964a529a834e2741b9ef01b4e2594))
- **table:** add responsive stacked table option
  ([#1407](https://github.com/bootstrap-vue/bootstrap-vue/issues/1407))
  ([26c35ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/26c35ba0ec44f6100c7c53caa4128af3313a936d))
- **table:** add responsive stacked table option
  ([#1407](https://github.com/bootstrap-vue/bootstrap-vue/issues/1407))
  ([df23115](https://github.com/bootstrap-vue/bootstrap-vue/commit/df231152b39a3a9049c6315a7d99b584c8fd1538))
- **table:** add toggleDetails method to scoped item slots
  ([#1404](https://github.com/bootstrap-vue/bootstrap-vue/issues/1404))
  ([e02fa49](https://github.com/bootstrap-vue/bootstrap-vue/commit/e02fa494aa13d48ed93a665d692c96b84c110ce4))
- **table:** add toggleDetails method to scoped item slots
  ([#1404](https://github.com/bootstrap-vue/bootstrap-vue/issues/1404))
  ([a9c4b7d](https://github.com/bootstrap-vue/bootstrap-vue/commit/a9c4b7dc62bf93560c566bc88d51c14fe023d828))
- **table:** Allow custom attributes in table td cell
  ([#1193](https://github.com/bootstrap-vue/bootstrap-vue/issues/1193))
  ([485adbf](https://github.com/bootstrap-vue/bootstrap-vue/commit/485adbfdf218a7bb996f9999079d4569b3acc8ba))
- **table:** BS V4.beta.2 New responsive breakpoints and table-dark class
  ([#1222](https://github.com/bootstrap-vue/bootstrap-vue/issues/1222))
  ([febdfd1](https://github.com/bootstrap-vue/bootstrap-vue/commit/febdfd1517e5182e9a69f33d5f7da27fa9427423))
- **table:** caption positioning prop
  ([#1341](https://github.com/bootstrap-vue/bootstrap-vue/issues/1341))
  ([7c86e66](https://github.com/bootstrap-vue/bootstrap-vue/commit/7c86e6618d2e6a84ac2e603b3b5493292a53e4a2))
- **table:** New fixed prop, allow disable localSort, emit context-changed event, and style tweaks
  ([#1076](https://github.com/bootstrap-vue/bootstrap-vue/issues/1076))
  ([4447c7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/4447c7cee9c77f185648cbb4b6666f5d369d91b4))
- **table:** Pass computed fields array to details scoped slot
  ([#1271](https://github.com/bootstrap-vue/bootstrap-vue/issues/1271))
  ([0745ae8](https://github.com/bootstrap-vue/bootstrap-vue/commit/0745ae8a567c5a218c26c57fc89d8804d6da476c))
- **tabs:** add name to helper component for better debugging
  ([e436a1d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e436a1d9a1f848172d10f95a0b3b171a5c295638))
- **tabs:** add name to helper component for better debugging
  ([51ef9e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/51ef9e3bbc26409e196f37c6a8ef179b3c75f8c0))
- **tabs:** add no-body prop to b-tab
  ([#1385](https://github.com/bootstrap-vue/bootstrap-vue/issues/1385))
  ([af36c0e](https://github.com/bootstrap-vue/bootstrap-vue/commit/af36c0ef7dce516f9a3dcdaded921e10d299e4d7))
- **tabs:** add no-body prop to b-tab
  ([#1385](https://github.com/bootstrap-vue/bootstrap-vue/issues/1385))
  ([ef3ff06](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef3ff069314f4cd041139e5c18f1130069617ae9))
- **tabs:** New props for adding classes to nav tab
  ([#1289](https://github.com/bootstrap-vue/bootstrap-vue/issues/1289))
  ([c6d3642](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6d3642fe590c50df1e8200a436f6dfe0bd3b3d8))
- **tabs:** vertical tabs + new props for adding classes to inner elements
  ([#1362](https://github.com/bootstrap-vue/bootstrap-vue/issues/1362))
  ([51d0e03](https://github.com/bootstrap-vue/bootstrap-vue/commit/51d0e03a14ad792966f7d9bd5da95b82158dac25))
- **tooltip popover:** Don't close if focus moves between trigger element and tip/popover
  ([#1093](https://github.com/bootstrap-vue/bootstrap-vue/issues/1093))
  ([87ffb4f](https://github.com/bootstrap-vue/bootstrap-vue/commit/87ffb4f3b4ff53290bfc4670e026e6c720ba2660))
- **tooltip+popover:** ability to programmatically show and hide tooltip and popover
  ([#1366](https://github.com/bootstrap-vue/bootstrap-vue/issues/1366))
  ([360b337](https://github.com/bootstrap-vue/bootstrap-vue/commit/360b337374146fb25b98170dd80bccc6d1812dbb)),
  closes [#1369](https://github.com/bootstrap-vue/bootstrap-vue/issues/1369)
- **tooltip+popover:** add boundary element config option (positioning constraint)
  ([#1439](https://github.com/bootstrap-vue/bootstrap-vue/issues/1439))
  ([08fd7ce](https://github.com/bootstrap-vue/bootstrap-vue/commit/08fd7ceedd97c6a08f8d7ec33c98fe8e1a586f4c))
- **tooltip+popover:** Allow delay to be object in component versions
  ([#1131](https://github.com/bootstrap-vue/bootstrap-vue/issues/1131))
  ([1a47c87](https://github.com/bootstrap-vue/bootstrap-vue/commit/1a47c87b9980e7c1c837ba0c623018aa8cf92167))
- **tooltip+popover:** Eight new placement options
  ([#1081](https://github.com/bootstrap-vue/bootstrap-vue/issues/1081))
  ([dae7855](https://github.com/bootstrap-vue/bootstrap-vue/commit/dae7855bb8b77cb770cf0b87a56647d63c62c2b7))
- **tooltip+popover:** programmatically disable/enable tooltip or popover
  ([#1387](https://github.com/bootstrap-vue/bootstrap-vue/issues/1387))
  ([c83e0d5](https://github.com/bootstrap-vue/bootstrap-vue/commit/c83e0d58f52c92d50eaf2ee5410e5d003340fd67))
- **tooltip+popover:** programmatically disable/enable tooltip or popover
  ([#1387](https://github.com/bootstrap-vue/bootstrap-vue/issues/1387))
  ([8104cb4](https://github.com/bootstrap-vue/bootstrap-vue/commit/8104cb43a6091a1b2a14ed19fc1bf0c1ec925716))
- **v-b-modal:** set role="button" if trigger element is not a button
  ([aa45d3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/aa45d3e15c4cd160dbe9f220f793facbe326fe7c))
- **v-b-toggle:** add role 'button' when trigger is not a button
  ([c2dd2d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2dd2d047e70040397cace567bdc588c6bf1aa28))
- es builds
  ([8647855](https://github.com/bootstrap-vue/bootstrap-vue/commit/8647855a8bd297340ffef8a5151304d3b2343ed7))
- make all components available as .js files
  ([#1279](https://github.com/bootstrap-vue/bootstrap-vue/issues/1279))
  ([d18eb66](https://github.com/bootstrap-vue/bootstrap-vue/commit/d18eb6663728bc74ec83a7a7b2858631a6a7c0a2))
- Make Components & Directives available as Vue plugins
  ([#1267](https://github.com/bootstrap-vue/bootstrap-vue/issues/1267))
  ([13d9a42](https://github.com/bootstrap-vue/bootstrap-vue/commit/13d9a42d9e3d9b076eef5d8de86b9e6aff73551f))
- use babel
  ([5e653e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e653e6c9d4f3386514ae9bfa7ef16b84c9a80ce))
- **b-col:** restore `.offset-*` col classes + new b-container and b-row components 🍾🍻🎉
  ([#929](https://github.com/bootstrap-vue/bootstrap-vue/issues/929))
  ([023f078](https://github.com/bootstrap-vue/bootstrap-vue/commit/023f078c03b05f45f1edb80ce11a38c54140a5a8))
- **b-img:** New component ([#933](https://github.com/bootstrap-vue/bootstrap-vue/issues/933))
  ([c4358e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4358e045d6f28be5c692e3df7f1fd33033c70ed))
- **b-img-lazy:** Lazy loaded image component
  ([#943](https://github.com/bootstrap-vue/bootstrap-vue/issues/943))
  ([68138cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/68138cbdf0d3a2647e94cda073d6627e41de422c))
- **carousel:** Add img slot to carousel-slide
  ([#879](https://github.com/bootstrap-vue/bootstrap-vue/issues/879))
  ([9d789e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d789e7dcf3c47553e3676c81b282c08a5d4b8d5))
- **carousel:** Use b-img component and id Mixin
  ([#945](https://github.com/bootstrap-vue/bootstrap-vue/issues/945))
  ([d95321b](https://github.com/bootstrap-vue/bootstrap-vue/commit/d95321bbb11759c1467ca18ced22af849da52ea9))
- **col:** BS4 column component ([#906](https://github.com/bootstrap-vue/bootstrap-vue/issues/906))
  ([9de80f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/9de80f8b215910543a0ade0c558b7c771efea281))
- **docs:** Add a new reference section
  ([#1050](https://github.com/bootstrap-vue/bootstrap-vue/issues/1050))
  ([7984117](https://github.com/bootstrap-vue/bootstrap-vue/commit/798411702d9d386b06933836d31ff452cd847496))
- **docs:** Add accessibility information for popovers
  ([099b1b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/099b1b67a17d7e8164a5635fe07fb51c9796664b))
- **docs:** Add aria roles to collapse accordion example
  ([2a34407](https://github.com/bootstrap-vue/bootstrap-vue/commit/2a344071d8c69e27a8303a68ec3227fa485c4fed))
- **docs:** Additional tooltip component usage docs
  ([d8bf486](https://github.com/bootstrap-vue/bootstrap-vue/commit/d8bf48609ec1afabb94b6639b7e396a7d17b69a6))
- **docs:** Expanded alert docs and examples
  ([f1730ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1730eeff209da7a8890f09a8eacdbab5983af24))
- **docs:** expanded popover component docs
  ([9f5dd75](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f5dd75271691c93adf94fbbc9354a54be3153ea))
- **docs:** Expanded popover component docs
  ([ccd1c7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ccd1c7c513fae3347d4583280a46f201da9b2450))
- **docs:** Improved collapse examples and documentation
  ([541fada](https://github.com/bootstrap-vue/bootstrap-vue/commit/541fada67a203af7f4d673b675150ac7dc6b4880))
- **docs:** New reference section wrt project relative urls and image based Bootstrap-Vue components
  ([#1072](https://github.com/bootstrap-vue/bootstrap-vue/issues/1072))
  ([7809fb2](https://github.com/bootstrap-vue/bootstrap-vue/commit/7809fb245331b01277d8464b4f35f7d0cde3e896))
- **docs:** starter examples ([#1061](https://github.com/bootstrap-vue/bootstrap-vue/issues/1061))
  ([dfc615f](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfc615f31ec33a1d3937c3277993edeec815d100))
- **docs:** Tooltip component documentation update
  ([c6b04a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6b04a66004d8c0b56435f8fa2864afb93fcb1bb))
- **docs:** Update tooltip directive example
  ([72a37b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/72a37b3bbd041ad87dec21f97b9d1a019609b106))
- **docs:** Updated b-img examples
  ([3ec187a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ec187a55001fee00d77f1eafe552c824b67f4c3))
- **docs:** Updated popover directive examples
  ([3adbcb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/3adbcb57a2dcfb30404a2451d7a6464a293babe0))
- **dom util:** new reflow, getBoundingClientRect, eventOn, eventOff methods
  ([#1052](https://github.com/bootstrap-vue/bootstrap-vue/issues/1052))
  ([346112d](https://github.com/bootstrap-vue/bootstrap-vue/commit/346112d5ac1d0a796ee034904a4d8f29862c1350)),
  closes [#1051](https://github.com/bootstrap-vue/bootstrap-vue/issues/1051)
- **dom utils:** Add getById method
  ([d73ff01](https://github.com/bootstrap-vue/bootstrap-vue/commit/d73ff01fb4be0544ede1fce52dcbd8fd31b5ce90))
- **dom utils:** Add offset and position methods
  ([baf15ca](https://github.com/bootstrap-vue/bootstrap-vue/commit/baf15caaefd9e5f55df8e33f85b7bfde2810073d))
- **dropdown:** Add auto ID generation
  ([#888](https://github.com/bootstrap-vue/bootstrap-vue/issues/888))
  ([25a20f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/25a20f2949a620bc7d2a062846a6d579eff8171b))
- **dropdowns:** Add hide() and show() methods
  ([#1012](https://github.com/bootstrap-vue/bootstrap-vue/issues/1012))
  ([a2a9bc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2a9bc4cec1ece3ae768dce3f94421186b0115c1)),
  closes [#1011](https://github.com/bootstrap-vue/bootstrap-vue/issues/1011)
- **embed:** New component b-embed for responsive video embeds
  ([#985](https://github.com/bootstrap-vue/bootstrap-vue/issues/985))
  ([e29c429](https://github.com/bootstrap-vue/bootstrap-vue/commit/e29c42975e03acd978c17add4cedc52cd779bbbf))
- **form-file:** Add focus styling for custom-file input
  ([#1033](https://github.com/bootstrap-vue/bootstrap-vue/issues/1033))
  ([72ffba9](https://github.com/bootstrap-vue/bootstrap-vue/commit/72ffba9695f568a97694e52a485607b74e4738cc))
- **form-file:** Propagate `capture` attribute to file input
  ([d7e4f8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7e4f8aa04882af9ed48ffe8e8b992f1b356e4e0))
- **forms:** Auto ID generation client side if no id prop provided
  ([#882](https://github.com/bootstrap-vue/bootstrap-vue/issues/882))
  ([da39b86](https://github.com/bootstrap-vue/bootstrap-vue/commit/da39b86c1c6988e62d7b0cf7276b4d217c5e3378))
- **forms:** New handling of form-select, form-radios and form-checkboxes
  ([#994](https://github.com/bootstrap-vue/bootstrap-vue/issues/994))
  ([0a50398](https://github.com/bootstrap-vue/bootstrap-vue/commit/0a50398cd03e9b016ea1c87a82a79268f8e5945a)),
  closes [#1038](https://github.com/bootstrap-vue/bootstrap-vue/issues/1038)
  [#995](https://github.com/bootstrap-vue/bootstrap-vue/issues/995)
  [#999](https://github.com/bootstrap-vue/bootstrap-vue/issues/999)
  [#1000](https://github.com/bootstrap-vue/bootstrap-vue/issues/1000)
  [#1004](https://github.com/bootstrap-vue/bootstrap-vue/issues/1004)
  [#1003](https://github.com/bootstrap-vue/bootstrap-vue/issues/1003)
  [#991](https://github.com/bootstrap-vue/bootstrap-vue/issues/991)
  [#1006](https://github.com/bootstrap-vue/bootstrap-vue/issues/1006)
  [#1005](https://github.com/bootstrap-vue/bootstrap-vue/issues/1005)
  [#1012](https://github.com/bootstrap-vue/bootstrap-vue/issues/1012)
  [#1011](https://github.com/bootstrap-vue/bootstrap-vue/issues/1011)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#1021](https://github.com/bootstrap-vue/bootstrap-vue/issues/1021)
  [#1016](https://github.com/bootstrap-vue/bootstrap-vue/issues/1016)
  [#1018](https://github.com/bootstrap-vue/bootstrap-vue/issues/1018)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#940](https://github.com/bootstrap-vue/bootstrap-vue/issues/940)
  [#1024](https://github.com/bootstrap-vue/bootstrap-vue/issues/1024)
  [#1033](https://github.com/bootstrap-vue/bootstrap-vue/issues/1033)
  [#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025)
  [#1037](https://github.com/bootstrap-vue/bootstrap-vue/issues/1037)
  [#1040](https://github.com/bootstrap-vue/bootstrap-vue/issues/1040)
  [#995](https://github.com/bootstrap-vue/bootstrap-vue/issues/995)
  [#999](https://github.com/bootstrap-vue/bootstrap-vue/issues/999)
  [#1000](https://github.com/bootstrap-vue/bootstrap-vue/issues/1000)
  [#1004](https://github.com/bootstrap-vue/bootstrap-vue/issues/1004)
  [#1003](https://github.com/bootstrap-vue/bootstrap-vue/issues/1003)
  [#991](https://github.com/bootstrap-vue/bootstrap-vue/issues/991)
  [#1006](https://github.com/bootstrap-vue/bootstrap-vue/issues/1006)
  [#1005](https://github.com/bootstrap-vue/bootstrap-vue/issues/1005)
  [#1012](https://github.com/bootstrap-vue/bootstrap-vue/issues/1012)
  [#1011](https://github.com/bootstrap-vue/bootstrap-vue/issues/1011)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#1021](https://github.com/bootstrap-vue/bootstrap-vue/issues/1021)
  [#1016](https://github.com/bootstrap-vue/bootstrap-vue/issues/1016)
  [#1018](https://github.com/bootstrap-vue/bootstrap-vue/issues/1018)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#940](https://github.com/bootstrap-vue/bootstrap-vue/issues/940)
  [#1024](https://github.com/bootstrap-vue/bootstrap-vue/issues/1024)
  [#1033](https://github.com/bootstrap-vue/bootstrap-vue/issues/1033)
  [#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025)
  [#1037](https://github.com/bootstrap-vue/bootstrap-vue/issues/1037)
  [#1039](https://github.com/bootstrap-vue/bootstrap-vue/issues/1039)
  [#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025)
- **img:** Add 'block' prop to set display mode to block
  ([6be7390](https://github.com/bootstrap-vue/bootstrap-vue/commit/6be73904302b89d65d1b00dbd7134644fe9aa9df))
- **input-group:** Add prop tag to change root element type
  ([800add6](https://github.com/bootstrap-vue/bootstrap-vue/commit/800add6133c9bb937775adfd5fd35f3b85fb74eb))
- **jumbotron:** Add support for variants
  ([#973](https://github.com/bootstrap-vue/bootstrap-vue/issues/973))
  ([bd9bb7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd9bb7cad48c2ba0e99f73808c193e89ec0ebb6e))
- **jumbotron:** Convert to functional component
  ([#932](https://github.com/bootstrap-vue/bootstrap-vue/issues/932))
  ([5f2df53](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f2df53df71a4ba7a831fe87730b8223aef3c223)),
  closes [#935](https://github.com/bootstrap-vue/bootstrap-vue/issues/935)
  [#934](https://github.com/bootstrap-vue/bootstrap-vue/issues/934)
  [#929](https://github.com/bootstrap-vue/bootstrap-vue/issues/929)
- **layout:** alignment utilities 🛠
  ([#941](https://github.com/bootstrap-vue/bootstrap-vue/issues/941))
  ([3435ac5](https://github.com/bootstrap-vue/bootstrap-vue/commit/3435ac55cc8df9fed616a9b7a88f25707f8a1aed))
- **list-group:** new list-group functional components
  ([#861](https://github.com/bootstrap-vue/bootstrap-vue/issues/861))
  ([c516d89](https://github.com/bootstrap-vue/bootstrap-vue/commit/c516d89ed6014836708941baa26b2c645660c0dd))
- **media:** new functional media components
  ([#872](https://github.com/bootstrap-vue/bootstrap-vue/issues/872))
  ([91ff681](https://github.com/bootstrap-vue/bootstrap-vue/commit/91ff681b8ef6b22df6fc8133c83b23ef339f36cb))
- **modal:** Add lazy loaded modal support
  ([#1046](https://github.com/bootstrap-vue/bootstrap-vue/issues/1046))
  ([7afcf81](https://github.com/bootstrap-vue/bootstrap-vue/commit/7afcf812e2943803127c3ece379ab4a892f40f24))
- **modal:** Add props to change the variant of the default modal buttons
  ([#1004](https://github.com/bootstrap-vue/bootstrap-vue/issues/1004))
  ([36acf4e](https://github.com/bootstrap-vue/bootstrap-vue/commit/36acf4e64d85046218cad8480cb22f1d1996d7df))
- **modal:** Improve modal transitions, padding adjustments, and aditional features
  ([#1024](https://github.com/bootstrap-vue/bootstrap-vue/issues/1024))
  ([dd5ddb0](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd5ddb026a123de8f3dee48656950d27a228c607))
- **nav:** new functional nav components
  ([#864](https://github.com/bootstrap-vue/bootstrap-vue/issues/864))
  ([ecec23d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecec23dda3f72dc5e311eb968003ddd731f591fe))
- **popover:** Add ability to disable fade animation in component version
  ([7161b5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/7161b5fa1ab437812ba68c08d4c4b5018a1d56f1))
- **popover:** Add deactivated hook to component to hide popover
  ([4a70215](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a702157cfb9535fb14a6ad1e439c713f8dacea6))
- **popover:** import fix
  ([b24764f](https://github.com/bootstrap-vue/bootstrap-vue/commit/b24764f65ad4ecf34e2b0ac194c37845e1b65395))
- **popover+tooltip:** Add hide event listener on $root
  ([#1003](https://github.com/bootstrap-vue/bootstrap-vue/issues/1003))
  ([6b12629](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b12629da279e7f85b4314b7f663b49cc496b5ff))
- **progress:** Support for multiple progress bars
  ([#889](https://github.com/bootstrap-vue/bootstrap-vue/issues/889))
  ([76c613c](https://github.com/bootstrap-vue/bootstrap-vue/commit/76c613cbdf4d2524b81b8e11e42271feb84f39c9))
- **readme:** add package quality badge
  ([#907](https://github.com/bootstrap-vue/bootstrap-vue/issues/907))
  ([6bd9f52](https://github.com/bootstrap-vue/bootstrap-vue/commit/6bd9f52dda7d22936e68fe25e186f3f1f7117a0c))
- **table:** Allow fields to be an array of objects
  ([#1075](https://github.com/bootstrap-vue/bootstrap-vue/issues/1075))
  ([e2f90ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/e2f90ff47619ef2e79128fd4f53bd7b30eb26768))
- **table:** easier usage
  ([019f8fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/019f8fad1eb129a85e512406f433640a215c741a))
- **table:** Include native event object with row-_ and head-_ events
  ([#892](https://github.com/bootstrap-vue/bootstrap-vue/issues/892))
  ([92d2794](https://github.com/bootstrap-vue/bootstrap-vue/commit/92d2794b2dfc67bd575eaa52b5d6fe97f6fff9fb))
- **table:** Refactor field formatter support + optimized sort-compare handling
  ([#991](https://github.com/bootstrap-vue/bootstrap-vue/issues/991))
  ([b66f994](https://github.com/bootstrap-vue/bootstrap-vue/commit/b66f994fcde9376033b55110fa395a948e4d8982))
- **table:** Scoped slots for fixed top/bottom rows
  ([#908](https://github.com/bootstrap-vue/bootstrap-vue/issues/908))
  ([3c761e2](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c761e209dc85b69b9fa6d9ed674b74032a15c1d))
- **table:** use computedFields for easier usage
  ([b9980f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9980f0c136a012ff0b2c6892398c733bca7e95a))
- **tooltip:** Add ability to disable fade animation in component version
  ([36c428a](https://github.com/bootstrap-vue/bootstrap-vue/commit/36c428aa962d970ad4cfc60cabd1152b5b68c600))
- **tooltip popover:** Better DOM change observation in component versions
  ([f723807](https://github.com/bootstrap-vue/bootstrap-vue/commit/f723807abc75d34501073e7dd8442db1b7ac1823))
- **tooltip+popover:** Create mixin for common props and methods
  ([#1021](https://github.com/bootstrap-vue/bootstrap-vue/issues/1021))
  ([edc7b20](https://github.com/bootstrap-vue/bootstrap-vue/commit/edc7b207a1ec6701aee39cf1ea2d916642cfe581))
- dom utility methods ([#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013))
  ([7ed199d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ed199d703e8664ff192345ba9d03ebcb7c3176e))
- Use dom utils ([#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017))
  ([5ca9fe3](https://github.com/bootstrap-vue/bootstrap-vue/commit/5ca9fe3ec58033725ddf766060fccb9cfd50f848))
- **tooltip:** Add deactivated hook to component
  ([ae605d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae605d39f8ab10f82ed1d607c2d946baafb4c79f))
- **tooltip+popover:** Add container prop to component versions
  ([#983](https://github.com/bootstrap-vue/bootstrap-vue/issues/983))
  ([860cb3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/860cb3cfd9c74f88b69ae3f717cb93218989a186))
- **tooltip+popover:** Allow element and component reference for target
  ([#980](https://github.com/bootstrap-vue/bootstrap-vue/issues/980))
  ([8785066](https://github.com/bootstrap-vue/bootstrap-vue/commit/8785066b16d2615c2a3d539b7221be802435cb10))
- **tooltips+popovers:** Add special blur "exit" trigger
  ([#974](https://github.com/bootstrap-vue/bootstrap-vue/issues/974))
  ([785b7a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/785b7a6cb3e23f66309abc0a371226944cec6681))
- **tooltips+popovers:** Automatically hide when trigger element is no longer visible
  ([#978](https://github.com/bootstrap-vue/bootstrap-vue/issues/978))
  ([09eaaa2](https://github.com/bootstrap-vue/bootstrap-vue/commit/09eaaa2ec9dcf03aba6cba915c4b3bb1353f41f0))
- New popper.js based tooltip/popover directives and components
  ([#923](https://github.com/bootstrap-vue/bootstrap-vue/issues/923))
  ([33c4cab](https://github.com/bootstrap-vue/bootstrap-vue/commit/33c4cab68984ca934e174e53f1f85995d003641e))
- **addEventListenerOnce:** add to utils
  ([0869ffd](https://github.com/bootstrap-vue/bootstrap-vue/commit/0869ffdc9ed80ad37645c0f550ca19e26c9817b0))
- **addEventListenerOnce:** New utility function
  ([6b4efdf](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b4efdfb559988fc278e107d65a8bb6a4fc6381f))
- **alert:** Hide dismiss button for auto-dismissing alerts
  ([#791](https://github.com/bootstrap-vue/bootstrap-vue/issues/791))
  ([080bb20](https://github.com/bootstrap-vue/bootstrap-vue/commit/080bb204318ad59fea18e56b1a18ce1cd5dc3d0a))
- **badge:** functional component
  ([#820](https://github.com/bootstrap-vue/bootstrap-vue/issues/820))
  ([8c172c1](https://github.com/bootstrap-vue/bootstrap-vue/commit/8c172c18a298b7e269526085babf17b408169db9))
- **btn-group:** functional component for button-group
  ([#822](https://github.com/bootstrap-vue/bootstrap-vue/issues/822))
  ([6891e9f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6891e9f7c3e90796c65205636cca5b280f466e5b))
- **button:** Add pressed prop to place button in active state
  ([#715](https://github.com/bootstrap-vue/bootstrap-vue/issues/715))
  ([61a104f](https://github.com/bootstrap-vue/bootstrap-vue/commit/61a104fab0d835acfcca7fce2f20b240278fcc12))
- **button:** refactor toggle button focus handler
  ([#730](https://github.com/bootstrap-vue/bootstrap-vue/issues/730))
  ([3ab3d89](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ab3d89b23b39ff29be7736004f134db47dbe993))
- **button:** set light as default variant
  ([2a72576](https://github.com/bootstrap-vue/bootstrap-vue/commit/2a725767e6828a10c58dae43392e9f3c08f00925))
- **card:** add card-body functional component & card-img fixes
  ([#843](https://github.com/bootstrap-vue/bootstrap-vue/issues/843))
  ([f88ab23](https://github.com/bootstrap-vue/bootstrap-vue/commit/f88ab23edcf65a761be3f07c553927eab92ae162))
- **card:** change card-block to card-body
  ([30d35a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/30d35a74cff8c113e41685e130d2e58fdba21c7b))
- **card:** functional components for card
  ([#827](https://github.com/bootstrap-vue/bootstrap-vue/issues/827))
  ([2089252](https://github.com/bootstrap-vue/bootstrap-vue/commit/2089252ba3b7d3a8589f772c4b6273e389608b64))
- **carousel:** Add v-model support (issue
  [#743](https://github.com/bootstrap-vue/bootstrap-vue/issues/743))
  ([#744](https://github.com/bootstrap-vue/bootstrap-vue/issues/744))
  ([028eb5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/028eb5fddf4c31406416034190213a462819c391))
- **carousel:** Transition event with setTimeout fallback
  ([8e6fc42](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e6fc42f0829c5ca0d17f207270f8984ee8cbb05))
- **carousel:** Use transitionend event instead of setTimeout
  ([192dfb8](https://github.com/bootstrap-vue/bootstrap-vue/commit/192dfb824ca806ee398cebdcc0a93a109b33d93a))
- **checkbox:** Add indeterminate state prop
  ([#720](https://github.com/bootstrap-vue/bootstrap-vue/issues/720))
  ([2271e7a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2271e7ad57206289eb6cd7e29289605a4a2e52fb))
- **collapse:** apply bootstrap classes during transition stages (issue
  [#565](https://github.com/bootstrap-vue/bootstrap-vue/issues/565))
  ([#707](https://github.com/bootstrap-vue/bootstrap-vue/issues/707))
  ([947d253](https://github.com/bootstrap-vue/bootstrap-vue/commit/947d253dad7f08a677aba095463e988624e60eee))
- **collapse:** Close navbar collapse when clicked in nav/navbar (issue
  [#712](https://github.com/bootstrap-vue/bootstrap-vue/issues/712))
  ([#714](https://github.com/bootstrap-vue/bootstrap-vue/issues/714))
  ([f104dc0](https://github.com/bootstrap-vue/bootstrap-vue/commit/f104dc04c370889db20aa7a11d0295eb5a2e05f2))
- **docs:** changelog page
  ([b2482cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b2482cb909f4e5723a3f7f8a6495309d544e01ce))
- **docs:** live demo ([#602](https://github.com/bootstrap-vue/bootstrap-vue/issues/602))
  ([843057e](https://github.com/bootstrap-vue/bootstrap-vue/commit/843057e47f71e62ec970b57c1eef4252640e13f6))
- **docs:** Native event capturing docs
  ([#605](https://github.com/bootstrap-vue/bootstrap-vue/issues/605))
  ([c2c200b](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2c200bed13966f53e71db799266ebe4abfedd15))
- **docs:** prepare for 1.0.0-beta
  ([8e46552](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e465526ae44c4ae3326a9c5526534285fdccb3d))
- **dropdowns:** functional dropdown sub-components and testing
  ([#848](https://github.com/bootstrap-vue/bootstrap-vue/issues/848))
  ([2bd562b](https://github.com/bootstrap-vue/bootstrap-vue/commit/2bd562bb0e3322522366f1d28d8e38139b49339b))
- **dropdowns:** Various optimizations for dropdown components
  ([#627](https://github.com/bootstrap-vue/bootstrap-vue/issues/627))
  ([56d29b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/56d29b0aa4270e6a9ccbe86278b7edd413970203))
- **Event:** standard evt obj emulates native Event
  ([#726](https://github.com/bootstrap-vue/bootstrap-vue/issues/726))
  ([919344b](https://github.com/bootstrap-vue/bootstrap-vue/commit/919344be16de8935472efdc69ee2b69455cec38f))
- **form:** Swith to functional component
  ([#865](https://github.com/bootstrap-vue/bootstrap-vue/issues/865))
  ([c9f054d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9f054dcd87fce9203ee09cec851da382e5250d8))
- **form controls:** Add required attribute and related ARIA support
  ([#613](https://github.com/bootstrap-vue/bootstrap-vue/issues/613))
  ([3db70a4](https://github.com/bootstrap-vue/bootstrap-vue/commit/3db70a48523fed5d992cb9fbc9d9ae2c30418a18))
- **form controls:** Optimize props
  ([#604](https://github.com/bootstrap-vue/bootstrap-vue/issues/604))
  ([35a5db6](https://github.com/bootstrap-vue/bootstrap-vue/commit/35a5db6e63f5e4bf9abac089c5bf680e7224959e))
- **form-checkbox:** Support button style checkbox
  ([#729](https://github.com/bootstrap-vue/bootstrap-vue/issues/729))
  ([740d7cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/740d7cb9f9b166ae8359884c9adda26a22d66878))
- **form-fieldset:** Add alias of b-form-group
  ([eebe36d](https://github.com/bootstrap-vue/bootstrap-vue/commit/eebe36de67fa9ef4fb6ffbc3065ffe085a198fe4))
- **form-fieldset:** label, description, and feedback slots, deprecate label-size
  ([#598](https://github.com/bootstrap-vue/bootstrap-vue/issues/598))
  ([e253dae](https://github.com/bootstrap-vue/bootstrap-vue/commit/e253daeb00d6d6d1fee1a7ae5bd9aec7de3b12f7))
- **form-input:** Add autocomplete prop
  ([#750](https://github.com/bootstrap-vue/bootstrap-vue/issues/750))
  ([d686787](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6867878a0130e4ce24d505a0b9820a328f918db))
- **form-input:** Pass input element to formatter (issue
  [#772](https://github.com/bootstrap-vue/bootstrap-vue/issues/772))
  ([#773](https://github.com/bootstrap-vue/bootstrap-vue/issues/773))
  ([da77f15](https://github.com/bootstrap-vue/bootstrap-vue/commit/da77f1569372a58c1b5851a4af38be2a2fb06f80))
- **form-input:** support aria-invalid attribute
  ([#610](https://github.com/bootstrap-vue/bootstrap-vue/issues/610))
  ([d676d8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/d676d8fc9424804b979d8d891afdf5242d472088))
- **form-radio:** Add support for aria-invalid
  ([#612](https://github.com/bootstrap-vue/bootstrap-vue/issues/612))
  ([69e449f](https://github.com/bootstrap-vue/bootstrap-vue/commit/69e449fe3990240d669772d9da185fbc7c8d2d20))
- **form-radio:** ARIA - Add IDs to individual radios
  ([#663](https://github.com/bootstrap-vue/bootstrap-vue/issues/663))
  ([1de785e](https://github.com/bootstrap-vue/bootstrap-vue/commit/1de785e4e25bab8fa94b02fd1215099a9d7b1a0e))
- **form-radio:** Support button style radios
  ([#728](https://github.com/bootstrap-vue/bootstrap-vue/issues/728))
  ([c7c150f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7c150f3814182563fc703edad31a7207097ada2))
- **form-row:** New functional component
  ([#844](https://github.com/bootstrap-vue/bootstrap-vue/issues/844))
  ([1e0f313](https://github.com/bootstrap-vue/bootstrap-vue/commit/1e0f313069e4456b3a0f5caa3116eaa277c966c8))
- **form-select:** Add aria-invalid support
  ([#611](https://github.com/bootstrap-vue/bootstrap-vue/issues/611))
  ([1d20f8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d20f8ae54ba0d58585570e54fdf18a9729b6b4d))
- **form-select:** add key for v-for
  ([299a2ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/299a2eae3993d0129fae5ceab5de486f8460fa1b))
- **form-select:** Add multiple select support (issue
  [#619](https://github.com/bootstrap-vue/bootstrap-vue/issues/619))
  ([#731](https://github.com/bootstrap-vue/bootstrap-vue/issues/731))
  ([19bf2f5](https://github.com/bootstrap-vue/bootstrap-vue/commit/19bf2f54d4ff7693429e51f4c7c61973eb24cc10))
- **form-select:** Allow selectSize to be set when not in multiple mode (Issue
  [#761](https://github.com/bootstrap-vue/bootstrap-vue/issues/761))
  ([#762](https://github.com/bootstrap-vue/bootstrap-vue/issues/762))
  ([6f04090](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f040904f51baf557a8b6265c22c844464773298))
- **form-text:** New functional component
  ([#846](https://github.com/bootstrap-vue/bootstrap-vue/issues/846))
  ([2ed7470](https://github.com/bootstrap-vue/bootstrap-vue/commit/2ed74707afeef9c1b7fc665aa2509db18c8a3f63))
- **listenonroot:** Use a constant for private property name
  ([#700](https://github.com/bootstrap-vue/bootstrap-vue/issues/700))
  ([26c8a3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/26c8a3ecde2582bc2c6cba742971d7957d16c2b9))
- **mixin:** Automate event registration & removal on root vm
  ([#581](https://github.com/bootstrap-vue/bootstrap-vue/issues/581))
  ([be5f834](https://github.com/bootstrap-vue/bootstrap-vue/commit/be5f8341b6e45863b427d6d2ab8cbdfb0d350e14))
- **modal:** Make enforceFocus configurable
  ([#706](https://github.com/bootstrap-vue/bootstrap-vue/issues/706))
  ([f1ab80b](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1ab80b42d7d02ded2c7aba310755d186a0ce3a3))
- **navbar:** change navbar-toggelable to navbar-expand-\*
  ([1fab033](https://github.com/bootstrap-vue/bootstrap-vue/commit/1fab0338250199a3229c80a4ae24459d49677c1d))
- **navbar-brand:** New component <b-navbar-brand>
  ([#710](https://github.com/bootstrap-vue/bootstrap-vue/issues/710))
  ([721292c](https://github.com/bootstrap-vue/bootstrap-vue/commit/721292cad0a107b1884a5186a102e6d3d772fb90))
- **pagination-nav:** New navigation pagination component
  ([#816](https://github.com/bootstrap-vue/bootstrap-vue/issues/816))
  ([3a4272c](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a4272cc04a6b0f2291d10d09d6877b3ba3bfc30))
- **progress:** Add height prop ([#837](https://github.com/bootstrap-vue/bootstrap-vue/issues/837))
  ([8a52b93](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a52b937e8f94d1c37376c3c14ddba7bb6ae8c9c))
- link, breadcrumb, & button functional components
  ([#830](https://github.com/bootstrap-vue/bootstrap-vue/issues/830))
  ([cdbef2d](https://github.com/bootstrap-vue/bootstrap-vue/commit/cdbef2d720282144fb87fa53c1d4aec0b0e4bf1b))
- **pagination:** Add alignment prop
  ([#745](https://github.com/bootstrap-vue/bootstrap-vue/issues/745))
  ([a8e83a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8e83a7486d4d776e10c11f4e55798ff5de35ea5))
- **readme:** add david dep badge
  ([#724](https://github.com/bootstrap-vue/bootstrap-vue/issues/724))
  ([435a857](https://github.com/bootstrap-vue/bootstrap-vue/commit/435a85736563dc740dcc018ced6ff82db8c3797f))
- **table:** add field data formatter prop
  ([#739](https://github.com/bootstrap-vue/bootstrap-vue/issues/739))
  ([9da94a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/9da94a6a72c2527c01624a3d459a0c38520a8b96))
- **table:** Add row-dblclicked event
  ([#780](https://github.com/bootstrap-vue/bootstrap-vue/issues/780))
  ([1aaf915](https://github.com/bootstrap-vue/bootstrap-vue/commit/1aaf9150480a17a35884f639a037911b2624f111))
- **table:** Add syncable sort-by and sort-desc props
  ([#742](https://github.com/bootstrap-vue/bootstrap-vue/issues/742))
  ([c8ad5a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/c8ad5a3aec719701076a5fc99c055fa7153c0ed6))
- **table:** Emit event when local filtering changes number of result items - issue
  [#650](https://github.com/bootstrap-vue/bootstrap-vue/issues/650)
  ([#652](https://github.com/bootstrap-vue/bootstrap-vue/issues/652))
  ([1b2a36a](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b2a36ab4e29fb699f99d0e6237dbf93227a7bfb))
- **toggle directives:** allow simple elements to use directive
  ([#651](https://github.com/bootstrap-vue/bootstrap-vue/issues/651))
  ([3361911](https://github.com/bootstrap-vue/bootstrap-vue/commit/3361911a5d3cb7bf427d9f010359210a23e32168))
- **utils:** transpiler friendly polyfills and methods
  ([#658](https://github.com/bootstrap-vue/bootstrap-vue/issues/658))
  ([2ee9ed6](https://github.com/bootstrap-vue/bootstrap-vue/commit/2ee9ed6815cd6d615a5654c7f1d207cdb8f8a2ee))
- **utils:** wrap-up as ES6 module
  ([#656](https://github.com/bootstrap-vue/bootstrap-vue/issues/656))
  ([b5f7cfc](https://github.com/bootstrap-vue/bootstrap-vue/commit/b5f7cfc9defaf66ff950bd578cb01ee3ea1f395b))

### Bug Fixes

- **b-alert:** handle case where dismiss countdown changes to a boolean value (closes
  [#3346](https://github.com/bootstrap-vue/bootstrap-vue/issues/3346))
  ([#3347](https://github.com/bootstrap-vue/bootstrap-vue/issues/3347))
  ([14ad833](https://github.com/bootstrap-vue/bootstrap-vue/commit/14ad8330bde33979919254361ed3a8a2cbda6f6f))
- **b-avatar:** badge `z-index` handling
  ([#5975](https://github.com/bootstrap-vue/bootstrap-vue/issues/5975))
  ([ecb33bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecb33bdb510832096bc5a5196a11c97388bf6411))
- **b-avatar:** image fit and scale (closes
  [#5610](https://github.com/bootstrap-vue/bootstrap-vue/issues/5610),
  [#5655](https://github.com/bootstrap-vue/bootstrap-vue/issues/5655))
  ([#5675](https://github.com/bootstrap-vue/bootstrap-vue/issues/5675))
  ([9812248](https://github.com/bootstrap-vue/bootstrap-vue/commit/9812248ea686e339f32604c0020a1714bb228d75))
- **b-avatar:** prevent avatar from being squished
  ([#5963](https://github.com/bootstrap-vue/bootstrap-vue/issues/5963))
  ([b3946ed](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3946ed7a7b327fb7c66b44caaf122460fc24005)),
  closes [#5962](https://github.com/bootstrap-vue/bootstrap-vue/issues/5962)
- **b-badge:** attribute inheritance
  ([#6217](https://github.com/bootstrap-vue/bootstrap-vue/issues/6217))
  ([2d31f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/2d31f31909c002faa2a9d8bd8620115ddf8ce603))
- **b-button-toolbar:** allow focus to leave toolbar by keyboard
  ([#5737](https://github.com/bootstrap-vue/bootstrap-vue/issues/5737))
  ([f54e427](https://github.com/bootstrap-vue/bootstrap-vue/commit/f54e4275881947cfb504235aa9330c03444e08bb))
- **b-calendar:** month formatting for ceratin dates
  ([#5911](https://github.com/bootstrap-vue/bootstrap-vue/issues/5911))
  ([7de1844](https://github.com/bootstrap-vue/bootstrap-vue/commit/7de1844c6d5c0014d25c930527a7fc49a2b0cc25))
- **b-card:** properly support header/footer with body image overlay
  ([#5872](https://github.com/bootstrap-vue/bootstrap-vue/issues/5872))
  ([bd8319d](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd8319da8c6166f9fe3e64d9a3ac5c490c6b2f48))
- **b-carousel:** fix glitching when switching slides fast (closes
  [#5810](https://github.com/bootstrap-vue/bootstrap-vue/issues/5810))
  ([#5845](https://github.com/bootstrap-vue/bootstrap-vue/issues/5845))
  ([761bc93](https://github.com/bootstrap-vue/bootstrap-vue/commit/761bc9381ba24aed751726c8213651e2014aa746))
- **b-dropdown:** click handling on close (closes
  [#5982](https://github.com/bootstrap-vue/bootstrap-vue/issues/5982))
  ([#6009](https://github.com/bootstrap-vue/bootstrap-vue/issues/6009))
  ([cf7a1cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf7a1cb017e2263939a64e300abbbbac35c121d4))
- **b-dropdown:** decrease delay when hiding inside a navbar on no-touch devices (closes
  [#6306](https://github.com/bootstrap-vue/bootstrap-vue/issues/6306))
  ([#6367](https://github.com/bootstrap-vue/bootstrap-vue/issues/6367))
  ([7d72605](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d726056eb40a148afbafd0710035cb306582bb6))
- **b-dropdown:** only apply `heading` role to header when not a `header` tag
  ([#6274](https://github.com/bootstrap-vue/bootstrap-vue/issues/6274))
  ([bd67da0](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd67da0c40744e6b245a4e514e2319ca7bfafe2d))
- **b-dropdown:** root events ([#6198](https://github.com/bootstrap-vue/bootstrap-vue/issues/6198))
  ([6dcd233](https://github.com/bootstrap-vue/bootstrap-vue/commit/6dcd23334f2870220ed5c4d8b30bd556e57c03d5))
- **b-dropdown:** Sets correct `aria-haspopup` attribute for the toggle button
  ([#6865](https://github.com/bootstrap-vue/bootstrap-vue/issues/6865))
  ([d92c2f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/d92c2f1237b44102f0bf6eadd26d97423b9f8c2b))
- **b-form-checkbox:** `change` event value when in multiple mode
  ([#5716](https://github.com/bootstrap-vue/bootstrap-vue/issues/5716))
  ([5150b94](https://github.com/bootstrap-vue/bootstrap-vue/commit/5150b943f25ff6b2f331aaef64321973bd60dd0e))
- **b-form-checkbox-group:** only emit `input` when value loosely changes
  ([#5432](https://github.com/bootstrap-vue/bootstrap-vue/issues/5432))
  ([e76d408](https://github.com/bootstrap-vue/bootstrap-vue/commit/e76d40874bd2a42126162101e94bb18e9042840b))
- **b-form-checkbox/b-form-radio:** `chnage` event timing
  ([#6008](https://github.com/bootstrap-vue/bootstrap-vue/issues/6008))
  ([37ec7e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/37ec7e9991b66af51ff81420da8eb88928615f9d))
- **b-form-checkbox/b-form-radio:** remove `autocomplete="off"` attribute
  ([#5764](https://github.com/bootstrap-vue/bootstrap-vue/issues/5764))
  ([443aaf1](https://github.com/bootstrap-vue/bootstrap-vue/commit/443aaf1afc38dc029e0b142c11a39d360bbc98d2))
- **b-form-datepicker:** `valueAsDate` prop handling
  ([#6159](https://github.com/bootstrap-vue/bootstrap-vue/issues/6159))
  ([5cb8e0c](https://github.com/bootstrap-vue/bootstrap-vue/commit/5cb8e0c474ab750868379b4293d0eb5d52f5dd85))
- **b-form-datepicker/b-form-timepicker:** control size
  ([#6249](https://github.com/bootstrap-vue/bootstrap-vue/issues/6249))
  ([f2ffbeb](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2ffbeb85a71f0e3ac5c6ea55622771357c703e1))
- **b-form-datepicker/b-form-timepicker:** label styles when in `button-only` mode (closes
  [#6172](https://github.com/bootstrap-vue/bootstrap-vue/issues/6172))
  ([#6186](https://github.com/bootstrap-vue/bootstrap-vue/issues/6186))
  ([e8842ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8842bae98e83d16f3429b37f219ae61890a5c38))
- **b-form-datepicker/b-form-timepicker/b-nav-item-dropdown:** dropdown positioning handling (closes
  [#5700](https://github.com/bootstrap-vue/bootstrap-vue/issues/5700),
  [#5630](https://github.com/bootstrap-vue/bootstrap-vue/issues/5630))
  ([#5765](https://github.com/bootstrap-vue/bootstrap-vue/issues/5765))
  ([7ec2205](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ec2205a96e0d14772f1ed6c047a9808a32fbf82))
- **b-form-file:** drop handling for huge amounts of files (closes
  [#5615](https://github.com/bootstrap-vue/bootstrap-vue/issues/5615))
  ([#5685](https://github.com/bootstrap-vue/bootstrap-vue/issues/5685))
  ([d54b240](https://github.com/bootstrap-vue/bootstrap-vue/commit/d54b240adeb6eadfe8736f4926384a5c4d351bde))
- **b-form-group:** accessibility when `label-for` prop not set
  ([#6006](https://github.com/bootstrap-vue/bootstrap-vue/issues/6006))
  ([16f777b](https://github.com/bootstrap-vue/bootstrap-vue/commit/16f777b14bdcf9ebb6fae0325d355c7f5272bd98))
- **b-form-group:** content element ID handling (closes
  [#5930](https://github.com/bootstrap-vue/bootstrap-vue/issues/5930))
  ([#5933](https://github.com/bootstrap-vue/bootstrap-vue/issues/5933))
  ([fecd558](https://github.com/bootstrap-vue/bootstrap-vue/commit/fecd55814c4f4553348d8016cdf0d449f22228f7))
- **b-form-group:** remove `role="alert"` from valid/invalid feedback (closes
  [#6300](https://github.com/bootstrap-vue/bootstrap-vue/issues/6300),
  [#6307](https://github.com/bootstrap-vue/bootstrap-vue/issues/6307))
  ([#6346](https://github.com/bootstrap-vue/bootstrap-vue/issues/6346))
  ([c0959c4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0959c4df2552929d7fa68e28fb700297df291f8))
- **b-form-input:** fix debounce when value does not change
  ([#5632](https://github.com/bootstrap-vue/bootstrap-vue/issues/5632))
  ([111ca65](https://github.com/bootstrap-vue/bootstrap-vue/commit/111ca65240ab6941e2173ca44806aa0a75691c95))
- **b-form-input:** modified value handling
  ([#6084](https://github.com/bootstrap-vue/bootstrap-vue/issues/6084))
  ([d6d8e3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6d8e3c0f309ca16ede0c874bb787ab2fed7b380))
- **b-form-input/b-form-textarea:** legacy browser support (closes
  [#6283](https://github.com/bootstrap-vue/bootstrap-vue/issues/6283))
  ([#6345](https://github.com/bootstrap-vue/bootstrap-vue/issues/6345))
  ([a79d98a](https://github.com/bootstrap-vue/bootstrap-vue/commit/a79d98a78f68ba3c15e626928f5e5208aba05d2f))
- **b-form-spinbutton:** button markup
  ([#6101](https://github.com/bootstrap-vue/bootstrap-vue/issues/6101))
  ([5082976](https://github.com/bootstrap-vue/bootstrap-vue/commit/5082976e90264cadd84a4c9dbf339ce90fe49456))
- **b-form-tags:** ensure same height with or without tags
  ([#5752](https://github.com/bootstrap-vue/bootstrap-vue/issues/5752))
  ([07102f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/07102f988cfe8e8290189e73f50790f70bbb4639))
- **b-form-tags:** required handling (closes
  [#6094](https://github.com/bootstrap-vue/bootstrap-vue/issues/6094))
  ([#6103](https://github.com/bootstrap-vue/bootstrap-vue/issues/6103))
  ([2dc6b9d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dc6b9d5bc5fcb3cf1febda7d9e5b03d1ee9a3d0))
- **b-form-tags:** unit test ([#5586](https://github.com/bootstrap-vue/bootstrap-vue/issues/5586))
  ([f4d509a](https://github.com/bootstrap-vue/bootstrap-vue/commit/f4d509af647eaf87e2b635d08ff9431b25150650))
- **b-form-textarea:** `setStyle()` util usage
  ([bf7a65f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf7a65f87caf0d725033c35ee85c1e32ced82adc))
- **b-icon:** local component lookup
  ([edb6ed6](https://github.com/bootstrap-vue/bootstrap-vue/commit/edb6ed66757299a81e5fd1cc1cb2b4fc20ce2b5e))
- **b-icon:** local component lookup
  ([#5939](https://github.com/bootstrap-vue/bootstrap-vue/issues/5939))
  ([4586b49](https://github.com/bootstrap-vue/bootstrap-vue/commit/4586b49d99e4239dbebe2518f57022d6e4e20224))
- **b-icon:** title render handling
  ([#6233](https://github.com/bootstrap-vue/bootstrap-vue/issues/6233))
  ([b025047](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0250477e6b4228f1f228c2776c8c211d8a57f00))
- **b-icon:** use `aria-label` attribute instead of `alt`
  ([#5581](https://github.com/bootstrap-vue/bootstrap-vue/issues/5581))
  ([72a1363](https://github.com/bootstrap-vue/bootstrap-vue/commit/72a13635b94aedfab1fb6800f2a297fa306f63ef))
- **b-img:** Allow empty `alt` prop (fixes
  [#5524](https://github.com/bootstrap-vue/bootstrap-vue/issues/5524))
  ([#5545](https://github.com/bootstrap-vue/bootstrap-vue/issues/5545))
  ([b22829d](https://github.com/bootstrap-vue/bootstrap-vue/commit/b22829d064b6e3820ef66168ec766a57520f31eb))
- **b-img-lazy:** `blank` placeholder for Firefox (closes
  [#6320](https://github.com/bootstrap-vue/bootstrap-vue/issues/6320))
  ([#6349](https://github.com/bootstrap-vue/bootstrap-vue/issues/6349))
  ([9b297c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b297c9415744ddb7bd3d50bbe5957859a61123e))
- **b-img-lazy:** fix blank-src not work error
  ([#6302](https://github.com/bootstrap-vue/bootstrap-vue/issues/6302))
  ([a6ace2f](https://github.com/bootstrap-vue/bootstrap-vue/commit/a6ace2f229680e13b0f91c17458461b8afda9f7b))
- **b-input-tags:** not respecting custom `$input-color` (closes
  [#6388](https://github.com/bootstrap-vue/bootstrap-vue/issues/6388))
  ([#6389](https://github.com/bootstrap-vue/bootstrap-vue/issues/6389))
  ([9f045d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f045d47b1eae4036910a1e397ed17b664e259c5))
- **b-link:** `href` handling inconsistencies to `<router-link>` (closes
  [#5820](https://github.com/bootstrap-vue/bootstrap-vue/issues/5820))
  ([#5876](https://github.com/bootstrap-vue/bootstrap-vue/issues/5876))
  ([daea0e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/daea0e5c638de9ec45d39af5aa1e9f8a9e455422))
- **b-link:** `href` handling with live router (closes
  [#5927](https://github.com/bootstrap-vue/bootstrap-vue/issues/5927))
  ([#5934](https://github.com/bootstrap-vue/bootstrap-vue/issues/5934))
  ([8a367b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a367b6296b0aa9700f67633fd60fb351e2f7373))
- **b-link:** remove default values from `vue-router` pass-down props (closes
  [#6373](https://github.com/bootstrap-vue/bootstrap-vue/issues/6373))
  ([#6374](https://github.com/bootstrap-vue/bootstrap-vue/issues/6374))
  ([0a14828](https://github.com/bootstrap-vue/bootstrap-vue/commit/0a14828961846b907cf8243e1a14954911f802cf))
- **b-modal:** solve body padding not being removed
  ([#5771](https://github.com/bootstrap-vue/bootstrap-vue/issues/5771))
  ([78d51f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/78d51f1e7146cbed756853003a93b991c9f0d8bc))
- **b-nav-item-dropdown:** `boundary` handling in `<b-navbar>` (closes
  [#5789](https://github.com/bootstrap-vue/bootstrap-vue/issues/5789))
  ([#5794](https://github.com/bootstrap-vue/bootstrap-vue/issues/5794))
  ([73383bf](https://github.com/bootstrap-vue/bootstrap-vue/commit/73383bfd935c097604bf5ad39a9cc2d18961ba87))
- **b-pagination:** don't set initial page count twice
  ([#6200](https://github.com/bootstrap-vue/bootstrap-vue/issues/6200))
  ([d7394e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7394e3426e5b06797caef070137ec47b25ef62a))
- **b-pagination:** properly calculate number of links with `hide-ellipsis` option (closes
  [#5514](https://github.com/bootstrap-vue/bootstrap-vue/issues/5514))
  ([#5678](https://github.com/bootstrap-vue/bootstrap-vue/issues/5678))
  ([98e17ca](https://github.com/bootstrap-vue/bootstrap-vue/commit/98e17ca85588b858f5d74e217c48fa82f11f487f))
- **b-sekelton:** animation overflow issue for Safari
  ([#5863](https://github.com/bootstrap-vue/bootstrap-vue/issues/5863))
  ([bfd4f96](https://github.com/bootstrap-vue/bootstrap-vue/commit/bfd4f960d7056edcd2ccb1ae3930639d543d8b34))
- **b-sidebar:** make sure to not exceed 100% in height (closes
  [#6176](https://github.com/bootstrap-vue/bootstrap-vue/issues/6176))
  ([#6234](https://github.com/bootstrap-vue/bootstrap-vue/issues/6234))
  ([782e11d](https://github.com/bootstrap-vue/bootstrap-vue/commit/782e11dedf8ed9f362a1c44772d660adf24975a5))
- **b-skeleton:** accepts custom attributes
  ([#6858](https://github.com/bootstrap-vue/bootstrap-vue/issues/6858))
  ([9b1edc9](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b1edc978f7029facaf5a4f2a512b13cd43987a8))
- **b-skeleton:** add missing component exports
  ([#5806](https://github.com/bootstrap-vue/bootstrap-vue/issues/5806))
  ([871ce22](https://github.com/bootstrap-vue/bootstrap-vue/commit/871ce22504c4e64348b844c0e4306161317abf60))
- **b-table:** add missing `role="grid"` when selectable (closes
  [#6305](https://github.com/bootstrap-vue/bootstrap-vue/issues/6305))
  ([#6372](https://github.com/bootstrap-vue/bootstrap-vue/issues/6372))
  ([bc02fb8](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc02fb86198701f8f2ef7b05dadf59cd2c0381cd))
- **b-table:** add missing `sortKey` field type and correct a typo
  ([#6355](https://github.com/bootstrap-vue/bootstrap-vue/issues/6355))
  ([f5ca62f](https://github.com/bootstrap-vue/bootstrap-vue/commit/f5ca62faec6d5fb9e873b362b6efb153d419a7cc))
- **b-table:** allow `responsive` and `stacked` props together
  ([#6266](https://github.com/bootstrap-vue/bootstrap-vue/issues/6266))
  ([fa977a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa977a83cf21dd118e30f81aacf80d1c25b5c484))
- **b-table:** default `role` to `grid` when `selectable` and `table` otherwise
  ([#6383](https://github.com/bootstrap-vue/bootstrap-vue/issues/6383))
  ([3f5a309](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f5a3095500c706a75f0f0d6015b0b2777051e1f)),
  closes [#6326](https://github.com/bootstrap-vue/bootstrap-vue/issues/6326)
- **b-table:** fix range selection of b-table
  ([#6606](https://github.com/bootstrap-vue/bootstrap-vue/issues/6606))
  ([c11f0db](https://github.com/bootstrap-vue/bootstrap-vue/commit/c11f0db211aa2c45209a4081ae4e02337ec55015))
- **b-table:** header cell overflow for `.sr-only` sort label
  ([#6371](https://github.com/bootstrap-vue/bootstrap-vue/issues/6371))
  ([11617b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/11617b4c78d06a0f48306983621fdb4ec1aa9932))
- **b-table:** make sure to apply all formatters of field configuration (closes
  [#5672](https://github.com/bootstrap-vue/bootstrap-vue/issues/5672))
  ([#5674](https://github.com/bootstrap-vue/bootstrap-vue/issues/5674))
  ([c7c14ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7c14ea1d023b26af8a12c12dbc2c3d8220b7f67))
- **b-table:** only set `aria-describedby` when caption really exists
  ([#6251](https://github.com/bootstrap-vue/bootstrap-vue/issues/6251))
  ([b980017](https://github.com/bootstrap-vue/bootstrap-vue/commit/b980017139613db5d7c8df4293a4d80673c9e646))
- **b-table:** only set `tabindex="0"` for sortable TH's
  ([#6102](https://github.com/bootstrap-vue/bootstrap-vue/issues/6102))
  ([dd23742](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd237425e4e7a7e73d5c17210780b02dab2110e2))
- **b-table:** prefer user-provided `role` attribute
  ([#6382](https://github.com/bootstrap-vue/bootstrap-vue/issues/6382))
  ([9e25a3b](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e25a3b97e911e84473991def78c9b4307b6f822))
- **b-table:** prevent endless reevaluation when using v-model and object/array literal prop values
  ([#5554](https://github.com/bootstrap-vue/bootstrap-vue/issues/5554))
  ([f127d91](https://github.com/bootstrap-vue/bootstrap-vue/commit/f127d916d1ddd3a3da37bcb081150f86b356a7a4))
- **b-table:** properly handle empty included/excluded filter fields (closes
  [#5775](https://github.com/bootstrap-vue/bootstrap-vue/issues/5775))
  ([#5780](https://github.com/bootstrap-vue/bootstrap-vue/issues/5780))
  ([78ac383](https://github.com/bootstrap-vue/bootstrap-vue/commit/78ac383c0c727be4f970874e73bf05e3f23b1a3b))
- **b-table:** selected table header text no longer prevents table row selection
  ([#6645](https://github.com/bootstrap-vue/bootstrap-vue/issues/6645))
  ([010ab31](https://github.com/bootstrap-vue/bootstrap-vue/commit/010ab3180eaeb9f43e9c922fb6e47419504b8f99))
- **b-table:** set `aria-sort` when using `sortKey` and `no-local-sorting` (closes
  [#6602](https://github.com/bootstrap-vue/bootstrap-vue/issues/6602))
  ([#6603](https://github.com/bootstrap-vue/bootstrap-vue/issues/6603))
  ([2438137](https://github.com/bootstrap-vue/bootstrap-vue/commit/2438137c3757b28657e7185432805079ee25c559))
- **b-table:** sort handling for numeric string values (closes
  [#6092](https://github.com/bootstrap-vue/bootstrap-vue/issues/6092))
  ([#6105](https://github.com/bootstrap-vue/bootstrap-vue/issues/6105))
  ([29fbcb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/29fbcb58c5efed0dbbafa8b0bb5fc1d1651079cd))
- **b-tabs:** cleanup rendering logic
  ([#6154](https://github.com/bootstrap-vue/bootstrap-vue/issues/6154))
  ([8aeb9e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/8aeb9e941e84ec45a3415ab7238729458f56e427))
- **b-tabs:** restore correct active tab detection logic (closes
  [#6205](https://github.com/bootstrap-vue/bootstrap-vue/issues/6205))
  ([#6208](https://github.com/bootstrap-vue/bootstrap-vue/issues/6208))
  ([6d92a43](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d92a4376c227a02a7c24e19c04e437bb8909c1c))
- **b-tags:** replace spacing utility with static CSS (fixes
  [#5523](https://github.com/bootstrap-vue/bootstrap-vue/issues/5523))
  ([#5544](https://github.com/bootstrap-vue/bootstrap-vue/issues/5544))
  ([e0de687](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0de6871640db405e7b0bfa23f3c33f348894cea))
- **b-tooltip, b-popover:** fix `title` not being reset on hide
  ([#5793](https://github.com/bootstrap-vue/bootstrap-vue/issues/5793))
  ([31eeb0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/31eeb0ab5ef262c33579f43969c7d6ee6c802e3d))
- **bv-tooltip:** hide the tooltip when the title is set to empty (closes
  [#5648](https://github.com/bootstrap-vue/bootstrap-vue/issues/5648))
  ([#5677](https://github.com/bootstrap-vue/bootstrap-vue/issues/5677))
  ([5363a31](https://github.com/bootstrap-vue/bootstrap-vue/commit/5363a3132df898cb5f0cac172c0510aead62d66e))
- **compat:** correctly handle undefined in slots
  ([725d31b](https://github.com/bootstrap-vue/bootstrap-vue/commit/725d31b9a9fed29e0e7d0e2685ab89d8f1b9e98a))
- **docs:** completing the url so that the link is correct
  ([#6545](https://github.com/bootstrap-vue/bootstrap-vue/issues/6545))
  ([c9c85a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9c85a92460c583439f96b61095e2fa0f3c41378))
- **nav-item-dropdown:** update dropdown to set correct aria-controls
  ([97bb97b](https://github.com/bootstrap-vue/bootstrap-vue/commit/97bb97b004b28bc34a49fc20dcc5b247f228404f))
- **perf:** reactivity issues with `bvAttrs` and `bvListeners` (closes
  [#5520](https://github.com/bootstrap-vue/bootstrap-vue/issues/5520))
  ([#5753](https://github.com/bootstrap-vue/bootstrap-vue/issues/5753))
  ([d83a2b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/d83a2b179cac2f7449a7138fce71e07139e18c94))
- **table:** default sort compare logic for date strings
  ([#6153](https://github.com/bootstrap-vue/bootstrap-vue/issues/6153))
  ([3696a1f](https://github.com/bootstrap-vue/bootstrap-vue/commit/3696a1f888f2462a428431a593e235fd89bf54d4))
- **util:** retain parent-child relationship for Vue 2
  ([58e2d7e](https://github.com/bootstrap-vue/bootstrap-vue/commit/58e2d7e4f5e883207c4f7baa856532d3ae924a0c))
- **utils/dom:** bind `requestAF()` to `window`
  ([#6508](https://github.com/bootstrap-vue/bootstrap-vue/issues/6508))
  ([#6511](https://github.com/bootstrap-vue/bootstrap-vue/issues/6511))
  ([f8caaec](https://github.com/bootstrap-vue/bootstrap-vue/commit/f8caaec837b184d3f2736a6fdb4b8ceea28942ae))
- **v-b-toggle:** prevent scroll anchoring behavior (closes
  [#5715](https://github.com/bootstrap-vue/bootstrap-vue/issues/5715))
  ([#5769](https://github.com/bootstrap-vue/bootstrap-vue/issues/5769))
  ([390a5c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/390a5c7045432c98999ae8bf9259fb9ae03bcb19))
- **v-tooltip, v-popover:** render data-\* attributes on root components (closes
  [#5836](https://github.com/bootstrap-vue/bootstrap-vue/issues/5836))
  ([#5882](https://github.com/bootstrap-vue/bootstrap-vue/issues/5882))
  ([f6b51e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6b51e04f074e45e98650034e88c2b5629ad25f6))
- **vue3:** do not rely on \_\_vueParentComponent in tooltip
  ([fe13503](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe13503f7aa6d0bd6f7e1ed4f4a2e7acff421106))
- clean up props inheritance ([#6265](https://github.com/bootstrap-vue/bootstrap-vue/issues/6265))
  ([79784ae](https://github.com/bootstrap-vue/bootstrap-vue/commit/79784ae6e03f90ee14ce90f8f5e02d0249eb5c4a))
- CodeSandbox integration ([#5381](https://github.com/bootstrap-vue/bootstrap-vue/issues/5381))
  ([a948846](https://github.com/bootstrap-vue/bootstrap-vue/commit/a948846400c37fca0fa3ed673b1c4684fc6f69e1))
- component destroy handling on parent destroy
  ([#5749](https://github.com/bootstrap-vue/bootstrap-vue/issues/5749))
  ([e67d341](https://github.com/bootstrap-vue/bootstrap-vue/commit/e67d34190358cb5e9d3e6d45ec74f045bf20caef))
- don't display BootstrapVue warning messages when in production
  ([bf8966f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf8966f6de725bf2828ca4609056c27dd4a96399))
- don't display warning messages when in production (closes
  [#5598](https://github.com/bootstrap-vue/bootstrap-vue/issues/5598))
  ([#5763](https://github.com/bootstrap-vue/bootstrap-vue/issues/5763))
  ([4b5d916](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b5d9162b8a6531c0ada66f646498b0ba40a0e9b))
- environment detection based on `userAgent`
  ([#6226](https://github.com/bootstrap-vue/bootstrap-vue/issues/6226))
  ([cdfd16c](https://github.com/bootstrap-vue/bootstrap-vue/commit/cdfd16c32296072e49596a8acf722c77709f1b93))
- replace sass division with multiplication
  ([#6834](https://github.com/bootstrap-vue/bootstrap-vue/issues/6834))
  ([dd051e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd051e93cbb2ce41d3060eda2b5a82ce28fe183c))
- update refs inside v-for to work for @vue/compat
  ([ae4bac8](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae4bac8a4327a1f293afbcf571e84ed1de4497f8))
- user supplied prop function detection (closes
  [#6112](https://github.com/bootstrap-vue/bootstrap-vue/issues/6112))
  ([#6113](https://github.com/bootstrap-vue/bootstrap-vue/issues/6113))
  ([1d85839](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d85839fa76c88f1a411a81945d03a4c895b3f4f))
- **ssr:** avoid tree missmatches by either using `domProps` or `children` (closes
  [#5453](https://github.com/bootstrap-vue/bootstrap-vue/issues/5453),
  [#5557](https://github.com/bootstrap-vue/bootstrap-vue/issues/5557))
  ([#5723](https://github.com/bootstrap-vue/bootstrap-vue/issues/5723))
  ([5e8dad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e8dad84c094ff1f7810f69293418b81e676af26))
- **table:** use original value for fallback when number parsing fails in `defaultSortCompare()`
  ([c375ce9](https://github.com/bootstrap-vue/bootstrap-vue/commit/c375ce9093ed91060b4ab199ad771dd667a68589))
- **v-b-toggle:** handle component updates on click listeners
  ([#5690](https://github.com/bootstrap-vue/bootstrap-vue/issues/5690))
  ([156b1d6](https://github.com/bootstrap-vue/bootstrap-vue/commit/156b1d6a3a1ebb6548ea0dbfac346d61a92f6ed9))
- ensure all intervals/timeouts/observers are cleared when component is destroyed
  ([#5362](https://github.com/bootstrap-vue/bootstrap-vue/issues/5362))
  ([064cdf4](https://github.com/bootstrap-vue/bootstrap-vue/commit/064cdf4f7e7c6b779c1bd689a6d300efdf81bc0d))
- properly handle HTML props render order (closes
  [#5363](https://github.com/bootstrap-vue/bootstrap-vue/issues/5363))
  ([#5365](https://github.com/bootstrap-vue/bootstrap-vue/issues/5365))
  ([844ecda](https://github.com/bootstrap-vue/bootstrap-vue/commit/844ecda654a2db50d9b84c193f1ab031e291d024))
- properly handle special characters in user-provided IDs (closes
  [#4927](https://github.com/bootstrap-vue/bootstrap-vue/issues/4927),
  [#5561](https://github.com/bootstrap-vue/bootstrap-vue/issues/5561))
  ([#5564](https://github.com/bootstrap-vue/bootstrap-vue/issues/5564))
  ([1fabd68](https://github.com/bootstrap-vue/bootstrap-vue/commit/1fabd68bb44b28a9127810f35bd07e1fdf3d12ec))
- user supplied prop function detection
  ([#6070](https://github.com/bootstrap-vue/bootstrap-vue/issues/6070))
  ([cea6051](https://github.com/bootstrap-vue/bootstrap-vue/commit/cea6051efc901325d63c22f65381242bd6e774e7))
- **b-alert:** memory leak by using the correct method to clear the countdown timeout
  ([#5158](https://github.com/bootstrap-vue/bootstrap-vue/issues/5158))
  ([7a7f33d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a7f33d74f906e5feecf2bf177636c7f85bc4537))
- **b-avatar:** fix button type font size inheritance
  ([#5177](https://github.com/bootstrap-vue/bootstrap-vue/issues/5177))
  ([441ebdc](https://github.com/bootstrap-vue/bootstrap-vue/commit/441ebdc8a262c6c6ed494ddc6a6c0c06604045ef))
- **b-avatar:** remove default padding when in button mode (fixes
  [#5073](https://github.com/bootstrap-vue/bootstrap-vue/issues/5073))
  ([#5076](https://github.com/bootstrap-vue/bootstrap-vue/issues/5076))
  ([26377b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/26377b3479f323baa2d702fab7f5200949ed680d))
- **b-avatar:** remove duplicate button variant class
  ([#5056](https://github.com/bootstrap-vue/bootstrap-vue/issues/5056))
  ([9f78f32](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f78f32d964b187f35a1feffb7aa4bc264587923))
- **b-avatar:** set `align-items: center` for default slot content (fixes:
  [#5205](https://github.com/bootstrap-vue/bootstrap-vue/issues/5205))
  ([#5207](https://github.com/bootstrap-vue/bootstrap-vue/issues/5207))
  ([c4981fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4981fd098253840a37e731331de65b0e732fc79))
- **b-button:** when `href` is "#" add `role=button` and appropriate keydown handlers for A11Y
  ([#4768](https://github.com/bootstrap-vue/bootstrap-vue/issues/4768))
  ([087a128](https://github.com/bootstrap-vue/bootstrap-vue/commit/087a1283977061c44d5b059c203f13d2326dabae))
- **b-calendar:** use `Intl.NumberFormat` for formatting the number in the date buttons (closes
  [#5171](https://github.com/bootstrap-vue/bootstrap-vue/issues/5171))
  ([#5179](https://github.com/bootstrap-vue/bootstrap-vue/issues/5179))
  ([cbf2cd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbf2cd007cce81a5f664fa649b08af6735fe16e4))
- **b-calendar, b-form-datepicker:** handle keyboard navigation when selected date is out of range
  (fixes [#5057](https://github.com/bootstrap-vue/bootstrap-vue/issues/5057))
  ([#5108](https://github.com/bootstrap-vue/bootstrap-vue/issues/5108))
  ([6ed09f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/6ed09f40ae1594c7ad96dedc8c3d7c2a54d4d9c7))
- **b-calendar, b-form-datepicker:** minor adjustments to styling and example updates
  ([#5211](https://github.com/bootstrap-vue/bootstrap-vue/issues/5211))
  ([f0d8ffe](https://github.com/bootstrap-vue/bootstrap-vue/commit/f0d8ffe4253079939008108fe86529a2f69553f1))
- **b-card:** handle `header-html` and `footer-html` props correctly (fixes
  [#5038](https://github.com/bootstrap-vue/bootstrap-vue/issues/5038))
  ([#5039](https://github.com/bootstrap-vue/bootstrap-vue/issues/5039))
  ([f378aef](https://github.com/bootstrap-vue/bootstrap-vue/commit/f378aeffdebdc7922f6ad4c5d513642dfb93cf1d))
- **b-collapse:** fix memory leak from `$root` listener (fixes
  [#3607](https://github.com/bootstrap-vue/bootstrap-vue/issues/3607))
  ([#3608](https://github.com/bootstrap-vue/bootstrap-vue/issues/3608))
  ([10cb3a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/10cb3a9bda50668497e47172f7e17796f0144409))
- **b-dropdown:** close when clicking on nested elements inside items with `to` prop
  ([#3476](https://github.com/bootstrap-vue/bootstrap-vue/issues/3476))
  ([8ec2eb1](https://github.com/bootstrap-vue/bootstrap-vue/commit/8ec2eb12d67f4b30f45f62b9a886ea202ae82cf3))
- **b-dropdown:** delay show of dropdown when calling `show()` (closes
  [#3366](https://github.com/bootstrap-vue/bootstrap-vue/issues/3366))
  ([#3367](https://github.com/bootstrap-vue/bootstrap-vue/issues/3367))
  ([1604022](https://github.com/bootstrap-vue/bootstrap-vue/commit/1604022f9866456e9da3c627e3613f56cca1f700))
- **b-dropdown:** focus-in handling for Safari and Firefox on macOS/iOS (closes
  [#4328](https://github.com/bootstrap-vue/bootstrap-vue/issues/4328))
  ([#4426](https://github.com/bootstrap-vue/bootstrap-vue/issues/4426))
  ([2eab55b](https://github.com/bootstrap-vue/bootstrap-vue/commit/2eab55b4672a35a487b30f0f64c63b887b361473))
- **b-dropdown:** handle issue with touch devices on MacOS using Safari/Firefox (Fixes
  [#4328](https://github.com/bootstrap-vue/bootstrap-vue/issues/4328),
  [#4344](https://github.com/bootstrap-vue/bootstrap-vue/issues/4344))
  ([#4329](https://github.com/bootstrap-vue/bootstrap-vue/issues/4329))
  ([2779a0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2779a0aeeebe0797bb38f3f17c83fb463ee41624))
- **b-dropdown-\*:** ensure class bindings are placed on root element for all dropdown
  sub-components (closes [#4022](https://github.com/bootstrap-vue/bootstrap-vue/issues/4022))
  ([#4024](https://github.com/bootstrap-vue/bootstrap-vue/issues/4024))
  ([81efb89](https://github.com/bootstrap-vue/bootstrap-vue/commit/81efb8981d38ffd3d154c4eedbfdea550676c000))
- **b-dropdown-form:** fix SCSS styling when placed in a nav dropdown (fixes
  [#4220](https://github.com/bootstrap-vue/bootstrap-vue/issues/4220))
  ([#4223](https://github.com/bootstrap-vue/bootstrap-vue/issues/4223))
  ([b852bba](https://github.com/bootstrap-vue/bootstrap-vue/commit/b852bba99c866f977af0b330167a9d49341392b4))
- **b-form-datepicker:** make datepicker respect `no-highlight-today` prop
  ([#5159](https://github.com/bootstrap-vue/bootstrap-vue/issues/5159))
  ([c4ead33](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4ead3302b176e4a90fbfcfe6380de0edc22640f))
- **b-form-datepicker:** menu focus handling for Firefox and Safari on MacOS (closes
  [#4814](https://github.com/bootstrap-vue/bootstrap-vue/issues/4814))
  ([#4824](https://github.com/bootstrap-vue/bootstrap-vue/issues/4824))
  ([09fa920](https://github.com/bootstrap-vue/bootstrap-vue/commit/09fa920e4a904c6340c60586b40451dce94efc44))
- **b-form-datepicker, b-form-timepicker:** adjust scss to support input-groups
  ([#5231](https://github.com/bootstrap-vue/bootstrap-vue/issues/5231))
  ([7b1adc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7b1adc460f11c2ee54466fe0d204579f3f6f1bd2))
- **b-form-datepicker, b-form-timepicker:** fix menu padding in button only mode (fixes
  [#5251](https://github.com/bootstrap-vue/bootstrap-vue/issues/5251))
  ([#5252](https://github.com/bootstrap-vue/bootstrap-vue/issues/5252))
  ([d57a643](https://github.com/bootstrap-vue/bootstrap-vue/commit/d57a643f0c6b5e805a42a3387fb0db4443bfc01f))
- **b-form-datepicker, b-form-timepicker:** prevent duplicate validation icons (fixes
  [#5237](https://github.com/bootstrap-vue/bootstrap-vue/issues/5237))
  ([#5238](https://github.com/bootstrap-vue/bootstrap-vue/issues/5238))
  ([6354e6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/6354e6eb90b93e668c2794b3b4c2117a7cfc0ab0))
- **b-form-file:** fix prop type checking for `value` prop
  ([#4168](https://github.com/bootstrap-vue/bootstrap-vue/issues/4168))
  ([a8e2e56](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8e2e566f34fa40614292f6192d8b322a2ed2877))
- **b-form-file:** fix value prop validation when using directory mode (fixes
  [#4912](https://github.com/bootstrap-vue/bootstrap-vue/issues/4912))
  ([#4913](https://github.com/bootstrap-vue/bootstrap-vue/issues/4913))
  ([498a262](https://github.com/bootstrap-vue/bootstrap-vue/commit/498a26219571bb6108aaa7134dc25c8e1ff6c98f))
- **b-form-file:** make sure to catch all errors when resetting the input
  ([#4936](https://github.com/bootstrap-vue/bootstrap-vue/issues/4936))
  ([682bc46](https://github.com/bootstrap-vue/bootstrap-vue/commit/682bc46028cacfdb570fe416a051160ee9789fe2))
- **b-form-input, b-form-textarea:** handle change event for all mobile device keyboards (closes
  [#4724](https://github.com/bootstrap-vue/bootstrap-vue/issues/4724))
  ([#4739](https://github.com/bootstrap-vue/bootstrap-vue/issues/4739))
  ([166a932](https://github.com/bootstrap-vue/bootstrap-vue/commit/166a932fb11fa552714aba7df67992e1265b9047))
- **b-form-input, b-form-textarea:** properly handle out-of-sync values (closes
  [#4695](https://github.com/bootstrap-vue/bootstrap-vue/issues/4695))
  ([#4701](https://github.com/bootstrap-vue/bootstrap-vue/issues/4701))
  ([954176d](https://github.com/bootstrap-vue/bootstrap-vue/commit/954176d733dccdd074f5b6cb31c4041081a3b206))
- **b-form-spinbutton:** prevent buttons from re-ordering when parent element is RTL
  ([#4802](https://github.com/bootstrap-vue/bootstrap-vue/issues/4802))
  ([ae2cce9](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae2cce9d593bd310b3d2256ade41df0243447970))
- **b-form-spinbutton:** prevent double increment/decrement on mobile (fixes
  [#4838](https://github.com/bootstrap-vue/bootstrap-vue/issues/4838))
  ([#4842](https://github.com/bootstrap-vue/bootstrap-vue/issues/4842))
  ([9c2c700](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c2c700a91d7a6e57572f579f68996eaceda5c00))
- **b-form-spinbutton:** respect step value for initial decrement when `wrap` enabled (closes
  [#4884](https://github.com/bootstrap-vue/bootstrap-vue/issues/4884))
  ([#4885](https://github.com/bootstrap-vue/bootstrap-vue/issues/4885))
  ([28e7245](https://github.com/bootstrap-vue/bootstrap-vue/commit/28e724536be4762382328648f203bd46d8f52fdc))
- **b-form-tags:** improve accessibility for screen reader users
  ([#4775](https://github.com/bootstrap-vue/bootstrap-vue/issues/4775))
  ([2328630](https://github.com/bootstrap-vue/bootstrap-vue/commit/2328630542defc395912165a964a95107f8a4ba9))
- **b-form-textarea:** handle initial auto-height when in modal, tabs, or other component with
  transition or which uses `v-show` (fixes
  [#3936](https://github.com/bootstrap-vue/bootstrap-vue/issues/3936),
  [#3702](https://github.com/bootstrap-vue/bootstrap-vue/issues/3702))
  ([#3937](https://github.com/bootstrap-vue/bootstrap-vue/issues/3937))
  ([be3ac62](https://github.com/bootstrap-vue/bootstrap-vue/commit/be3ac62b81d43c434d03bd833db22e99bd1da3f4))
- **b-img-lazy:** better initial inView check + new show prop (fixes
  [#1755](https://github.com/bootstrap-vue/bootstrap-vue/issues/1755))
  ([#2382](https://github.com/bootstrap-vue/bootstrap-vue/issues/2382))
  ([2416bad](https://github.com/bootstrap-vue/bootstrap-vue/commit/2416bad6a57a02f4144eb131412370410ff2597d))
- **b-input-group:** fix kebab-case prop names for `prepend-html` and `append-html` (fixes
  [#3565](https://github.com/bootstrap-vue/bootstrap-vue/issues/3565))
  ([#3567](https://github.com/bootstrap-vue/bootstrap-vue/issues/3567))
  ([e48d3dc](https://github.com/bootstrap-vue/bootstrap-vue/commit/e48d3dc350c4767df9d53e3e2173b6bf125523dd))
- **b-link:** default new `<nuxt-link>` prop `prefetch` to `null` for true tri-state prop
  ([#5357](https://github.com/bootstrap-vue/bootstrap-vue/issues/5357))
  ([3f41c91](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f41c91961c29988ba13ca11f4dc8f81810e761f))
- **b-link:** don't render `target` or `rel` attrs when `router-tag` other than `a` or `area`
  provided ([#5107](https://github.com/bootstrap-vue/bootstrap-vue/issues/5107))
  ([33c6cef](https://github.com/bootstrap-vue/bootstrap-vue/commit/33c6cefc2f46ab8110e39f110d984f230d525c86))
- **b-link:** only add the `nativeOn` property to componentData when rendering a router link
  ([#3976](https://github.com/bootstrap-vue/bootstrap-vue/issues/3976))
  ([62fb0b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/62fb0b68aa059d5c827072f569026222eaa9ad4b))
- **b-media:** fix vertical align class when top or bottom selected (fixes
  [#4052](https://github.com/bootstrap-vue/bootstrap-vue/issues/4052))
  ([#4055](https://github.com/bootstrap-vue/bootstrap-vue/issues/4055))
  ([9ccfe4c](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ccfe4ca61914d23bd1da0e33550e6a1af83bb18))
- **b-modal:** additional fixes for show transition behaviour (closes
  [#4761](https://github.com/bootstrap-vue/bootstrap-vue/issues/4761))
  ([#4777](https://github.com/bootstrap-vue/bootstrap-vue/issues/4777))
  ([1113c6f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1113c6f951d86b7e6e6ba2161f935d2b6e0b5ce8))
- **b-modal:** ensure header is read for accessibility with JAWS (closes
  [#3712](https://github.com/bootstrap-vue/bootstrap-vue/issues/3712))
  ([#3713](https://github.com/bootstrap-vue/bootstrap-vue/issues/3713))
  ([6a9d0ce](https://github.com/bootstrap-vue/bootstrap-vue/commit/6a9d0ceb363a40ff9e23d0aaf6a9185a3384f268))
- **b-modal:** ensure non-prop attributes are transferred to the modal outer wrapper `div` (closes
  [#3896](https://github.com/bootstrap-vue/bootstrap-vue/issues/3896))
  ([#3921](https://github.com/bootstrap-vue/bootstrap-vue/issues/3921))
  ([8bf3a55](https://github.com/bootstrap-vue/bootstrap-vue/commit/8bf3a55a01811671fee223011dd90903faf1b79b))
- **b-modal:** prevent page scroll when tabbing to bottom of modal + better tab containment in
  enforceFocus (closes [#3842](https://github.com/bootstrap-vue/bootstrap-vue/issues/3842))
  ([#3846](https://github.com/bootstrap-vue/bootstrap-vue/issues/3846))
  ([ed99f9c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed99f9c67793a3a8895812a514717b9c10d9012e))
- **b-modal:** remove `role="document"` from `.modal-content`
  ([#5345](https://github.com/bootstrap-vue/bootstrap-vue/issues/5345))
  ([0c2b406](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c2b406e8dadc274e8433d3a4c414e799d0fa228))
- **b-modal:** transition timing
  ([#4766](https://github.com/bootstrap-vue/bootstrap-vue/issues/4766))
  ([968c957](https://github.com/bootstrap-vue/bootstrap-vue/commit/968c95758e45610a8c002507790c79d87d8fe956))
- **b-nav-form, b-nav-text:** ensure these sub-components have `<li>` as root element for
  accessibility ([#4100](https://github.com/bootstrap-vue/bootstrap-vue/issues/4100))
  ([6774800](https://github.com/bootstrap-vue/bootstrap-vue/commit/677480035f34ee735d0aa3ac98323aea2cbad732))
- **b-nav-item-dropdown:** clicking toggle a second time should close menu (closes
  [#3707](https://github.com/bootstrap-vue/bootstrap-vue/issues/3707))
  ([#3706](https://github.com/bootstrap-vue/bootstrap-vue/issues/3706))
  ([629951e](https://github.com/bootstrap-vue/bootstrap-vue/commit/629951e4763dcdc625d31484495e17f4a9e39f68))
- **b-pagination-nav:** attempt to auto-detect current page when `pages` array or `number of pages`
  changes (closes [#3443](https://github.com/bootstrap-vue/bootstrap-vue/issues/3443))
  ([#3444](https://github.com/bootstrap-vue/bootstrap-vue/issues/3444))
  ([88b95c6](https://github.com/bootstrap-vue/bootstrap-vue/commit/88b95c6d0e97372ad9a2d59b06df1975b5aad338))
- **b-pagination, b-pagination-nav:** add UP/DOWN keyboard navigation support for JAWS (fixes
  [#4322](https://github.com/bootstrap-vue/bootstrap-vue/issues/4322))
  ([#4325](https://github.com/bootstrap-vue/bootstrap-vue/issues/4325))
  ([c686088](https://github.com/bootstrap-vue/bootstrap-vue/commit/c686088f939328eb30d0bf089d077584e2988b70))
- **b-popover, b-tooltip:** ensure `boundary-padding` is passed to popper instance (fixes
  [#4131](https://github.com/bootstrap-vue/bootstrap-vue/issues/4131))
  ([#4133](https://github.com/bootstrap-vue/bootstrap-vue/issues/4133))
  ([a54a647](https://github.com/bootstrap-vue/bootstrap-vue/commit/a54a647d64dc1251c2667f2179f6e8d648dccd40))
- **b-table:** add clearfix to table cells in case label wraps in stacked mode
  ([#3652](https://github.com/bootstrap-vue/bootstrap-vue/issues/3652))
  ([3115dae](https://github.com/bootstrap-vue/bootstrap-vue/commit/3115daeedf334479b79623a58bc0d9a2bcc7f242))
- **b-table:** ensure `ctx.sortBy` is an empty string when no sorting
  ([#3534](https://github.com/bootstrap-vue/bootstrap-vue/issues/3534))
  ([d451687](https://github.com/bootstrap-vue/bootstrap-vue/commit/d451687ffcb8bfdbf90ed7d2a79bcf1c1e18b23a))
- **b-table:** handle filter as an object when using providers and prevent duplicate provider calls
  on mount (fixes [#4065](https://github.com/bootstrap-vue/bootstrap-vue/issues/4065))
  ([#4068](https://github.com/bootstrap-vue/bootstrap-vue/issues/4068))
  ([9ddd115](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ddd1151a316b47d26ca91319f0f9eba630c5538))
- **b-table:** IE11 edge case where custom inputs were not clickable in clickable/sortable cells
  (fixes [#3693](https://github.com/bootstrap-vue/bootstrap-vue/issues/3693))
  ([#3697](https://github.com/bootstrap-vue/bootstrap-vue/issues/3697))
  ([fce8b5b](https://github.com/bootstrap-vue/bootstrap-vue/commit/fce8b5bc78e47462f5831584b0bfde9f2329293d))
- **b-table:** minor code optimizations to filter debouncing
  ([#4167](https://github.com/bootstrap-vue/bootstrap-vue/issues/4167))
  ([018eef1](https://github.com/bootstrap-vue/bootstrap-vue/commit/018eef139ee9a49dd08a5da01157412adccb4486))
- **b-table:** remove extra slashes in mixins imports
  ([#4087](https://github.com/bootstrap-vue/bootstrap-vue/issues/4087))
  ([77f5be1](https://github.com/bootstrap-vue/bootstrap-vue/commit/77f5be15c08f4ce73b015592b55ee01239d7eaa1))
- **b-table-lite:** add checks to helper mixins for existence of stopIfBusy (closes
  [#3518](https://github.com/bootstrap-vue/bootstrap-vue/issues/3518))
  ([#3520](https://github.com/bootstrap-vue/bootstrap-vue/issues/3520))
  ([285cf94](https://github.com/bootstrap-vue/bootstrap-vue/commit/285cf94608c5be7c9a4f5a3d89e9970734fafb03))
- **b-table, b-table-lite:** handle edge case where field slot returns no vNodes (fixes
  [#3919](https://github.com/bootstrap-vue/bootstrap-vue/issues/3919))
  ([#3920](https://github.com/bootstrap-vue/bootstrap-vue/issues/3920))
  ([a392059](https://github.com/bootstrap-vue/bootstrap-vue/commit/a39205940f6ccf777e92c54d680e9ed0008abd77))
- **b-table, b-table-lite:** handle edge case with row events when table is removed from dom.
  instantiate row event handlers only when listeners are registered (fixes
  [#4384](https://github.com/bootstrap-vue/bootstrap-vue/issues/4384))
  ([#4388](https://github.com/bootstrap-vue/bootstrap-vue/issues/4388))
  ([9a81cd4](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a81cd414a2c534b96de0d82c3d00d94651e5a7b))
- **b-table, b-table-lite:** render header when not always stacked mode (fixes
  [#3886](https://github.com/bootstrap-vue/bootstrap-vue/issues/3886))
  ([#3887](https://github.com/bootstrap-vue/bootstrap-vue/issues/3887))
  ([2302b31](https://github.com/bootstrap-vue/bootstrap-vue/commit/2302b31d63290abcf72b52d3ddb5d6a6767ec356))
- **b-table, b-table-lite:** use `:key` for row details based on the primary key value if available
  ([#4025](https://github.com/bootstrap-vue/bootstrap-vue/issues/4025))
  ([c7cb16f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7cb16fee8d3a4d884490f4cb41298c597b0bfa5))
- **b-table, b-table-lite, b-table-simple:** handle header variant for sticky columns (fixes
  [#5278](https://github.com/bootstrap-vue/bootstrap-vue/issues/5278))
  ([#5279](https://github.com/bootstrap-vue/bootstrap-vue/issues/5279))
  ([53e309e](https://github.com/bootstrap-vue/bootstrap-vue/commit/53e309e947b4710fcf8d989cc9ef0f31c58487ae))
- **b-table, b-table-lite, b-tbody:** fix delegated event handlers when transition + minor
  adjustment to row `key` generation (fixes
  [#4370](https://github.com/bootstrap-vue/bootstrap-vue/issues/4370))
  ([#4372](https://github.com/bootstrap-vue/bootstrap-vue/issues/4372))
  ([030a3d8](https://github.com/bootstrap-vue/bootstrap-vue/commit/030a3d8c9a89b253c0bb8dbf9be98151bd020176))
- **b-tabs:** allow space to trigger tab activation when `no-key-nav` is enabled (fixes
  [#4323](https://github.com/bootstrap-vue/bootstrap-vue/issues/4323))
  ([#4326](https://github.com/bootstrap-vue/bootstrap-vue/issues/4326))
  ([731365b](https://github.com/bootstrap-vue/bootstrap-vue/commit/731365b27f290fd2266709865b51307edd04e54e))
- **b-tabs:** improve child b-tab detection routine (closes
  [#3260](https://github.com/bootstrap-vue/bootstrap-vue/issues/3260))
  ([#3442](https://github.com/bootstrap-vue/bootstrap-vue/issues/3442))
  ([4a54e8d](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a54e8dcb941590b28ebe7bf40805cc1ce5f1f5e))
- **b-toast:** fix ensureToaster method call when toaster name changes
  ([#4468](https://github.com/bootstrap-vue/bootstrap-vue/issues/4468))
  ([744bb7a](https://github.com/bootstrap-vue/bootstrap-vue/commit/744bb7a77092a04184af31bf285e432110e1ab44))
- **b-tooltip:** fix arrow margin
  ([#4727](https://github.com/bootstrap-vue/bootstrap-vue/issues/4727))
  ([865a655](https://github.com/bootstrap-vue/bootstrap-vue/commit/865a6557fbf49115c05326f9a96c4f9fdf135e96))
- **b-tooltip/b-popover:** add `SVGElement` as acceptable prop type (closes
  [#4173](https://github.com/bootstrap-vue/bootstrap-vue/issues/4173))
  ([#4174](https://github.com/bootstrap-vue/bootstrap-vue/issues/4174))
  ([fab7fea](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab7fea0a69b36b95f0c9606122140fe771e8ac8))
- **breadcrumb-item:** correctly set domProps when no children provided
  ([523e3a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/523e3a2e6bc997d83e2379de27e2504a73de0dfe))
- **breadcrumb-item:** Fix `to` prop handling
  ([#2578](https://github.com/bootstrap-vue/bootstrap-vue/issues/2578))
  ([fba9df3](https://github.com/bootstrap-vue/bootstrap-vue/commit/fba9df350789e7bc58dccd6d795a65465dd66713))
- **breadcrumb-link:** correctly use html/text
  ([8b086a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b086a99a5878eabdc55ecae694f72b310287517))
- **build:** don't include babel runtime
  ([#2590](https://github.com/bootstrap-vue/bootstrap-vue/issues/2590))
  ([20828fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/20828fab7acf5d6fc60b699e5eb2529f8992dbe4))
- **card:** Drop `img-fluid` property
  ([#2548](https://github.com/bootstrap-vue/bootstrap-vue/issues/2548))
  ([cfc685f](https://github.com/bootstrap-vue/bootstrap-vue/commit/cfc685fab151899b47775b83a54815b34cbad635))
- **carousel:** disable the next/prev controls when the carousel is sliding (closes
  [#4210](https://github.com/bootstrap-vue/bootstrap-vue/issues/4210))
  ([#4212](https://github.com/bootstrap-vue/bootstrap-vue/issues/4212))
  ([64d556d](https://github.com/bootstrap-vue/bootstrap-vue/commit/64d556d452ed8feefdb56a7f40ceb9a08b5e617f))
- **carousel:** fix touchmove handler to re-enable swipe gestures
  ([#2844](https://github.com/bootstrap-vue/bootstrap-vue/issues/2844))
  ([a067f8c](https://github.com/bootstrap-vue/bootstrap-vue/commit/a067f8c03c511d3886a17576cab47ae59a3733af))
- **carousel:** reset `touchDeltaX` to prevent click transformed in swipe
  ([#3734](https://github.com/bootstrap-vue/bootstrap-vue/issues/3734))
  ([0e54839](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e548398e530687a6ec9ec35c89e97ed4cd913c6))
- **carousel:** setInterval memory leak when no slides provided
  ([#2399](https://github.com/bootstrap-vue/bootstrap-vue/issues/2399))
  ([ac2a708](https://github.com/bootstrap-vue/bootstrap-vue/commit/ac2a708194fdec9afca971cae1a8145ca8f591e6))
- **carousel-slide:** do not render `carousel-caption` wrapper if no content
  ([#3662](https://github.com/bootstrap-vue/bootstrap-vue/issues/3662))
  ([615a719](https://github.com/bootstrap-vue/bootstrap-vue/commit/615a719d8f7754be5cd1940a66fdf8bca469d6e8))
- **changelog:** correct typos ([#3950](https://github.com/bootstrap-vue/bootstrap-vue/issues/3950))
  ([2efd38a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2efd38ac3022a1e4a8503513b1094dd57bfdeb3c))
- **ci:** remove test-beta
  ([1076f3f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1076f3f392d5b22abce67f80783c94b09b69c036))
- **ci:** remove test-beta
  ([0fec992](https://github.com/bootstrap-vue/bootstrap-vue/commit/0fec9920a00ebb4aab0c4ae5df1662d36cb85cd5))
- **ci:** test on current vue
  ([e3282bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3282bdff9913e12f3292629002af878ffa2a321))
- **collapse:** don't make `id` prop required
  ([#4109](https://github.com/bootstrap-vue/bootstrap-vue/issues/4109))
  ([4f935ce](https://github.com/bootstrap-vue/bootstrap-vue/commit/4f935ced9371aac7e18bb65c591791ec7f76430c))
- **collapse/toggle:** persist toggle state on element and prevent multiple state emits (closes
  [#2923](https://github.com/bootstrap-vue/bootstrap-vue/issues/2923))
  ([#2924](https://github.com/bootstrap-vue/bootstrap-vue/issues/2924))
  ([6f899fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f899fcff1550e2109002ee6b3121fbd72c12a60))
- **config:** avoid using `of` operator (closes
  [#3525](https://github.com/bootstrap-vue/bootstrap-vue/issues/3525))
  ([#3526](https://github.com/bootstrap-vue/bootstrap-vue/issues/3526))
  ([17ec8d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/17ec8d0d2d9e280a4de9aaa25ec4385fcbb31a13))
- **deps:** Add @babel/runtime to devDependencies
  ([#2569](https://github.com/bootstrap-vue/bootstrap-vue/issues/2569))
  ([83a253b](https://github.com/bootstrap-vue/bootstrap-vue/commit/83a253b2f92a1d52a8ead6fb2064c08bf7d864c1))
- **docs:** add back missing leading slash to search urls
  ([#2947](https://github.com/bootstrap-vue/bootstrap-vue/issues/2947))
  ([fff8795](https://github.com/bootstrap-vue/bootstrap-vue/commit/fff8795aca5e574c3deab8ce5f09cc7571822075))
- **docs:** always use array format for `<b-form-select>` options
  ([#4841](https://github.com/bootstrap-vue/bootstrap-vue/issues/4841))
  ([6308a0f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6308a0f5c07aee3267c21bc5ca60746b7fab7cf0))
- **docs:** broken links and sync layout docs with Bootstrap's
  ([#4261](https://github.com/bootstrap-vue/bootstrap-vue/issues/4261))
  ([c7bc62c](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7bc62cb22e0b6d0d0363e3170890c497a1a8d36))
- **docs:** broken Twitter link
  ([#3912](https://github.com/bootstrap-vue/bootstrap-vue/issues/3912))
  ([611a507](https://github.com/bootstrap-vue/bootstrap-vue/commit/611a5072a5ae87ff56da67a0d39286549233cd4a))
- **docs:** change [@include](https://github.com/include) to [@import](https://github.com/import) in
  the Nuxt plugin module section
  ([4fad60a](https://github.com/bootstrap-vue/bootstrap-vue/commit/4fad60a200d5bbf24b2990fdc7ee9ac10b08f6a8))
- **docs:** correct and validate component meta information (closes
  [#2665](https://github.com/bootstrap-vue/bootstrap-vue/issues/2665))
  ([#2650](https://github.com/bootstrap-vue/bootstrap-vue/issues/2650))
  ([29147ca](https://github.com/bootstrap-vue/bootstrap-vue/commit/29147caba02b99ed32ba8f078b62bab063ea6395))
- **docs:** correct formatting of <b-modal> `ok-only` prop
  ([#4517](https://github.com/bootstrap-vue/bootstrap-vue/issues/4517))
  ([988653e](https://github.com/bootstrap-vue/bootstrap-vue/commit/988653ef626ca53535900634a62ccba289ac51a3))
- **docs:** correct modal directive name
  ([#3335](https://github.com/bootstrap-vue/bootstrap-vue/issues/3335))
  ([d4dcc35](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4dcc35718ed9f98171e6abc37d3b7318ddcb525))
- **docs:** correct polyfilling suggestions
  ([#3605](https://github.com/bootstrap-vue/bootstrap-vue/issues/3605))
  ([35806e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/35806e763bdd7f5689934b5db605668b6c3c76a5))
- **docs:** correct spelling error in `b-form-file` property description
  ([#4551](https://github.com/bootstrap-vue/bootstrap-vue/issues/4551))
  ([2f9b14a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2f9b14a105fa12e68299c101cd794023ed79eb7b))
- **docs:** correct typo on intro page
  ([#3827](https://github.com/bootstrap-vue/bootstrap-vue/issues/3827))
  ([986f5c0](https://github.com/bootstrap-vue/bootstrap-vue/commit/986f5c041e701e96f1d573aed793b94a14d1e884))
- **docs:** correct typos ([#2592](https://github.com/bootstrap-vue/bootstrap-vue/issues/2592))
  ([9883f8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/9883f8f9a18b72d541c40b67847aaac09501833e))
- **docs:** Correct typos in carousel docs
  ([#2585](https://github.com/bootstrap-vue/bootstrap-vue/issues/2585))
  ([87a721f](https://github.com/bootstrap-vue/bootstrap-vue/commit/87a721ff61b98a55d14ea8ef3c6c7b3ad5c3fb51))
- **docs:** create local marked-loader.js
  ([#2380](https://github.com/bootstrap-vue/bootstrap-vue/issues/2380))
  ([06cfb47](https://github.com/bootstrap-vue/bootstrap-vue/commit/06cfb47552fdacbdb05ee2e358aec1f126b5163a))
- **docs:** drop self-closing tags + build system improvements (fixes
  [#2882](https://github.com/bootstrap-vue/bootstrap-vue/issues/2882))
  ([#2893](https://github.com/bootstrap-vue/bootstrap-vue/issues/2893))
  ([310c7dc](https://github.com/bootstrap-vue/bootstrap-vue/commit/310c7dc94c1dc415c7f6db3d7296b277e8368021))
- **docs:** fix broken link ([#5341](https://github.com/bootstrap-vue/bootstrap-vue/issues/5341))
  ([562be51](https://github.com/bootstrap-vue/bootstrap-vue/commit/562be515608c777db0fb1b0b35ce6836e2951fad))
- **docs:** fix broken link in form-textarea docs
  ([#2598](https://github.com/bootstrap-vue/bootstrap-vue/issues/2598))
  ([07162e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/07162e17ac0f32791905a2571c2309b37fda54f5))
- **docs:** fix broken links ([#2635](https://github.com/bootstrap-vue/bootstrap-vue/issues/2635))
  ([fa90f3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa90f3ea38ef36a37915ead17b14a84299f1242c))
- **docs:** Fix broken links. Closes
  [#2517](https://github.com/bootstrap-vue/bootstrap-vue/issues/2517)
  ([#2528](https://github.com/bootstrap-vue/bootstrap-vue/issues/2528))
  ([c4b7e1e](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4b7e1ef7e69dbb082d939de0769eabd00956a80))
- **docs:** Fix directive import paths
  ([#2570](https://github.com/bootstrap-vue/bootstrap-vue/issues/2570))
  ([2475542](https://github.com/bootstrap-vue/bootstrap-vue/commit/2475542679ea9407d42463149a35d63c4cf3d70a))
- **docs:** fix grid options table layout issue
  ([#2630](https://github.com/bootstrap-vue/bootstrap-vue/issues/2630))
  ([86a882f](https://github.com/bootstrap-vue/bootstrap-vue/commit/86a882f6951fe8e8c9a4b2758e39e27577c1c4c7))
- **docs:** fix issue with table docs page (closes
  [#2939](https://github.com/bootstrap-vue/bootstrap-vue/issues/2939))
  ([#2940](https://github.com/bootstrap-vue/bootstrap-vue/issues/2940))
  ([c6abfd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6abfd00fb8f78137d6ed7356d5ba47dc52d0fd2))
- **docs:** fix modal docs typo
  ([#2507](https://github.com/bootstrap-vue/bootstrap-vue/issues/2507))
  ([524db85](https://github.com/bootstrap-vue/bootstrap-vue/commit/524db85567fbb95fb769197d2379316cd79d894f))
- **docs:** fix typo ([#2864](https://github.com/bootstrap-vue/bootstrap-vue/issues/2864))
  ([ec6951d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec6951d8dbdd60a12ab68c216c48868590f3205f))
- **docs:** fix typo in modal ([#3413](https://github.com/bootstrap-vue/bootstrap-vue/issues/3413))
  ([510577f](https://github.com/bootstrap-vue/bootstrap-vue/commit/510577f1b6e87be8e02c51e9ef612a8d2928ec3e))
- **docs:** guarantee css load order
  ([#2274](https://github.com/bootstrap-vue/bootstrap-vue/issues/2274))
  ([8841f6b](https://github.com/bootstrap-vue/bootstrap-vue/commit/8841f6bc158ada1bc93c97cb4019ccdcfdb69039))
- **docs:** hading before margin
  ([#4029](https://github.com/bootstrap-vue/bootstrap-vue/issues/4029))
  ([4b8a8c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b8a8c71744bcfa36bc1fd65610e2e25a2c3d39b))
- **docs:** handle undocumented breaking changes in babel-standalone for IE11
  ([#4484](https://github.com/bootstrap-vue/bootstrap-vue/issues/4484))
  ([56f8bb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/56f8bb5af7fb7188da035210e8be28d7ae1c7bc1))
- **docs:** Improve wording in footer
  ([#2576](https://github.com/bootstrap-vue/bootstrap-vue/issues/2576))
  ([af7e36e](https://github.com/bootstrap-vue/bootstrap-vue/commit/af7e36e1ff3777ef147e879dc24f98ae02727ae2))
- **docs:** route generation + `b-progress-bar` label HTML support examples (closes
  [#3333](https://github.com/bootstrap-vue/bootstrap-vue/issues/3333))
  ([#3336](https://github.com/bootstrap-vue/bootstrap-vue/issues/3336))
  ([526f274](https://github.com/bootstrap-vue/bootstrap-vue/commit/526f274096327b9fe9ca1dbda0e3372dc1ab008b))
- **docs:** tabs lazy examples ([#4362](https://github.com/bootstrap-vue/bootstrap-vue/issues/4362))
  ([a858523](https://github.com/bootstrap-vue/bootstrap-vue/commit/a85852330a1dfa0cc33a424b6378e887a58b2881))
- **docs:** Update Bootstrap links to v4.3
  ([#2556](https://github.com/bootstrap-vue/bootstrap-vue/issues/2556))
  ([b5d5499](https://github.com/bootstrap-vue/bootstrap-vue/commit/b5d54994f667b7aba5a3deb6c027b79ac4a71651))
- **docs:** Update links to Bootstrap V4.2
  ([#2370](https://github.com/bootstrap-vue/bootstrap-vue/issues/2370))
  ([470a083](https://github.com/bootstrap-vue/bootstrap-vue/commit/470a0835c985fb1e0ec5665e3fbdbe68b8e17229))
- **docs:** update Vuelidate links
  ([#2841](https://github.com/bootstrap-vue/bootstrap-vue/issues/2841))
  ([84ed139](https://github.com/bootstrap-vue/bootstrap-vue/commit/84ed139aafda86b6e4b9609581882a4b93e6e1f9))
- **dom-utils:** check for `el.classList` existence (closes
  [#2713](https://github.com/bootstrap-vue/bootstrap-vue/issues/2713))
  ([#2714](https://github.com/bootstrap-vue/bootstrap-vue/issues/2714))
  ([4ff8b05](https://github.com/bootstrap-vue/bootstrap-vue/commit/4ff8b0561807bc47f6220e69118e321bc452b999))
- **dropdown:** Add back missing `click` events
  ([#2460](https://github.com/bootstrap-vue/bootstrap-vue/issues/2460))
  ([c5d858f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c5d858f0e2286070beac3c953977df41c9712935))
- **dropdown:** fix `no-caret` prop when dropleft (fixes
  [#2909](https://github.com/bootstrap-vue/bootstrap-vue/issues/2909))
  ([#2910](https://github.com/bootstrap-vue/bootstrap-vue/issues/2910))
  ([3bef981](https://github.com/bootstrap-vue/bootstrap-vue/commit/3bef9812f007ba4b575b7fd3936f0a19d3983856))
- **dropdown:** focus menu container before emitting shown event. Closes
  [#2520](https://github.com/bootstrap-vue/bootstrap-vue/issues/2520)
  ([#2527](https://github.com/bootstrap-vue/bootstrap-vue/issues/2527))
  ([1649c00](https://github.com/bootstrap-vue/bootstrap-vue/commit/1649c00f8473818967a01f33e973dae66df22f75))
- **dropdown:** focus-out handling when new focus comes from another `dropdown-toggle` (closes
  [#4113](https://github.com/bootstrap-vue/bootstrap-vue/issues/4113))
  ([#4139](https://github.com/bootstrap-vue/bootstrap-vue/issues/4139))
  ([9c37875](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c37875ea08a9cadf348fb42f78f576b1b3848d6))
- **dropdown:** Menu focusout close handling
  ([#2252](https://github.com/bootstrap-vue/bootstrap-vue/issues/2252))
  ([1853954](https://github.com/bootstrap-vue/bootstrap-vue/commit/1853954b0afefbc747f3b68f69ae45123393918b))
- **env:** check for undefined on process (closes
  [#2958](https://github.com/bootstrap-vue/bootstrap-vue/issues/2958))
  ([#2959](https://github.com/bootstrap-vue/bootstrap-vue/issues/2959))
  ([0c3a7b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c3a7b0211ac741f2be37056951bd9c5583d1821))
- **form control:** handle autofocus inside modal or when inside a transition
  ([#3386](https://github.com/bootstrap-vue/bootstrap-vue/issues/3386))
  ([c4a8edb](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4a8edb0e98ea6fbbac46c6445d31e76a7cd631f))
- **form-control:** remove interim class fixes from bootstrap 4.0.x (fixes
  [#1896](https://github.com/bootstrap-vue/bootstrap-vue/issues/1896))
  ([#2265](https://github.com/bootstrap-vue/bootstrap-vue/issues/2265))
  ([64bdf69](https://github.com/bootstrap-vue/bootstrap-vue/commit/64bdf69d3a920408ac6a304d4d13e82c8555b48b))
- **form-file:** `input` event loop on `reset()` in multiple mode
  ([#2289](https://github.com/bootstrap-vue/bootstrap-vue/issues/2289))
  ([f483c7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/f483c7bc49db84920b4ec5b45ea9e50bffe2d440))
- **form-file:** fix v-model update watcher
  ([#2695](https://github.com/bootstrap-vue/bootstrap-vue/issues/2695))
  ([abf9d6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/abf9d6e7b4feee6e773a58897f3d63b176bd9ea1))
- **form-group:** allow label alignment on label when not horizontal
  ([#2284](https://github.com/bootstrap-vue/bootstrap-vue/issues/2284))
  ([c306b18](https://github.com/bootstrap-vue/bootstrap-vue/commit/c306b185d81b54ef188744242a944af520599efb))
- **form-group:** don't render aria-labelledby on group when label-for provided (fixes
  [#2933](https://github.com/bootstrap-vue/bootstrap-vue/issues/2933))
  ([#2936](https://github.com/bootstrap-vue/bootstrap-vue/issues/2936))
  ([8058c03](https://github.com/bootstrap-vue/bootstrap-vue/commit/8058c03d04b80b503f88b47f8e86aee6d7cc58d7))
- **form-input:** Allow number as value type
  ([#2583](https://github.com/bootstrap-vue/bootstrap-vue/issues/2583))
  ([dfaf34e](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfaf34e0350b2ac9a170ad5f9a2654802c91af9b))
- **form-input:** allow number type for form-inputs via form-text mixin
  ([#2738](https://github.com/bootstrap-vue/bootstrap-vue/issues/2738))
  ([ec91788](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec9178840914ae008b14d9eabce4e8b223f9ad28))
- **form-input, form-textarea:** handle case where input has been removed from document (closes
  [#3498](https://github.com/bootstrap-vue/bootstrap-vue/issues/3498))
  ([#3501](https://github.com/bootstrap-vue/bootstrap-vue/issues/3501))
  ([9a62e44](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a62e4447aba0c2f07a700d62a0cb41f2e0c54b7))
- **form-radio/form-checkbox:** ensure required prop propagated in group mode (fixes
  [#2839](https://github.com/bootstrap-vue/bootstrap-vue/issues/2839))
  ([#2842](https://github.com/bootstrap-vue/bootstrap-vue/issues/2842))
  ([fc24589](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc24589841b77e010b84927ac435575a657928c2))
- **icons:** make icon transform props work with IE11 (closes
  [#4607](https://github.com/bootstrap-vue/bootstrap-vue/issues/4607))
  ([#4608](https://github.com/bootstrap-vue/bootstrap-vue/issues/4608))
  ([899779f](https://github.com/bootstrap-vue/bootstrap-vue/commit/899779f20015f719198a763136137eea01aa11ea))
- **link:** support handling multiple click event listeners (fixes
  [#2938](https://github.com/bootstrap-vue/bootstrap-vue/issues/2938))
  ([#2943](https://github.com/bootstrap-vue/bootstrap-vue/issues/2943))
  ([97e8ece](https://github.com/bootstrap-vue/bootstrap-vue/commit/97e8ecee5f03d4a486ca31ee9b7ef088ea537d15))
- **link:** use `active` class when manually placed into active state
  ([#2405](https://github.com/bootstrap-vue/bootstrap-vue/issues/2405))
  ([8f13ede](https://github.com/bootstrap-vue/bootstrap-vue/commit/8f13edecade085646b759bae7d3c0249fa07998a))
- **modal:** better backdrop clickout handling (Closes:
  [#2597](https://github.com/bootstrap-vue/bootstrap-vue/issues/2597))
  ([#2608](https://github.com/bootstrap-vue/bootstrap-vue/issues/2608))
  ([11c7524](https://github.com/bootstrap-vue/bootstrap-vue/commit/11c75244b907f32adb68bb7e8c7b91b91b6079ca))
- **modal:** ensure `ignoreBackdropClick` flag is cleared in `clickOutHandler`
  ([#3488](https://github.com/bootstrap-vue/bootstrap-vue/issues/3488))
  ([afb4680](https://github.com/bootstrap-vue/bootstrap-vue/commit/afb46801475181d2b26da177b0df7a19f04f12cf))
- **modal:** fix IE11 issue with copy/paste from modal into MS Word (fixes
  [#3457](https://github.com/bootstrap-vue/bootstrap-vue/issues/3457))
  ([#3489](https://github.com/bootstrap-vue/bootstrap-vue/issues/3489))
  ([16dbdf1](https://github.com/bootstrap-vue/bootstrap-vue/commit/16dbdf1c9916c59b03acbc0de51ac0099306ff97))
- **modal:** fix scroll to top issue when modal has `no-fade` set
  ([#4004](https://github.com/bootstrap-vue/bootstrap-vue/issues/4004))
  ([332b79f](https://github.com/bootstrap-vue/bootstrap-vue/commit/332b79fe8511c0f2b8401c34c80abfb0f4138920))
- **modal:** handle edge cases where modal is shown/hidden in rapid succession (fixes
  [#2236](https://github.com/bootstrap-vue/bootstrap-vue/issues/2236))
  ([#2270](https://github.com/bootstrap-vue/bootstrap-vue/issues/2270))
  ([e4a7bab](https://github.com/bootstrap-vue/bootstrap-vue/commit/e4a7babfb02632793bfcc97f6262752176b98b7b))
- **modal:** modal stacking position fix (Closes
  [#2677](https://github.com/bootstrap-vue/bootstrap-vue/issues/2677))
  ([#2681](https://github.com/bootstrap-vue/bootstrap-vue/issues/2681))
  ([ff4c4c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff4c4c983c562199895fa507ef4534943b6a6455))
- **modal:** prevent page scroll as modal opens
  ([#2963](https://github.com/bootstrap-vue/bootstrap-vue/issues/2963))
  ([3bf3622](https://github.com/bootstrap-vue/bootstrap-vue/commit/3bf3622842852ad96b2afe714403cdfa585d90a7))
- **modal:** properly render `*-html` props if provided (closes
  [#3491](https://github.com/bootstrap-vue/bootstrap-vue/issues/3491))
  ([#3492](https://github.com/bootstrap-vue/bootstrap-vue/issues/3492))
  ([c1ada9f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c1ada9f48e31905555e64d14df6d2f7fd7344991))
- **modal:** Show/Hide when once prevented
  ([#2275](https://github.com/bootstrap-vue/bootstrap-vue/issues/2275))
  ([9758dfd](https://github.com/bootstrap-vue/bootstrap-vue/commit/9758dfd365e0f66a0b9be690b3d07e703d839572))
- **modal:** use `safeId()` when comparing `id` received by hide/show handler (closes
  [#3389](https://github.com/bootstrap-vue/bootstrap-vue/issues/3389)
  ([#3394](https://github.com/bootstrap-vue/bootstrap-vue/issues/3394))
  ([fae3d25](https://github.com/bootstrap-vue/bootstrap-vue/commit/fae3d25092d9537ac1ce6f2addf27b85c422d622))
- **modal, tooltips, popovers:** remove no longer needed `nextTick` delay when updating content in
  transporter portal (closes [#4589](https://github.com/bootstrap-vue/bootstrap-vue/issues/4589))
  ([#4604](https://github.com/bootstrap-vue/bootstrap-vue/issues/4604))
  ([0e3e7e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e3e7e03370685367ac69949e596c9fff5c68163))
- **nav-item:** move listeners to link element
  ([#2755](https://github.com/bootstrap-vue/bootstrap-vue/issues/2755))
  ([40b19a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/40b19a73492a9870121908a019e0fe4cfbea3fcf))
- **nuxt:** correct transformAssetUrls value for `b-card-img` (closes
  [#3521](https://github.com/bootstrap-vue/bootstrap-vue/issues/3521))
  ([#3523](https://github.com/bootstrap-vue/bootstrap-vue/issues/3523))
  ([db8c6fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/db8c6fd4863e1ca01f86b59c14997ac3846b07a4))
- **nuxt:** use bundle for development mode (closes
  [#3397](https://github.com/bootstrap-vue/bootstrap-vue/issues/3397))
  ([#3399](https://github.com/bootstrap-vue/bootstrap-vue/issues/3399))
  ([f43097e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f43097ea27c4362dafe96fa8b52dac4eda39e271))
- **nuxt plugin:** fix typo with bootstrap vue css import properties
  ([#2618](https://github.com/bootstrap-vue/bootstrap-vue/issues/2618))
  ([8581090](https://github.com/bootstrap-vue/bootstrap-vue/commit/858109099f5e0b6c31ebed4eecec4164535492b2))
- **nuxt-module:** fix default inclusion of CSS files (closes
  [#2629](https://github.com/bootstrap-vue/bootstrap-vue/issues/2629))
  ([#2701](https://github.com/bootstrap-vue/bootstrap-vue/issues/2701))
  ([afbb650](https://github.com/bootstrap-vue/bootstrap-vue/commit/afbb650f94f036fce79458ddbc6ba3100bcd8cc8))
- **package.json:** prevent css and scss from being tree shaken out in docs
  ([#2271](https://github.com/bootstrap-vue/bootstrap-vue/issues/2271))
  ([44fd864](https://github.com/bootstrap-vue/bootstrap-vue/commit/44fd8643efec30484a6c136ac34eb1d48717f10b))
- **package.json:** flag most of bootstrap-vue as being side effect free
  ([#2268](https://github.com/bootstrap-vue/bootstrap-vue/issues/2268))
  ([5a77532](https://github.com/bootstrap-vue/bootstrap-vue/commit/5a7753284b2a7fe315e71340604f08f801668310))
- **pagination:** adjust aria label defaults. Fixes
  [#2508](https://github.com/bootstrap-vue/bootstrap-vue/issues/2508)
  ([#2529](https://github.com/bootstrap-vue/bootstrap-vue/issues/2529))
  ([9790dc2](https://github.com/bootstrap-vue/bootstrap-vue/commit/9790dc2b93bec614e76ef43f02007c2b819f66bc))
- **pagination:** avoid using domProps innerText (Addresses
  [#2744](https://github.com/bootstrap-vue/bootstrap-vue/issues/2744))
  ([#2757](https://github.com/bootstrap-vue/bootstrap-vue/issues/2757))
  ([d10f804](https://github.com/bootstrap-vue/bootstrap-vue/commit/d10f804e204078534bed0901f7bc7a33d93191bd))
- **pagination:** Component name in `package.json`
  ([#2541](https://github.com/bootstrap-vue/bootstrap-vue/issues/2541))
  ([331dc46](https://github.com/bootstrap-vue/bootstrap-vue/commit/331dc46842df94d223dfb4ea669f7ab55793d762))
- **pagination:** correct pagination props/slots/event docs and fix ellipsis slot
  ([#2699](https://github.com/bootstrap-vue/bootstrap-vue/issues/2699))
  ([25e04e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/25e04e166e28fae7c22511c5145715fa8ec05ba0))
- **pagination:** fx esxaped chars (fixes
  [#2479](https://github.com/bootstrap-vue/bootstrap-vue/issues/2479))
  ([1efd59c](https://github.com/bootstrap-vue/bootstrap-vue/commit/1efd59c844891a47afb8c4657a9caf710aae3dfc))
- **pagination:** set default total rows to 0 (fixes
  [#2498](https://github.com/bootstrap-vue/bootstrap-vue/issues/2498))
  ([#2526](https://github.com/bootstrap-vue/bootstrap-vue/issues/2526))
  ([c3227a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3227a6863a93b881af4629d5e668042c6afa250))
- **pagination pagination-nav:** v-model active class fix + keypress click fix (Fixes
  [#1985](https://github.com/bootstrap-vue/bootstrap-vue/issues/1985),
  [#1629](https://github.com/bootstrap-vue/bootstrap-vue/issues/1629))
  ([#2299](https://github.com/bootstrap-vue/bootstrap-vue/issues/2299))
  ([9afba6c](https://github.com/bootstrap-vue/bootstrap-vue/commit/9afba6c58be8a52242397f78217bd979ab90c186))
- **pagination-nav:** fix incorrect name in component package.json file (closes
  [#3458](https://github.com/bootstrap-vue/bootstrap-vue/issues/3458))
  ([#3459](https://github.com/bootstrap-vue/bootstrap-vue/issues/3459))
  ([ef252df](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef252df3da9a612dbbfd1b80aa469f5694089722))
- **pagination-nav:** fix race condition with clicking prev/next buttons
  ([#2834](https://github.com/bootstrap-vue/bootstrap-vue/issues/2834))
  ([42f14e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/42f14e1d8c12534c530e4d440e825139b88547c8))
- **perf:** avoid useless re-renders of component on parent update
  ([#4825](https://github.com/bootstrap-vue/bootstrap-vue/issues/4825))
  ([2cb3fe0](https://github.com/bootstrap-vue/bootstrap-vue/commit/2cb3fe0fa822a8284e023ccf71f8e451f124016a))
- **playground:** fix undefined variable error in IE 11
  ([#3606](https://github.com/bootstrap-vue/bootstrap-vue/issues/3606))
  ([b3f7053](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3f70535fe02e295ac9d44709e045b4ab6dcf8df))
- **radio/check group:** remove redundant size class from the group container (Closes
  [#2743](https://github.com/bootstrap-vue/bootstrap-vue/issues/2743))
  ([#2761](https://github.com/bootstrap-vue/bootstrap-vue/issues/2761))
  ([0639588](https://github.com/bootstrap-vue/bootstrap-vue/commit/063958890ab8161645dede0f04fec0a19b10bb2c))
- **router-link:** remove default values for active-class and exact-active-class (Fixes
  [#2387](https://github.com/bootstrap-vue/bootstrap-vue/issues/2387))
  ([#2388](https://github.com/bootstrap-vue/bootstrap-vue/issues/2388))
  ([e3e30b8](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3e30b887af155fd36ae928705813f8b90c24519))
- **table:** adjustments to sort icon positioning SCSS (closes
  [#3563](https://github.com/bootstrap-vue/bootstrap-vue/issues/3563))
  ([#3568](https://github.com/bootstrap-vue/bootstrap-vue/issues/3568))
  ([5c572e8](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c572e8dce46d71ef5bbddea70ac484f2350e198))
- **table:** allow filtering on false values and sorting date objects. Fixes
  [#2485](https://github.com/bootstrap-vue/bootstrap-vue/issues/2485)
  ([#2544](https://github.com/bootstrap-vue/bootstrap-vue/issues/2544))
  ([79315d6](https://github.com/bootstrap-vue/bootstrap-vue/commit/79315d630614f77b829eada9a5bf577e4be0e10f))
- **table:** allow string for pagination prop types
  ([#2824](https://github.com/bootstrap-vue/bootstrap-vue/issues/2824))
  ([31d2044](https://github.com/bootstrap-vue/bootstrap-vue/commit/31d20446d5a1acb6d777c941177d660070f348f1))
- **table:** better detection of active text selection during click events
  ([#3763](https://github.com/bootstrap-vue/bootstrap-vue/issues/3763))
  ([1a9c688](https://github.com/bootstrap-vue/bootstrap-vue/commit/1a9c6883ace162878d44281ad53eceabd2c3c238))
- **table:** Clear selection when data change
  ([#2267](https://github.com/bootstrap-vue/bootstrap-vue/issues/2267))
  ([e381f38](https://github.com/bootstrap-vue/bootstrap-vue/commit/e381f38e5770bb90b77f16ae8b2c0c904dfdad56))
- **table:** disable sticky header max-height on printers
  ([#4147](https://github.com/bootstrap-vue/bootstrap-vue/issues/4147))
  ([24c62c5](https://github.com/bootstrap-vue/bootstrap-vue/commit/24c62c5b5624b68b16b3729144b16c3e5ea052c1))
- **table:** don't emit row-clicked when user is selecting text (Closes
  [#2791](https://github.com/bootstrap-vue/bootstrap-vue/issues/2791))
  ([ecf0689](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecf0689f3bde07300e57640d441e53d4f2c7ac3b))
- **table:** don't use css `grid` for stacked table SCSS - for IE11 compatibility (closes
  [#3307](https://github.com/bootstrap-vue/bootstrap-vue/issues/3307))
  ([#3383](https://github.com/bootstrap-vue/bootstrap-vue/issues/3383))
  ([ce19fc7](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce19fc7caa90ff1a53cdd3bee7d27dd5eaacc292))
- **table:** ensure provider is refreshed when filter is an object (closes
  [#3428](https://github.com/bootstrap-vue/bootstrap-vue/issues/3428))
  ([#3429](https://github.com/bootstrap-vue/bootstrap-vue/issues/3429))
  ([b95c614](https://github.com/bootstrap-vue/bootstrap-vue/commit/b95c6141744b9b853a4def5e946c0a13bb177a52))
- **table:** fix broken aria-labels for sortable columns + break out code into additional mixins +
  tests ([#2884](https://github.com/bootstrap-vue/bootstrap-vue/issues/2884))
  ([ddc2006](https://github.com/bootstrap-vue/bootstrap-vue/commit/ddc20060f6e0704043fa711308350e4f5e43f74b))
- **table:** fix detection of text selection
  ([#2804](https://github.com/bootstrap-vue/bootstrap-vue/issues/2804))
  ([c7e68f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7e68f0b931e0be1aca11684cd2467bb2ff34e3e))
- **table:** fix range selection
  ([#2865](https://github.com/bootstrap-vue/bootstrap-vue/issues/2865))
  ([da49558](https://github.com/bootstrap-vue/bootstrap-vue/commit/da49558a8f05889ef09fa469575365519e46b833))
- **table:** fix SSR mismatch errors
  ([#2897](https://github.com/bootstrap-vue/bootstrap-vue/issues/2897))
  ([6c1940d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6c1940d4a9660425fc80bea55445e047844a772a))
- **tables:** add in missing Bootstrap variant class `bg-active` for dark tables
  ([#4098](https://github.com/bootstrap-vue/bootstrap-vue/issues/4098))
  ([d9900ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/d9900ab12555540987eb130b4b0300e3c810e247))
- **tables:** ensure row variant `active` (class `table-active`) takes precedence over other row
  variants (addresses [#3008](https://github.com/bootstrap-vue/bootstrap-vue/issues/3008))
  ([#4127](https://github.com/bootstrap-vue/bootstrap-vue/issues/4127))
  ([fdb8bb6](https://github.com/bootstrap-vue/bootstrap-vue/commit/fdb8bb60f4c92cbc1dc742d3e0e4fdeb609bd3cb))
- **tables:** fix issue with sticky columns when table is not responsive but has sticky headers
  (fixes [#4354](https://github.com/bootstrap-vue/bootstrap-vue/issues/4354))
  ([#4356](https://github.com/bootstrap-vue/bootstrap-vue/issues/4356))
  ([56b3958](https://github.com/bootstrap-vue/bootstrap-vue/commit/56b395899ed9c6606e5757a2fd222a8c9aecf362))
- **tabs:** add detection of when registered tabs change order
  ([#3513](https://github.com/bootstrap-vue/bootstrap-vue/issues/3513))
  ([130f8ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/130f8ffe85305a4f6eb9f38e199562edeabf72ea))
- **tabs:** Emit click on b-tab instance when button clicked. Fixes
  [#2512](https://github.com/bootstrap-vue/bootstrap-vue/issues/2512)
  ([#2530](https://github.com/bootstrap-vue/bootstrap-vue/issues/2530))
  ([8e129a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e129a31dc841e2a919febbff13e1bbbb197e18f))
- **tabs:** fix initial value handling (closes
  [#2656](https://github.com/bootstrap-vue/bootstrap-vue/issues/2656))
  ([#2661](https://github.com/bootstrap-vue/bootstrap-vue/issues/2661))
  ([2708c74](https://github.com/bootstrap-vue/bootstrap-vue/commit/2708c74780b9b290bcd95354e0b24eded63dc617))
- **tabs:** fix regression of tabs in lazy modals - use DOM query for probing tabs after mount
  (closes: [#3361](https://github.com/bootstrap-vue/bootstrap-vue/issues/3361))
  ([#3375](https://github.com/bootstrap-vue/bootstrap-vue/issues/3375))
  ([2b188a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/2b188a246ba9c6beddacb942c4a8e9d297b0fafc))
- **tabs:** fix regression with dynamically added tabs (fixes
  [#3395](https://github.com/bootstrap-vue/bootstrap-vue/issues/3395))
  ([#3396](https://github.com/bootstrap-vue/bootstrap-vue/issues/3396))
  ([f254f90](https://github.com/bootstrap-vue/bootstrap-vue/commit/f254f9002e52d6539d0ed01355f529fb4358fe04))
- **tabs:** nav item `id` and `aria-controls`
  ([#3832](https://github.com/bootstrap-vue/bootstrap-vue/issues/3832))
  ([06c6119](https://github.com/bootstrap-vue/bootstrap-vue/commit/06c61198c739aab313fb0afaf6fb0c2518522159))
- **tabs:** prevent double input event on mount, and add additional tests
  ([#2748](https://github.com/bootstrap-vue/bootstrap-vue/issues/2748))
  ([c462e0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/c462e0a7e12d8e06600036eae8bf75034507da12))
- **toast:** accessibility - prevent duplicate toast announcements for screen readers (closes
  [#3322](https://github.com/bootstrap-vue/bootstrap-vue/issues/3322))
  ([#3329](https://github.com/bootstrap-vue/bootstrap-vue/issues/3329))
  ([d44fba5](https://github.com/bootstrap-vue/bootstrap-vue/commit/d44fba5f12ee5665707984c10cdb0b291b9e744c))
- **tooltip, popover:** check `document.body` instead of `document` for IE11 support (fixes
  [#4074](https://github.com/bootstrap-vue/bootstrap-vue/issues/4074))
  ([#4075](https://github.com/bootstrap-vue/bootstrap-vue/issues/4075))
  ([1eda4fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/1eda4fe8b13690a12735404924295c8be4800e05))
- **tooltip, popover:** handle case where tooltips are applied to dropdown root elements (closes
  [#3703](https://github.com/bootstrap-vue/bootstrap-vue/issues/3703))
  ([#3704](https://github.com/bootstrap-vue/bootstrap-vue/issues/3704))
  ([39df4f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/39df4f10c7f07f471585d24b59699977ff4c1a7a))
- **tooltip, popover:** hide trigger element title attribute during show delay (fixes
  [#4114](https://github.com/bootstrap-vue/bootstrap-vue/issues/4114))
  ([#4120](https://github.com/bootstrap-vue/bootstrap-vue/issues/4120))
  ([2dd8d5a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dd8d5a6b1e70157f7127021ec160630eeb9cd59))
- **tooltips, popovers:** fix memory leak (closes
  [#4400](https://github.com/bootstrap-vue/bootstrap-vue/issues/4400))
  ([#4401](https://github.com/bootstrap-vue/bootstrap-vue/issues/4401))
  ([c71352d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c71352d674347e5e2d72fe8b82334fc87a4ffd8c))
- **types:** add BInputGroup to TypeScript definitions
  ([#3487](https://github.com/bootstrap-vue/bootstrap-vue/issues/3487))
  ([b4ac081](https://github.com/bootstrap-vue/bootstrap-vue/commit/b4ac0819825c542039347b009d66e02a28a8939e))
- **types:** adjust typing of BvComponent and BvPlugin (closes
  [#3390](https://github.com/bootstrap-vue/bootstrap-vue/issues/3390))
  ([#3391](https://github.com/bootstrap-vue/bootstrap-vue/issues/3391))
  ([6f0f3fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f0f3fd0d49997b3cbd9848ad4233b9272f3c1e0))
- **types:** BCardSubTitle component declared export name
  ([#4229](https://github.com/bootstrap-vue/bootstrap-vue/issues/4229))
  ([9f216df](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f216df0bc7bc97a96e432ea22cabd917bf56ed7))
- **types:** update table field definition types to include sticky column (fixes
  [#5263](https://github.com/bootstrap-vue/bootstrap-vue/issues/5263))
  ([#5265](https://github.com/bootstrap-vue/bootstrap-vue/issues/5265))
  ([20eb3ac](https://github.com/bootstrap-vue/bootstrap-vue/commit/20eb3ac9e22ddbcc41d1f1aa923871007abe0dc0))
- **util/html:** ensure argument is a string (Closes
  [#2770](https://github.com/bootstrap-vue/bootstrap-vue/issues/2770))
  ([#2775](https://github.com/bootstrap-vue/bootstrap-vue/issues/2775))
  ([356247f](https://github.com/bootstrap-vue/bootstrap-vue/commit/356247fd27eef618d788536db9c8348efd291dba))
- **util/loose-equal:** handle comparing sparse arrays
  ([#2813](https://github.com/bootstrap-vue/bootstrap-vue/issues/2813))
  ([6ac8ade](https://github.com/bootstrap-vue/bootstrap-vue/commit/6ac8ade1edea9b95ffc20ff2b7226d7d9fbeeaed))
- **utils:** add back array notation support to `get()` util
  ([#2689](https://github.com/bootstrap-vue/bootstrap-vue/issues/2689))
  ([9e824a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e824a510d0b8a3022a4e926f870e914d7072621))
- **utils:** make `looseEqual()` util compliant with Vue.js spec
  ([#2651](https://github.com/bootstrap-vue/bootstrap-vue/issues/2651))
  ([1b6a994](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b6a994d4effa29a86d908aad0b96f9a6695ec31))
- **utils:** Make `looseEqual()` util handle File comparison correctly
  ([#2640](https://github.com/bootstrap-vue/bootstrap-vue/issues/2640))
  ([401d3e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/401d3e974249c404df2d80282ccecae71baf57a7))
- **utils/dom:** update closest routine to support SVG
  ([#2901](https://github.com/bootstrap-vue/bootstrap-vue/issues/2901))
  ([9d4408d](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d4408d6bebcc2859b8fa1c383c59b692e126099))
- **utils/get:** handle case where passed object is undefined (Fixes
  [#2623](https://github.com/bootstrap-vue/bootstrap-vue/issues/2623))
  ([#2624](https://github.com/bootstrap-vue/bootstrap-vue/issues/2624))
  ([eb07b19](https://github.com/bootstrap-vue/bootstrap-vue/commit/eb07b196f3762d5e441b10d3e24d563544d014f8))
- **utils/get:** handle cases when field value is not array or object (closes
  [#2807](https://github.com/bootstrap-vue/bootstrap-vue/issues/2807))
  ([#2808](https://github.com/bootstrap-vue/bootstrap-vue/issues/2808))
  ([c656fa3](https://github.com/bootstrap-vue/bootstrap-vue/commit/c656fa31f4983e991a2e8d0d3c19e52bcfbc032b))
- **utils/get:** handle edge case with inherited object getters (fixes
  [#3463](https://github.com/bootstrap-vue/bootstrap-vue/issues/3463))
  ([#3465](https://github.com/bootstrap-vue/bootstrap-vue/issues/3465))
  ([e2c8cb1](https://github.com/bootstrap-vue/bootstrap-vue/commit/e2c8cb126619e158a3263b1781598c2255190b34))
- **utisl/observeDom:** make sure to check for browser enviroment
  ([#2838](https://github.com/bootstrap-vue/bootstrap-vue/issues/2838))
  ([8471f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/8471f317785ce6f98b3fd0ce1218d66238fe00f5))
- **v-b-toggle:** don't override `role` if element has a `role` assigned
  ([#3889](https://github.com/bootstrap-vue/bootstrap-vue/issues/3889))
  ([5d155ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/5d155badd671cc60f1f6ab3c294e713ebf7e9915))
- fix Html casing for props ([#2594](https://github.com/bootstrap-vue/bootstrap-vue/issues/2594))
  ([3772bf5](https://github.com/bootstrap-vue/bootstrap-vue/commit/3772bf5b09de8b251c469b52e9f87a6ade0b2bca))
- handle nested form options normalization
  ([#5247](https://github.com/bootstrap-vue/bootstrap-vue/issues/5247))
  ([0c57ffe](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c57ffe31c946475498fa3554b8b4aba4e9d19df))
- nested form options normalization
  ([bea0393](https://github.com/bootstrap-vue/bootstrap-vue/commit/bea039386518c0b0a77bed46b13330c6840b7daa))
- remove underscore form variable and method names
  ([#3352](https://github.com/bootstrap-vue/bootstrap-vue/issues/3352))
  ([bcd0a2f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bcd0a2f6bdf995e56aa0d62c395caf6922424502))
- temporary fix for validation icon positioning (Closes
  [#2599](https://github.com/bootstrap-vue/bootstrap-vue/issues/2599))
  ([#2607](https://github.com/bootstrap-vue/bootstrap-vue/issues/2607))
  ([7168989](https://github.com/bootstrap-vue/bootstrap-vue/commit/71689892576de559c90a5fa9a4a9b80b9371ced3))
- use `installFactory` for main `BootstrapVue` plugin (closes
  [#3338](https://github.com/bootstrap-vue/bootstrap-vue/issues/3338))
  ([#3340](https://github.com/bootstrap-vue/bootstrap-vue/issues/3340))
  ([4c0c445](https://github.com/bootstrap-vue/bootstrap-vue/commit/4c0c4451430cb9e5aec162d1cc30f75e0c6c3dd5))
- **$bvToast,$bvModal:** ensure values passed to slots are arrays for Vue.js 2.5.x compatibility
  (closes [#3174](https://github.com/bootstrap-vue/bootstrap-vue/issues/3174))
  ([#3252](https://github.com/bootstrap-vue/bootstrap-vue/issues/3252))
  ([f46b5d8](https://github.com/bootstrap-vue/bootstrap-vue/commit/f46b5d8eba9936b0c1c9522afb271b111291b432))
- **b-input-group:** fix issue with slots (closes
  [#3284](https://github.com/bootstrap-vue/bootstrap-vue/issues/3284))
  ([#3288](https://github.com/bootstrap-vue/bootstrap-vue/issues/3288))
  ([5639e8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/5639e8f4e6070c0f5001dbc43e3e1e2de9772503))
- **b-input-group:** use same input-group-prepend/append for both props and slots
  ([#3321](https://github.com/bootstrap-vue/bootstrap-vue/issues/3321))
  ([fb7386e](https://github.com/bootstrap-vue/bootstrap-vue/commit/fb7386e020f6d710c665eb8895d490489c5af278))
- **b-link:** ensure href prop is not passed to router-links (fixes
  [#3066](https://github.com/bootstrap-vue/bootstrap-vue/issues/3066))
  ([#3084](https://github.com/bootstrap-vue/bootstrap-vue/issues/3084))
  ([f679c11](https://github.com/bootstrap-vue/bootstrap-vue/commit/f679c118a91615bd2e76047ffbdfff672f0152d7))
- **b-modal:** delay initially open modal via nextTick when using v-model or visible prop
  ([#3320](https://github.com/bootstrap-vue/bootstrap-vue/issues/3320))
  ([6f3010a](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f3010a63f6d79bfe0318187b0f52870c58befc7)),
  closes
  [/github.com/bootstrap-vue/bootstrap-vue/issues/3312#issuecomment-493389988](https://github.com/bootstrap-vue//github.com/bootstrap-vue/bootstrap-vue/issues/3312/issues/issuecomment-493389988)
- **b-nav-item-dropdown:** fix disabled state (fixes
  [#3264](https://github.com/bootstrap-vue/bootstrap-vue/issues/3264))
  ([#3266](https://github.com/bootstrap-vue/bootstrap-vue/issues/3266))
  ([10d4c4d](https://github.com/bootstrap-vue/bootstrap-vue/commit/10d4c4df13bfa27fefe373ff561056b707610889))
- **b-toaster:** CSS fix for IE11 support (fixes
  [#3327](https://github.com/bootstrap-vue/bootstrap-vue/issues/3327))
  ([#3328](https://github.com/bootstrap-vue/bootstrap-vue/issues/3328))
  ([88b1cfd](https://github.com/bootstrap-vue/bootstrap-vue/commit/88b1cfdbe26660d878af0f1936a281b9712525a0))
- **breadcrumb-item:** remove `role="presentation"`
  ([#2991](https://github.com/bootstrap-vue/bootstrap-vue/issues/2991))
  ([e84c4a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/e84c4a76468e6faabeafb08cbe0789362c288e6a))
- **build:** enable babel option to interop default (fixes
  [#3038](https://github.com/bootstrap-vue/bootstrap-vue/issues/3038))
  ([#3046](https://github.com/bootstrap-vue/bootstrap-vue/issues/3046))
  ([4e981c2](https://github.com/bootstrap-vue/bootstrap-vue/commit/4e981c2a4174197983477526a78564114e728ad6))
- **col, form-group:** implement self overwriting lazy props getter (fixes:
  [#3080](https://github.com/bootstrap-vue/bootstrap-vue/issues/3080))
  ([#3125](https://github.com/bootstrap-vue/bootstrap-vue/issues/3125))
  ([92756bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/92756bd0ad59133a9aecaa4231158ce47e81a29d))
- **collapse:** is-nav link click behaviour - check if collapse has `display: block !important`
  before attempting to close collapse
  ([#3199](https://github.com/bootstrap-vue/bootstrap-vue/issues/3199))
  ([b0729cc](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0729ccd0f38edad354fb85e9ad9403f737a0a3b))
- **docs:** add missing close tags for `<b-icon>` components
  ([#4680](https://github.com/bootstrap-vue/bootstrap-vue/issues/4680))
  ([0d86940](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d86940d67520f418c966a7c8879898db0b899e0))
- **docs:** correct Vuelidate validation example and some minor tweaks
  ([#3332](https://github.com/bootstrap-vue/bootstrap-vue/issues/3332))
  ([d5c22a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/d5c22a8cef00bba7f383e8dd03a23caab2d45514))
- **docs:** fix component plugin's included plugins and directives
  ([#2966](https://github.com/bootstrap-vue/bootstrap-vue/issues/2966))
  ([cbf24c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbf24c39a71501802b49a370663b1e55ee863deb))
- **docs:** fix polyfill for IE 11
  ([#3114](https://github.com/bootstrap-vue/bootstrap-vue/issues/3114))
  ([298f733](https://github.com/bootstrap-vue/bootstrap-vue/commit/298f73388c94abec3430a03994cadb70ac0d3159))
- **docs:** improve <b-modal> prevent closing example
  ([#3054](https://github.com/bootstrap-vue/bootstrap-vue/issues/3054))
  ([f609316](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6093165a3b48a567519b5f9385c4e0264552e78))
- **docs:** improve code highlighting + table styles
  ([#3078](https://github.com/bootstrap-vue/bootstrap-vue/issues/3078))
  ([d4b9895](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4b98957133106b636016a60966b093d26afb488))
- **docs:** improve nav social links alignment
  ([#3122](https://github.com/bootstrap-vue/bootstrap-vue/issues/3122))
  ([d37500e](https://github.com/bootstrap-vue/bootstrap-vue/commit/d37500e9a9bf9db9405e9d2b44900387bde9c3c0))
- **docs:** info modal in complete <b-table> example (closes
  [#3144](https://github.com/bootstrap-vue/bootstrap-vue/issues/3144))
  ([#3145](https://github.com/bootstrap-vue/bootstrap-vue/issues/3145))
  ([9dfe0bf](https://github.com/bootstrap-vue/bootstrap-vue/commit/9dfe0bfaed704c7939c002e86ef3d3ac409ed1f8))
- **docs:** minor tweaks ([#3121](https://github.com/bootstrap-vue/bootstrap-vue/issues/3121))
  ([1917f1b](https://github.com/bootstrap-vue/bootstrap-vue/commit/1917f1bda1dcda9e3af2e0a9d5dcfe414bf6d361))
- **docs:** overall improvements
  ([#3129](https://github.com/bootstrap-vue/bootstrap-vue/issues/3129))
  ([be53376](https://github.com/bootstrap-vue/bootstrap-vue/commit/be533769c53f6e1a215abc83b3c10f1f5f985728))
- **docs:** typo in ´<strong>´ tags
  ([#3163](https://github.com/bootstrap-vue/bootstrap-vue/issues/3163))
  ([e465ae9](https://github.com/bootstrap-vue/bootstrap-vue/commit/e465ae96c05c951a45924db06cb2e0dadca09d4d))
- **docs:** unify heading casing
  ([#3101](https://github.com/bootstrap-vue/bootstrap-vue/issues/3101))
  ([649a845](https://github.com/bootstrap-vue/bootstrap-vue/commit/649a845a2a182c7aa0d89ec2603722ca94448da2))
- **docs:** use regex to normalize URL with better browser support
  ([#3147](https://github.com/bootstrap-vue/bootstrap-vue/issues/3147))
  ([c3bd004](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3bd004eea9bb15fca06c2ac5787767b06657bdc))
- **events:** correct `capture` value of `EVENT_OPTIONS_NO_CAPTURE`
  ([#4763](https://github.com/bootstrap-vue/bootstrap-vue/issues/4763))
  ([e9a99e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9a99e6e2cf080ae5d9783229b93fd2eaeedf436))
- **form-input:** properly handle out-of-sync values (closes
  [#2657](https://github.com/bootstrap-vue/bootstrap-vue/issues/2657))
  ([#3172](https://github.com/bootstrap-vue/bootstrap-vue/issues/3172))
  ([976f9c1](https://github.com/bootstrap-vue/bootstrap-vue/commit/976f9c1bfbd4443206e1d81c2664f1cf4a312f56))
- **form-textarea:** improve auto-row height calculation timing (closes
  [#3103](https://github.com/bootstrap-vue/bootstrap-vue/issues/3103))
  ([#3105](https://github.com/bootstrap-vue/bootstrap-vue/issues/3105))
  ([dfc662e](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfc662ed2b4a845186d87e5849c034de43326fdf))
- **form-textarea:** improved computedHeight calculation when in auto resize mode
  ([#3012](https://github.com/bootstrap-vue/bootstrap-vue/issues/3012))
  ([0043b92](https://github.com/bootstrap-vue/bootstrap-vue/commit/0043b9263298999ec09c37a79a2c9af088c97278))
- **modal:** clear internal return_focus after modal closes (fixes
  [#3067](https://github.com/bootstrap-vue/bootstrap-vue/issues/3067))
  ([#3068](https://github.com/bootstrap-vue/bootstrap-vue/issues/3068))
  ([971556f](https://github.com/bootstrap-vue/bootstrap-vue/commit/971556f17342fb11635fd74f0da6fabaadbcc688))
- **modal:** ensure that v-model is updated when show or hide is canceled
  ([#3131](https://github.com/bootstrap-vue/bootstrap-vue/issues/3131))
  ([6726a33](https://github.com/bootstrap-vue/bootstrap-vue/commit/6726a33a765af6aba148ea7a434f5e2b71a662fb))
- **modal:** exclude document.body when determining return focus element
  ([#3228](https://github.com/bootstrap-vue/bootstrap-vue/issues/3228))
  ([092ab2d](https://github.com/bootstrap-vue/bootstrap-vue/commit/092ab2decbd76e98a90b1f71a509bd29c68f03f8))
- **modal:** fix close on click-out for IE11
  ([#3117](https://github.com/bootstrap-vue/bootstrap-vue/issues/3117))
  ([9b09e52](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b09e52567aedbfe17d68cd27470b886b1c5d350))
- **modal:** handle HMR when defining property on Vue prototype
  ([#3123](https://github.com/bootstrap-vue/bootstrap-vue/issues/3123))
  ([a4e7f21](https://github.com/bootstrap-vue/bootstrap-vue/commit/a4e7f2188f0fbcc8189290fbb125f6572cceb024))
- **modal:** prevent close on backdrop when click initiated inside modal content (fixes
  [#3025](https://github.com/bootstrap-vue/bootstrap-vue/issues/3025))
  ([#3029](https://github.com/bootstrap-vue/bootstrap-vue/issues/3029))
  ([ad57e8c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ad57e8cfb7a3e88d92a3f1b43e33c495b0d0eb84))
- **modal:** prevent duplicate key when sending to portal-target
  ([#3235](https://github.com/bootstrap-vue/bootstrap-vue/issues/3235))
  ([5204ad7](https://github.com/bootstrap-vue/bootstrap-vue/commit/5204ad795d5005db14780330a195f8c13e6dc070))
- **modal:** return focus edge case bug in IE11 (fixes
  [#3206](https://github.com/bootstrap-vue/bootstrap-vue/issues/3206))
  ([#3207](https://github.com/bootstrap-vue/bootstrap-vue/issues/3207))
  ([7ef36c2](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ef36c219f7ed493906be5c86f2da53521871c47))
- **modal:** stacked modal z-index calculations (closes
  [#3015](https://github.com/bootstrap-vue/bootstrap-vue/issues/3015))
  ([#3017](https://github.com/bootstrap-vue/bootstrap-vue/issues/3017))
  ([891e8cc](https://github.com/bootstrap-vue/bootstrap-vue/commit/891e8cc21937b9b96204d4f5c012e5e8600adc35))
- **nuxt module:** ensure that css and transpile are arrays (fixes:
  [#3141](https://github.com/bootstrap-vue/bootstrap-vue/issues/3141))
  ([#3142](https://github.com/bootstrap-vue/bootstrap-vue/issues/3142))
  ([239da77](https://github.com/bootstrap-vue/bootstrap-vue/commit/239da7775f2a3de0b0aec393eae9d52e60239fd1))
- **nuxt module:** remove unnecessary export statements
  ([#4624](https://github.com/bootstrap-vue/bootstrap-vue/issues/4624))
  ([27f066c](https://github.com/bootstrap-vue/bootstrap-vue/commit/27f066cfa07ee311fe1e312d9a9ebd0eb76750c7))
- **pagination:** reset to page 1 when total-rows or per-page changes (closes
  [#2987](https://github.com/bootstrap-vue/bootstrap-vue/issues/2987))
  ([#2993](https://github.com/bootstrap-vue/bootstrap-vue/issues/2993))
  ([df2e77a](https://github.com/bootstrap-vue/bootstrap-vue/commit/df2e77ac1613324e79baa73ae90f893eb059c4f1))
- **pagination:** use unicode escape sequence for default bookend button text
  ([#3186](https://github.com/bootstrap-vue/bootstrap-vue/issues/3186))
  ([dfb6af7](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfb6af73c4bdbf7815ea82ed1077c07d8e2962e4))
- **pagination-nav:** better current page detection in IE
  ([#3006](https://github.com/bootstrap-vue/bootstrap-vue/issues/3006))
  ([f742aa9](https://github.com/bootstrap-vue/bootstrap-vue/commit/f742aa948108c72d67d688925410ac98504eb77a))
- **tab:** don't use `aria-expanded` on the panel
  ([#3143](https://github.com/bootstrap-vue/bootstrap-vue/issues/3143))
  ([381eacf](https://github.com/bootstrap-vue/bootstrap-vue/commit/381eacf170f88e4e2169ef855d49ad91413bb0e2))
- **table:** fix bad copy paste
  ([#5067](https://github.com/bootstrap-vue/bootstrap-vue/issues/5067))
  ([874dca2](https://github.com/bootstrap-vue/bootstrap-vue/commit/874dca2c8c385fecf7cec76e6cfa44eda9fcabf4))
- **table:** prevent hover style on busy/empty row (closes
  [#3079](https://github.com/bootstrap-vue/bootstrap-vue/issues/3079))
  ([#3086](https://github.com/bootstrap-vue/bootstrap-vue/issues/3086))
  ([c53ffd4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c53ffd4fab943006b000d706683ea8f5653afe4d))
- **toast:** use appendChild instead of append for IE 11 support
  ([#3160](https://github.com/bootstrap-vue/bootstrap-vue/issues/3160))
  ([be118a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/be118a98727f88e8771ba6c883018e3b154d452b))
- **toaster:** let on-demand toasts know the toaster has been destroyed
  ([#3130](https://github.com/bootstrap-vue/bootstrap-vue/issues/3130))
  ([0b44e4d](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b44e4d043a0dce30d95e2e53b71cd0d94bf5525))
- **tooltip/popover:** prevent double show/shown event emits when .sync modifier used (fixes
  [#1637](https://github.com/bootstrap-vue/bootstrap-vue/issues/1637))
  ([#3001](https://github.com/bootstrap-vue/bootstrap-vue/issues/3001))
  ([0d3599a](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d3599a83c6bef5f2262763550daa1b66095abee))
- **types:** fix msxBoxConfirm typo
  ([#3280](https://github.com/bootstrap-vue/bootstrap-vue/issues/3280))
  ([8027e5a](https://github.com/bootstrap-vue/bootstrap-vue/commit/8027e5ab6c4d65e53b727355caaeed2b18f5563f))
- **typescript:** replaced invalid `mixed` keyword with `any` (fixes
  [#3041](https://github.com/bootstrap-vue/bootstrap-vue/issues/3041))
  ([#3043](https://github.com/bootstrap-vue/bootstrap-vue/issues/3043))
  ([36e8246](https://github.com/bootstrap-vue/bootstrap-vue/commit/36e824626454ecb7869b212d0cb69e92937074ff))
- **utils:** improve `dom`, `env`, `inspect` and test utils
  ([#3085](https://github.com/bootstrap-vue/bootstrap-vue/issues/3085))
  ([bd85049](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd85049b67836c0f451d0fd27de7fdd257e6d535))
- **utils/get:** handle case when nested value is falsy
  ([#2982](https://github.com/bootstrap-vue/bootstrap-vue/issues/2982))
  ([40f6cb7](https://github.com/bootstrap-vue/bootstrap-vue/commit/40f6cb7c11d561ce035d23bde88f591891dcd057))
- **v-b-toggle/b-collapse:** ensure toggle remains in sync with collapse (Closes
  [#3020](https://github.com/bootstrap-vue/bootstrap-vue/issues/3020))
  ([#3021](https://github.com/bootstrap-vue/bootstrap-vue/issues/3021))
  ([6b36d0d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b36d0d088789cf8439498a890881d45d572d20c))
- use stable nuxt opencollective
  ([#1885](https://github.com/bootstrap-vue/bootstrap-vue/issues/1885))
  ([876f4a1](https://github.com/bootstrap-vue/bootstrap-vue/commit/876f4a1a4f46cc58f9d20788758c7ec03c576a3c))
- **table:** generate TR key using serialized item or primary key if provided (fixes:
  [#2410](https://github.com/bootstrap-vue/bootstrap-vue/issues/2410))
  ([#2416](https://github.com/bootstrap-vue/bootstrap-vue/issues/2416))
  ([6e22d99](https://github.com/bootstrap-vue/bootstrap-vue/commit/6e22d99bb3ae50674abaace337270f65a5cbf6b9))
- **table:** selectable range mode update and minor fixes
  ([#2326](https://github.com/bootstrap-vue/bootstrap-vue/issues/2326))
  ([ef281d1](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef281d12dbb3a6d3ff56b621f5712f0d914495f9))
- **tabs:** `tabIndex` prop type
  ([#2459](https://github.com/bootstrap-vue/bootstrap-vue/issues/2459))
  ([05ef65a](https://github.com/bootstrap-vue/bootstrap-vue/commit/05ef65ad1706c44b4aa3a093719da7040eaad5fa))
- **tabs:** Fix tab titleLinkClass and titleItemClass handling
  ([#2448](https://github.com/bootstrap-vue/bootstrap-vue/issues/2448))
  ([36400f5](https://github.com/bootstrap-vue/bootstrap-vue/commit/36400f5f50ea762b7ae0f8c62044cf5d6ec5f238))
- **tabs:** various fixes and improvements (Fixes:
  [#2327](https://github.com/bootstrap-vue/bootstrap-vue/issues/2327),
  [#2148](https://github.com/bootstrap-vue/bootstrap-vue/issues/2148). Closes:
  [#2403](https://github.com/bootstrap-vue/bootstrap-vue/issues/2403),
  [#2180](https://github.com/bootstrap-vue/bootstrap-vue/issues/2180))
  ([#2442](https://github.com/bootstrap-vue/bootstrap-vue/issues/2442))
  ([de11a8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/de11a8f5e9999cbd98909b9ae3a9d58b556ee587))
- **types:** add missing declaration for `b-form-timepicker` (closes
  [#5035](https://github.com/bootstrap-vue/bootstrap-vue/issues/5035))
  ([#5036](https://github.com/bootstrap-vue/bootstrap-vue/issues/5036))
  ([ae84118](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae841184dc3037b5d6f365311cc668bccb0e85da))
- **types:** add missing declarations for `b-form-select-option` & `b-form-select-option-group`
  ([#4595](https://github.com/bootstrap-vue/bootstrap-vue/issues/4595))
  ([8d60832](https://github.com/bootstrap-vue/bootstrap-vue/commit/8d60832d38e74231a4bda15aa045b84aae97d2ed))
- **typescript:** include named export BootstrapVue in declaration file
  ([#4590](https://github.com/bootstrap-vue/bootstrap-vue/issues/4590))
  ([603307a](https://github.com/bootstrap-vue/bootstrap-vue/commit/603307aeccf6141b94eff2186baee4ec43439033))
- **utils:** correct `identity` spelling error
  ([#4579](https://github.com/bootstrap-vue/bootstrap-vue/issues/4579))
  ([7fed191](https://github.com/bootstrap-vue/bootstrap-vue/commit/7fed1911d6d9f7eae81526010483c71e1679e770))
- **utils:** pass all Array/Object util shortcuts as functions, for handling late loaded polyfills
  ([#4647](https://github.com/bootstrap-vue/bootstrap-vue/issues/4647))
  ([f584425](https://github.com/bootstrap-vue/bootstrap-vue/commit/f5844256a03d2f4b8006900419acfa2c5e3803c3)),
  closes
  [/github.com/bootstrap-vue/bootstrap-vue/pull/3641#issuecomment-575884289](https://github.com/bootstrap-vue//github.com/bootstrap-vue/bootstrap-vue/pull/3641/issues/issuecomment-575884289)
- **v-b-modal:** bind to inner link or button for dropdown items or nav items (fixes
  [#4149](https://github.com/bootstrap-vue/bootstrap-vue/issues/4149))
  ([#4187](https://github.com/bootstrap-vue/bootstrap-vue/issues/4187))
  ([5c28bd2](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c28bd2fe22a14e5b30b3e955a0eaed5acf62ee5))
- **v-b-modal:** ensure trigger element is keyboard accessible if not a link or button, for A11Y
  ([#4365](https://github.com/bootstrap-vue/bootstrap-vue/issues/4365))
  ([f54ca29](https://github.com/bootstrap-vue/bootstrap-vue/commit/f54ca2969a38f75a69d58a8eedeac4f0bd905eca))
- **v-b-modal:** only unbind/rebind if trigger element or modal ID changes (closes
  [#4669](https://github.com/bootstrap-vue/bootstrap-vue/issues/4669))
  ([#4672](https://github.com/bootstrap-vue/bootstrap-vue/issues/4672))
  ([e53a05d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e53a05d960a9de0ca9636ee31e0197e7e554ddbc))
- **v-b-modal:** open modal using `ENTER` key on non-button elements for A11Y
  ([#4364](https://github.com/bootstrap-vue/bootstrap-vue/issues/4364))
  ([0d27d7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d27d7be2677f1fdada7c91c5b9f58a216a3de4e))
- **v-b-tooltip, v-b-popover:** add missing `disabled` config option
  ([#4057](https://github.com/bootstrap-vue/bootstrap-vue/issues/4057))
  ([f488dc1](https://github.com/bootstrap-vue/bootstrap-vue/commit/f488dc1e6c8aab7ba43fce9805f6f5bccd6419c3))
- **v-b-tooltip, v-b-popover:** don't show if no title/content provided (closes
  [#4064](https://github.com/bootstrap-vue/bootstrap-vue/issues/4064))
  ([#4076](https://github.com/bootstrap-vue/bootstrap-vue/issues/4076))
  ([0b7de29](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b7de2992b42c094541b574b4bf24bcf10abe22e))
- **v-b-tooltip, v-b-popover:** ensure reference to trigger element is passed to title/content
  function (fixes [#4331](https://github.com/bootstrap-vue/bootstrap-vue/issues/4331))
  ([#4332](https://github.com/bootstrap-vue/bootstrap-vue/issues/4332))
  ([ea0cbda](https://github.com/bootstrap-vue/bootstrap-vue/commit/ea0cbda18b58a619c1ddd100d3b48905f88bf926))
- **v-b-visible:** fix type error in `componentUpdated` hook + minor docs update/fixes
  ([#4327](https://github.com/bootstrap-vue/bootstrap-vue/issues/4327))
  ([5f3ba9e](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f3ba9e7a22c236f7f8023a99dc0116e1b382dc8))
- **web-types:** update web-types code generation to match schema
  ([#4271](https://github.com/bootstrap-vue/bootstrap-vue/issues/4271))
  ([009431e](https://github.com/bootstrap-vue/bootstrap-vue/commit/009431ee2f0769dc22a47f7f15ee834621e5b73c))
- relax prop type checks to prevent vue warns
  ([835eccf](https://github.com/bootstrap-vue/bootstrap-vue/commit/835eccfe92de90a56a06531006245b53a43ec5b8))
- **alert:** import button-close in alert with a name matching tag.
  ([#1523](https://github.com/bootstrap-vue/bootstrap-vue/issues/1523)) fixes
  [#1522](https://github.com/bootstrap-vue/bootstrap-vue/issues/1522).
  ([51b527f](https://github.com/bootstrap-vue/bootstrap-vue/commit/51b527f83c0577f62fe2e0035e15aaa2d5fb8bac))
- **alert:** target custom transition CSS to the alert component
  ([#2205](https://github.com/bootstrap-vue/bootstrap-vue/issues/2205))
  ([0a48268](https://github.com/bootstrap-vue/bootstrap-vue/commit/0a4826852a35e3d257f39883cc5dfb44d0363ad0))
- **build:** don't exclude lodash.get
  ([543c3c2](https://github.com/bootstrap-vue/bootstrap-vue/commit/543c3c2f9aeccffb03c571aeea93333774243ab3))
- **card:** duplicate header and footer slots with no-body
  ([#1713](https://github.com/bootstrap-vue/bootstrap-vue/issues/1713),
  [#1680](https://github.com/bootstrap-vue/bootstrap-vue/issues/1680))
  ([2bd0e71](https://github.com/bootstrap-vue/bootstrap-vue/commit/2bd0e713b877e1ced7fa5caba418e9b88c12aa1f))
- **card:** fix card and sub component render issues. Fixes
  [#2062](https://github.com/bootstrap-vue/bootstrap-vue/issues/2062)
  ([#2125](https://github.com/bootstrap-vue/bootstrap-vue/issues/2125))
  ([430371f](https://github.com/bootstrap-vue/bootstrap-vue/commit/430371ff1ce5933b041673e31bd6ba75605eb673))
- **card:** pass children instead of default prop to sub-components
  ([63b35e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/63b35e3429b353d8ac1af01fd3e65383cc7baf13))
- **checkbox,radio:** update HTML markup for BS4
  ([#1539](https://github.com/bootstrap-vue/bootstrap-vue/issues/1539))
  ([ccfb5b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/ccfb5b1f45cc5ac4c056070f4e78ef098411729c))
- **collapse:** when is-nav, do better checking of click events (Fixes
  [#2222](https://github.com/bootstrap-vue/bootstrap-vue/issues/2222))
  ([#2225](https://github.com/bootstrap-vue/bootstrap-vue/issues/2225))
  ([8b96e1e](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b96e1efdd9d3ea03ca707eec17de16423afc19c))
- **collapse/toggle:** "collapsed" class cleared when component updated
  ([#2102](https://github.com/bootstrap-vue/bootstrap-vue/issues/2102))
  ([6d33cae](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d33caee025a6ba08b1ce49cbc357c2111b52e56)),
  closes [#1798](https://github.com/bootstrap-vue/bootstrap-vue/issues/1798)
- **contributing:** Improve the commit guidelines
  ([c506280](https://github.com/bootstrap-vue/bootstrap-vue/commit/c506280af9acffb1d8978890e7efecca36042212))
- **dependencies:** replace opencollective with opencollective-postintall
  ([#2067](https://github.com/bootstrap-vue/bootstrap-vue/issues/2067))
  ([fa26882](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa26882686166a74621330bf658c0b9447a93590))
- **docs:** Button - typo ([#1962](https://github.com/bootstrap-vue/bootstrap-vue/issues/1962))
  ([dcbfcf9](https://github.com/bootstrap-vue/bootstrap-vue/commit/dcbfcf9a2de47f2c70486461e0716f9f79f03501))
- **docs:** change b-input-group attribute 'left' to 'prepend'
  ([#2017](https://github.com/bootstrap-vue/bootstrap-vue/issues/2017))
  ([d471502](https://github.com/bootstrap-vue/bootstrap-vue/commit/d471502e8e96b1bdc6581360c1960382b676adf3))
- **docs:** Collapse - typo fix
  ([#1964](https://github.com/bootstrap-vue/bootstrap-vue/issues/1964))
  ([becaa98](https://github.com/bootstrap-vue/bootstrap-vue/commit/becaa98558c56136a4cc3742708e5983f0376747))
- **docs:** Embed - Typos ([#1965](https://github.com/bootstrap-vue/bootstrap-vue/issues/1965))
  ([ae7101e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae7101edfcaf566ed648d7d534b85ff42c3a3a0a))
- **docs:** Fix broken examples
  ([1d599a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d599a56acd9003e7a1f2f9d4483e5dc1325cb91))
- **docs:** Fix console errors and improve `play` directive
  ([#2176](https://github.com/bootstrap-vue/bootstrap-vue/issues/2176))
  ([cc02130](https://github.com/bootstrap-vue/bootstrap-vue/commit/cc02130f6d45bdb391d6c34a79c435b1bb0f08ba))
- **docs:** Fix duplicate keys in events table
  ([#1786](https://github.com/bootstrap-vue/bootstrap-vue/issues/1786))
  ([fa60d56](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa60d56e812aedfa3506199dbaf7826cc521be60))
- **docs:** fix issue with playground export button and improved error catching
  ([#2197](https://github.com/bootstrap-vue/bootstrap-vue/issues/2197))
  ([c69ffbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/c69ffbc2f2f66f1a8a3df38fc0fe0c098450dc1d))
- **docs:** fix playground hang issues. fixes
  [#1843](https://github.com/bootstrap-vue/bootstrap-vue/issues/1843)
  ([#2177](https://github.com/bootstrap-vue/bootstrap-vue/issues/2177))
  ([5bdc2e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bdc2e63c615f653415a24b513b8ef1ec27a61df))
- **docs:** fix table refresh event name
  ([#1692](https://github.com/bootstrap-vue/bootstrap-vue/issues/1692))
  ([01e223c](https://github.com/bootstrap-vue/bootstrap-vue/commit/01e223caaae965234f14205c67505506768e9a3e))
- **docs:** fix typo in collapse events doc
  ([d8f5d69](https://github.com/bootstrap-vue/bootstrap-vue/commit/d8f5d694b64761120f3b4b230b1d3541bf4b0753))
- **docs:** fixes broken styling of docs navigation
  ([#1911](https://github.com/bootstrap-vue/bootstrap-vue/issues/1911))
  ([95a5012](https://github.com/bootstrap-vue/bootstrap-vue/commit/95a5012575b25b9594f3757512218b98156bc5a9))
- **docs:** improve CSS load ordering
  ([#2255](https://github.com/bootstrap-vue/bootstrap-vue/issues/2255))
  ([e193362](https://github.com/bootstrap-vue/bootstrap-vue/commit/e19336272a8a6a5fb04d28580a487f72e11d4fc8))
- **docs:** incorrect closing <b-form-file> tag
  ([#1838](https://github.com/bootstrap-vue/bootstrap-vue/issues/1838))
  ([69e410d](https://github.com/bootstrap-vue/bootstrap-vue/commit/69e410d204a31664f6f85e06f8a92f19e05ecb56))
- **docs:** input group prepend slot typo
  ([#2059](https://github.com/bootstrap-vue/bootstrap-vue/issues/2059))
  ([3c3cd8d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c3cd8d2683e6ecb8e50811ca0bf6cc3acd7e23a))
- **docs:** Layout - Typo ([#1966](https://github.com/bootstrap-vue/bootstrap-vue/issues/1966))
  ([c5a37d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/c5a37d3873fcbd73f11680dc12c2c85bbad54548))
- **docs:** missing dash and typo
  ([#1850](https://github.com/bootstrap-vue/bootstrap-vue/issues/1850))
  ([7b5fde8](https://github.com/bootstrap-vue/bootstrap-vue/commit/7b5fde8ea1a00373465f0d587ec834fbeaf61724))
- **docs:** Remove incorrect code added during debugging
  ([#1787](https://github.com/bootstrap-vue/bootstrap-vue/issues/1787))
  ([9911507](https://github.com/bootstrap-vue/bootstrap-vue/commit/99115074a1e57b7ccb7e8c4d31555749b5934c0a))
- **docs:** spelling correction in comment
  ([#1568](https://github.com/bootstrap-vue/bootstrap-vue/issues/1568))
  ([e0e4006](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0e40069b2e75514f07edcc6927bd358d34f9f0c))
- **docs:** typo ([#2009](https://github.com/bootstrap-vue/bootstrap-vue/issues/2009))
  ([9e0eb67](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e0eb677c3ebad0ea82f3837bccefe442f16c0de))
- **docs:** typo in docs plugin
  ([#1777](https://github.com/bootstrap-vue/bootstrap-vue/issues/1777))
  ([fb50c6f](https://github.com/bootstrap-vue/bootstrap-vue/commit/fb50c6f750be7a9363d147bf8e1ab9135892dbcb))
- **docs:** vue-loader v15 changes
  ([#2005](https://github.com/bootstrap-vue/bootstrap-vue/issues/2005))
  ([449a712](https://github.com/bootstrap-vue/bootstrap-vue/commit/449a7121928f394f912dad488e388f1dc78fc09f))
- **dropdown:** add missing TAB keyCode. closes
  [#1577](https://github.com/bootstrap-vue/bootstrap-vue/issues/1577)
  ([#2140](https://github.com/bootstrap-vue/bootstrap-vue/issues/2140))
  ([5e5c5c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e5c5c9a447bebde19460c38c21ebf36448c5bf2))
- **dropdown:** aria-labbeledby for dropdowns
  ([8efa7ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/8efa7ee3978bb2ee29b45d1c92465292174af4e4))
- **dropdown:** Item click event timing
  ([#2251](https://github.com/bootstrap-vue/bootstrap-vue/issues/2251))
  ([e620e07](https://github.com/bootstrap-vue/bootstrap-vue/commit/e620e07d1e15aba43cac0164f502f13672a7ebb7))
- **dropdown:** typo in README ([#1939](https://github.com/bootstrap-vue/bootstrap-vue/issues/1939))
  ([#1942](https://github.com/bootstrap-vue/bootstrap-vue/issues/1942))
  ([8a2ca5e](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a2ca5e607b4e3942a835dddd1a1db3d93a528d7))
- **dropdown:** Use custom CSS for `no-caret` option
  [#1473](https://github.com/bootstrap-vue/bootstrap-vue/issues/1473)
  ([#2136](https://github.com/bootstrap-vue/bootstrap-vue/issues/2136))
  ([2eb706f](https://github.com/bootstrap-vue/bootstrap-vue/commit/2eb706f65c1dbbe46223e9003fd06098c00b42e6))
- **dropdown-item-button:** Add support for `active` state
  ([#2212](https://github.com/bootstrap-vue/bootstrap-vue/issues/2212))
  ([4b9e6c0](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b9e6c01b1fb1466050b7708e414820a4dc4ac38))
- **dropdown, button, link:** various bug fixes and aria fixes (Fixes
  [#1814](https://github.com/bootstrap-vue/bootstrap-vue/issues/1814),[#1817](https://github.com/bootstrap-vue/bootstrap-vue/issues/1817))
  ([#2159](https://github.com/bootstrap-vue/bootstrap-vue/issues/2159))
  ([e79270d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e79270d623a606ed9fabea11af154002831da190))
- **fom-input:** revert changes from PR
  [#1841](https://github.com/bootstrap-vue/bootstrap-vue/issues/1841)
  ([#2174](https://github.com/bootstrap-vue/bootstrap-vue/issues/2174))
  ([aacc7c0](https://github.com/bootstrap-vue/bootstrap-vue/commit/aacc7c083e8b7d62f0cdb1142da349338fd46e29))
- **form-file:** Add prop to allow customization of browse button text. fixes
  [#2143](https://github.com/bootstrap-vue/bootstrap-vue/issues/2143)
  ([#2168](https://github.com/bootstrap-vue/bootstrap-vue/issues/2168))
  ([56c26da](https://github.com/bootstrap-vue/bootstrap-vue/commit/56c26dacd1a7fd9b6990db5225593f8de22efe19))
- **form-file:** fix drag and drop feature
  ([#2169](https://github.com/bootstrap-vue/bootstrap-vue/issues/2169))
  ([07bfc29](https://github.com/bootstrap-vue/bootstrap-vue/commit/07bfc29e641369c6ea385acc7f38e1a509173f2a))
- **form-file:** issue with "accept" values
  [fixes [#1526](https://github.com/bootstrap-vue/bootstrap-vue/issues/1526), reverts [#2028](https://github.com/bootstrap-vue/bootstrap-vue/issues/2028)](<[#2008](https://github.com/bootstrap-vue/bootstrap-vue/issues/2008)>)
  ([963d478](https://github.com/bootstrap-vue/bootstrap-vue/commit/963d4785e341ffc83ea79f0bba9e04afc302ed0f))
- **form-group:** add missing disabled prop
  ([#2106](https://github.com/bootstrap-vue/bootstrap-vue/issues/2106))
  ([4971c06](https://github.com/bootstrap-vue/bootstrap-vue/commit/4971c067817b8c4c3336111614ae9957dc603ee0)),
  closes [#1920](https://github.com/bootstrap-vue/bootstrap-vue/issues/1920)
- **form-group:** replace .col-form-legend with .col-form-label
  ([ac2d4dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ac2d4dd54ce9940b63457975cea949c541d76833))
- **id:** fixed check for \_uid in client side id generator
  ([#1499](https://github.com/bootstrap-vue/bootstrap-vue/issues/1499))
  ([f3fe0f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/f3fe0f468b6cf242bb2af41b9fee3d5a67db2197))
- **input-group:** fix dropdown rounded corners. closes
  [#1560](https://github.com/bootstrap-vue/bootstrap-vue/issues/1560).
  ([7df01ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/7df01ff4dde2a934f287b7fa193ea97196cdcd99))
- **modal:** Correct the internal btn variable names
  ([301f2e4](https://github.com/bootstrap-vue/bootstrap-vue/commit/301f2e422864eb0b799a2dfdc8ef920393a6594f)),
  closes [#1650](https://github.com/bootstrap-vue/bootstrap-vue/issues/1650)
- **modal:** hide dropdown on click.
  ([#1528](https://github.com/bootstrap-vue/bootstrap-vue/issues/1528))
  ([3ad8a9a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ad8a9a8a23ae075f9115b61ec989f24d4cde577))
- **select:** Fix issues with form-select
  ([#1673](https://github.com/bootstrap-vue/bootstrap-vue/issues/1673))
  ([e3336c5](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3336c5636ad66dd0efbc1a8b1aa52e70fbd92d1)),
  closes [#1658](https://github.com/bootstrap-vue/bootstrap-vue/issues/1658)
- **tab:** fix the delay in tab transition
  ([#1812](https://github.com/bootstrap-vue/bootstrap-vue/issues/1812))
  ([#1806](https://github.com/bootstrap-vue/bootstrap-vue/issues/1806))
  ([5a7a290](https://github.com/bootstrap-vue/bootstrap-vue/commit/5a7a29002f3140162e597c76d98c0101a9ca3949))
- **tab:** typo aria-lablelledby
  ([#1959](https://github.com/bootstrap-vue/bootstrap-vue/issues/1959))
  ([5933955](https://github.com/bootstrap-vue/bootstrap-vue/commit/59339555070586a838cf8fb87a32638a3b25cb25)),
  closes [#954](https://github.com/bootstrap-vue/bootstrap-vue/issues/954)
- **table:** only call provider once DOM is fully updated
  ([#1904](https://github.com/bootstrap-vue/bootstrap-vue/issues/1904))
  ([#1955](https://github.com/bootstrap-vue/bootstrap-vue/issues/1955))
  ([ae7147e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae7147e34b7727fb28d7f6aa4a47ff0422484c59))
- typo corrected in tooltips ([#1930](https://github.com/bootstrap-vue/bootstrap-vue/issues/1930))
  ([5e4fbe4](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e4fbe40a7f85c612e46a7ccfc9f554cc1c2af75))
- typo in form-radio watcher ([#1943](https://github.com/bootstrap-vue/bootstrap-vue/issues/1943))
  ([9ab23ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ab23ef3642d545c91514809a98063a48a04d29c))
- **form-input:** allow readonly to be forced to false when plaintext is enabled
  ([#1841](https://github.com/bootstrap-vue/bootstrap-vue/issues/1841))
  ([b02a6ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/b02a6ee376681a16f898170d387c99d0af1291b3))
- **form-input:** always return formatted value
  ([#1839](https://github.com/bootstrap-vue/bootstrap-vue/issues/1839))
  ([77cc97b](https://github.com/bootstrap-vue/bootstrap-vue/commit/77cc97bf89d083603902288435e82183cf0bd534))
- **form-input:** bug fixes and add new features
  ([#2100](https://github.com/bootstrap-vue/bootstrap-vue/issues/2100))
  ([0299159](https://github.com/bootstrap-vue/bootstrap-vue/commit/02991599a087ce145e8409f3e1fb81875e579660))
- **form-input:** custom-range style adjustments
  ([#2122](https://github.com/bootstrap-vue/bootstrap-vue/issues/2122))
  ([1917c15](https://github.com/bootstrap-vue/bootstrap-vue/commit/1917c15b6fe2204e930df4555f685f4d5f7eb9f5))
- **form-input:** force update formatted value
  ([#1845](https://github.com/bootstrap-vue/bootstrap-vue/issues/1845))
  ([497cc6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/497cc6e39ab6872549c0b5884041719d4e25afec))
- **form-input:** revert step, min and max props
  ([#1767](https://github.com/bootstrap-vue/bootstrap-vue/issues/1767))
  ([1ce1a20](https://github.com/bootstrap-vue/bootstrap-vue/commit/1ce1a20b35cbcd385dd4327ced73e8cf0bbfcdb0))
- **form-state:** explicitly handle when state is set to empty string. fixes
  [#2166](https://github.com/bootstrap-vue/bootstrap-vue/issues/2166)
  ([#2167](https://github.com/bootstrap-vue/bootstrap-vue/issues/2167))
  ([805a7fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/805a7fe8d38f17cf03131a3a46d00fc0f1239d06))
- **img-lazy:** typo ([#1778](https://github.com/bootstrap-vue/bootstrap-vue/issues/1778))
  ([11d113c](https://github.com/bootstrap-vue/bootstrap-vue/commit/11d113cc93506bfb4803692f523b6e5cf1c784ff))
- **input-group:** Fix size styling issues for input types range and color
  ([3ba1230](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ba12309b242b5025afab4e4fb312576b1311405))
- **input-group:** Minor fixes and documentation update
  ([#2128](https://github.com/bootstrap-vue/bootstrap-vue/issues/2128))
  ([afe1cd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/afe1cd06091eb531fd24e31fc58f22e4925b0fc3))
- **input-group:** Styling fix for dropdowns, radio and checkbox groups. Fixes
  [#2114](https://github.com/bootstrap-vue/bootstrap-vue/issues/2114),[#1560](https://github.com/bootstrap-vue/bootstrap-vue/issues/1560)
  ([#2118](https://github.com/bootstrap-vue/bootstrap-vue/issues/2118))
  ([ed31bcd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed31bcde977e735e1b887c529afaf05ebe400333))
- **list-group-item:** set button type to 'button' when button in mode or tag=button (Fixes
  [#2192](https://github.com/bootstrap-vue/bootstrap-vue/issues/2192))
  ([#2194](https://github.com/bootstrap-vue/bootstrap-vue/issues/2194))
  ([4322ccb](https://github.com/bootstrap-vue/bootstrap-vue/commit/4322ccb800ac3886cf7b2b252ae7e8b22b73e7ee))
- **modal:** better enforce focus handler.
  ([#2215](https://github.com/bootstrap-vue/bootstrap-vue/issues/2215))
  ([9628de2](https://github.com/bootstrap-vue/bootstrap-vue/commit/9628de25577bc33cdcac6440a49b80415623084b))
- **modal:** clear modal paddingLeft and paddingRight if no Scrollbar(s) in adjustDialog().
  ([#2050](https://github.com/bootstrap-vue/bootstrap-vue/issues/2050))
  ([80f1d6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/80f1d6e927ebf6c86c84824df54f0f8b1e13d5ac))
- **modal:** Handle enforce focus when modals are stacked (Fixes
  [#2175](https://github.com/bootstrap-vue/bootstrap-vue/issues/2175))
  ([#2211](https://github.com/bootstrap-vue/bootstrap-vue/issues/2211))
  ([7d768d1](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d768d1ce12648050659a565e20cc69e2f8f4c7d))
- **modal:** prevent scrolling on .modal-content focus, fixes
  [#1748](https://github.com/bootstrap-vue/bootstrap-vue/issues/1748)
  ([#2060](https://github.com/bootstrap-vue/bootstrap-vue/issues/2060))
  ([df9efad](https://github.com/bootstrap-vue/bootstrap-vue/commit/df9efadbb51797918016fdc7fda8e5304c4e3682))
- **nav-item-dropdown:** close menu when clicked outside
  ([#2202](https://github.com/bootstrap-vue/bootstrap-vue/issues/2202))
  ([9e3e33e](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e3e33ea8484ae0cc6e972b53ac39f868674060b)),
  closes [#2198](https://github.com/bootstrap-vue/bootstrap-vue/issues/2198)
- **navbar:** Support always expanded navbar (fixes
  [#2209](https://github.com/bootstrap-vue/bootstrap-vue/issues/2209))
  ([#2210](https://github.com/bootstrap-vue/bootstrap-vue/issues/2210))
  ([7c3737c](https://github.com/bootstrap-vue/bootstrap-vue/commit/7c3737c2446683b2dd616e618b82358149bfde99))
- **observe-dom:** fix comment typo
  ([#2084](https://github.com/bootstrap-vue/bootstrap-vue/issues/2084))
  ([8b41913](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b419139f7f5111a7f5ac745450d5b5d0bdcae27))
- **popover:** Add directive to component plugin
  ([#2115](https://github.com/bootstrap-vue/bootstrap-vue/issues/2115))
  ([e39a855](https://github.com/bootstrap-vue/bootstrap-vue/commit/e39a8550f8a492dcc6ecc0e521f87e6a1b65589b))
- **popover:** fixes close emit argument
  ([#1937](https://github.com/bootstrap-vue/bootstrap-vue/issues/1937))
  ([8b9db28](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b9db28e5be1e96acd28bc4905e6a53aabc5c7c1))
- **safeId:** trigger id creation/update after mount (fixes
  [#1978](https://github.com/bootstrap-vue/bootstrap-vue/issues/1978))
  ([#2161](https://github.com/bootstrap-vue/bootstrap-vue/issues/2161))
  ([48218fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/48218fe7fd0dc78a7936608b11fd7f98a1dfc243))
- **scss:** import \_input-group.scss once at most
  ([#2239](https://github.com/bootstrap-vue/bootstrap-vue/issues/2239))
  ([2e7dcfa](https://github.com/bootstrap-vue/bootstrap-vue/commit/2e7dcfab5813e6712486798fe85f7fa2e3596659))
- **select:** Wait for the v-model value to update before emitting change event on form select
  ([#2207](https://github.com/bootstrap-vue/bootstrap-vue/issues/2207))
  ([7a860ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a860eeae5664dbc7560e58a8cce4adcd32f0241))
- **table:** Emit v-model input event only when computedItems changes (closes
  [#2231](https://github.com/bootstrap-vue/bootstrap-vue/issues/2231))
  ([#2254](https://github.com/bootstrap-vue/bootstrap-vue/issues/2254))
  ([f0fb9af](https://github.com/bootstrap-vue/bootstrap-vue/commit/f0fb9af0b4f2398addac1441574967a90aa6a747))
- **table:** fix aria-rowcount ([#1836](https://github.com/bootstrap-vue/bootstrap-vue/issues/1836))
  ([e3e5439](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3e54395838261e296f92ab5baac635ba9f78803))
- **table:** fix filtered event, fix emptyFilter message w/filter function, fix reactivity of filter
  sub routines, fix empty header label accessibility issue (Fixes
  [#1989](https://github.com/bootstrap-vue/bootstrap-vue/issues/1989),[#1517](https://github.com/bootstrap-vue/bootstrap-vue/issues/1517))
  ([#2149](https://github.com/bootstrap-vue/bootstrap-vue/issues/2149))
  ([e0e1eee](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0e1eeef2a55348a52511f388baf70bc1a2df07b))
- **table:** import lodash.get from "dependencies"
  ([#1697](https://github.com/bootstrap-vue/bootstrap-vue/issues/1697))
  ([4d620a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/4d620a5e68acafd03abc157cad0ecf7353a52bd6))
- **table:** Preserve aria-rowcount and aria-describedby if provided. Fixes
  [#1801](https://github.com/bootstrap-vue/bootstrap-vue/issues/1801)
  ([#2195](https://github.com/bootstrap-vue/bootstrap-vue/issues/2195))
  ([e0cdca0](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0cdca08cbdaae34b5bab8e669194a7775eeacf5))
- **table:** return empty string if cell value is null or undefined. Fixes
  [#1502](https://github.com/bootstrap-vue/bootstrap-vue/issues/1502)
  ([#2139](https://github.com/bootstrap-vue/bootstrap-vue/issues/2139))
  ([b62f8f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/b62f8f4d311fbb234cbb8f131a8a0df2b600a739))
- **table:** typo in README.md ([#1729](https://github.com/bootstrap-vue/bootstrap-vue/issues/1729))
  ([8d0e186](https://github.com/bootstrap-vue/bootstrap-vue/commit/8d0e1863124d779e8de38364ad283b7221129a94))
- **tabs:** change default key nav to avoid breaking changes
  ([#1733](https://github.com/bootstrap-vue/bootstrap-vue/issues/1733))
  ([a6dea02](https://github.com/bootstrap-vue/bootstrap-vue/commit/a6dea0236e1912b02792a6720d0a61bae1693e0a))
- **tabs:** typo in tabs ([#1735](https://github.com/bootstrap-vue/bootstrap-vue/issues/1735))
  ([89eff3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/89eff3c90f861215b9b92dd30d89cea15efe58bd))
- **tooltip:** typo in comment ([#1779](https://github.com/bootstrap-vue/bootstrap-vue/issues/1779))
  ([ef253f7](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef253f7affcad451766dd57b55d6b16901c1e353))
- default export in TypeScript definitions
  ([cd7e310](https://github.com/bootstrap-vue/bootstrap-vue/commit/cd7e310f9ba9117b5c97ed51567cc7ebff732c52))
- **tabs:** rename prop to no-key-nav, update docs
  ([491d698](https://github.com/bootstrap-vue/bootstrap-vue/commit/491d698e0d2347f0b650fccb3122f008a16e1d1f))
- **text-area:** input event ([#1714](https://github.com/bootstrap-vue/bootstrap-vue/issues/1714))
  ([5e2973d](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e2973de2b70b4943e332fae80f10ee748966332))
- **toolpop mixin:** allow boundary type to be HTMLElement (Fixes
  [#2229](https://github.com/bootstrap-vue/bootstrap-vue/issues/2229))
  ([#2233](https://github.com/bootstrap-vue/bootstrap-vue/issues/2233))
  ([8b8272b](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b8272bad45585389989064aa11e1fd622237493))
- **tooltip:** Add directive to component plugin
  ([#2116](https://github.com/bootstrap-vue/bootstrap-vue/issues/2116))
  ([e5bb09e](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5bb09e5dc62e09538a344f535d321921d5d3532))
- **utils/loose-equal:** check dates in looseEqual util
  ([#2123](https://github.com/bootstrap-vue/bootstrap-vue/issues/2123))
  ([8a8d0f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a8d0f07b9f941d55254b30f68c95d84d0ebc2e6))
- call `removeEventListener` on the right element
  ([#1557](https://github.com/bootstrap-vue/bootstrap-vue/issues/1557))
  ([cf2bfca](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf2bfca67411833805e6094c614854d56ff30787)),
  closes [#1391](https://github.com/bootstrap-vue/bootstrap-vue/issues/1391)
- polyfill HTMLElement for SSR
  ([d4dd9b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4dd9b386907b0b35639a6e2ce20ab77d9e5e416))
- **button:** allow custom size classes to be passed to the size prop
  ([#1389](https://github.com/bootstrap-vue/bootstrap-vue/issues/1389))
  ([41a46b2](https://github.com/bootstrap-vue/bootstrap-vue/commit/41a46b28ef4ff184ca5d198c06b43e8e820f488c))
- **button:** allow custom size classes to be passed to the size prop
  ([#1389](https://github.com/bootstrap-vue/bootstrap-vue/issues/1389))
  ([96fb934](https://github.com/bootstrap-vue/bootstrap-vue/commit/96fb934d378e10a94533b78792ec42f8ebdc82fc))
- **button-close:** switch to slots() from children
  ([#1345](https://github.com/bootstrap-vue/bootstrap-vue/issues/1345))
  ([9c997b7](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c997b765430ab94bcbca4ccf10ecc0bcc4245e2))
- **carousel:** clear timers on beforeDestroy
  ([fa1c083](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa1c083cad4495d6020b9363aaceaab1f084bd25))
- **carousel:** clear timers on beforeDestroy
  ([53ea1b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/53ea1b4ae61618af5de4cf4c3098e41a88b80b0e))
- **carousel:** remove un-needed `aria-` atribute on slides
  ([#1448](https://github.com/bootstrap-vue/bootstrap-vue/issues/1448))
  ([260919f](https://github.com/bootstrap-vue/bootstrap-vue/commit/260919f30c46efdc2b162931d155c042c2d31d59))
- **carousel:** uncaught typeerror on empty slides.
  ([#1401](https://github.com/bootstrap-vue/bootstrap-vue/issues/1401))
  ([cadae79](https://github.com/bootstrap-vue/bootstrap-vue/commit/cadae7928c40e444d785b7bc317024473d700748))
- **carousel:** uncaught typeerror on empty slides.
  ([#1401](https://github.com/bootstrap-vue/bootstrap-vue/issues/1401))
  ([a2ee9b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2ee9b6498d655e4bf92b261453ce4dcade0e499))
- **ci:** auto deploy docs from master branch
  ([22e432d](https://github.com/bootstrap-vue/bootstrap-vue/commit/22e432d972a67638ec9111675333c934e6b0ff1b))
- **docs play:** prevent duplicate key errors in console output
  ([#1476](https://github.com/bootstrap-vue/bootstrap-vue/issues/1476))
  ([68deee1](https://github.com/bootstrap-vue/bootstrap-vue/commit/68deee1a90a2360396f9b58efc51a7d1cabb5ef1))
- **dropdown:** fix condition for when position-static is applied
  ([#1477](https://github.com/bootstrap-vue/bootstrap-vue/issues/1477))
  ([1717edb](https://github.com/bootstrap-vue/bootstrap-vue/commit/1717edbda6f4c581111342f4fb66e06ce058021a))
- **dropdown:** fixed aria-labbeledby for non-split dropdowns
  ([d597dbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/d597dbce683928246eaf3cf6e386f63b6c9f157b))
- **dropdown:** prevent toggle click from closing in collapsed navbar
  ([#1475](https://github.com/bootstrap-vue/bootstrap-vue/issues/1475))
  ([24ef1e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/24ef1e6b2a94981d302da3a05ed790a9b46afa32)),
  closes [#1474](https://github.com/bootstrap-vue/bootstrap-vue/issues/1474)
- **dropdown:** use class `position-static` instead of inline style
  ([#1451](https://github.com/bootstrap-vue/bootstrap-vue/issues/1451))
  ([fc49325](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc493259aee8fd0f4a806c69a3844e63b80ede3a))
- **dropdowns:** prevent memory leak on destroy
  ([#1392](https://github.com/bootstrap-vue/bootstrap-vue/issues/1392))
  ([839418e](https://github.com/bootstrap-vue/bootstrap-vue/commit/839418ee666c44b3b56d20e28fb1e98f170ea0a1)),
  closes [#1391](https://github.com/bootstrap-vue/bootstrap-vue/issues/1391)
- **dropdowns:** prevent memory leak on destroy
  ([#1392](https://github.com/bootstrap-vue/bootstrap-vue/issues/1392))
  ([05a5c50](https://github.com/bootstrap-vue/bootstrap-vue/commit/05a5c504a61eba9b5b87bdc254283523f10acbaf)),
  closes [#1391](https://github.com/bootstrap-vue/bootstrap-vue/issues/1391)
- **form-file:** invalid/valid feedback display for plain file input missing in Bootstrap V4
  ([#1373](https://github.com/bootstrap-vue/bootstrap-vue/issues/1373))
  ([85ab0d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/85ab0d0b418559d36cd693d235167e933a3d906e))
- **form-group:** import b-form-row directly from layout
  ([8dcce39](https://github.com/bootstrap-vue/bootstrap-vue/commit/8dcce39e670cbdd0401cb0ff5ebe7b098bf3c8df))
- **form-group:** import b-form-row directly from layout
  ([b43d7c8](https://github.com/bootstrap-vue/bootstrap-vue/commit/b43d7c836d23c5d126428b37325adf355f968afa))
- **form-radio-group:** prepare for bootstrap V4.beta.3
  ([39eb237](https://github.com/bootstrap-vue/bootstrap-vue/commit/39eb2377b78886f22e547e509d999524e7ed4f27))
- **form-radio-group:** prepare for bootstrap V4.beta.3
  ([5b659d1](https://github.com/bootstrap-vue/bootstrap-vue/commit/5b659d17ecb4aeaed5d9a0a4e3940de61c8a8a29))
- **form-textarea:** initial value population
  ([#1370](https://github.com/bootstrap-vue/bootstrap-vue/issues/1370))
  ([a08a46e](https://github.com/bootstrap-vue/bootstrap-vue/commit/a08a46e661b5bcae5a3266299c91d66bd65ca014)),
  closes [#1368](https://github.com/bootstrap-vue/bootstrap-vue/issues/1368)
- **form-textarea:** monitor localValue instead of value when calculating lines
  ([9f3439f](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f3439f870f8281536d27eb86a9933813a31e25b))
- **id mixin:** set prop type to String
  ([9a6eaa5](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a6eaa5f40047e72a7d66f8f04169885fa003b33))
- **id mixin:** set prop type to String
  ([37ab5cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/37ab5cbf78f848a7d09e5b541568334ab377013e))
- **link:** restore original tabindex when not disabled
  ([cfdf0b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/cfdf0b98b3d5961cfa056455056c2f983a62979e))
- **link:** take link out of tab sequence if disabled
  ([#1347](https://github.com/bootstrap-vue/bootstrap-vue/issues/1347))
  ([360588a](https://github.com/bootstrap-vue/bootstrap-vue/commit/360588aa4aa4011a0cc90141801ad4c778aa45fe))
- **list-group:** disabled button items
  ([#1444](https://github.com/bootstrap-vue/bootstrap-vue/issues/1444))
  ([c037b38](https://github.com/bootstrap-vue/bootstrap-vue/commit/c037b381ae44e6d89b073a6fc9417aba99394219))
- **modal:** modal-open body class lost when switching between modals
  ([#1327](https://github.com/bootstrap-vue/bootstrap-vue/issues/1327))
  ([99e146f](https://github.com/bootstrap-vue/bootstrap-vue/commit/99e146f34c6a99ecb9ee2dacff40b88b8cf7cb43)),
  closes [#1325](https://github.com/bootstrap-vue/bootstrap-vue/issues/1325)
- **modal:** rounded-top class no longer needed when header variant applied
  ([#1433](https://github.com/bootstrap-vue/bootstrap-vue/issues/1433))
  ([ecf1bf5](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecf1bf508f945a996cabb91f3efb9aeffa2e6c90))
- **modal:** update centered modal margins to align with BSV4.beta.3 update
  ([f7e80a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/f7e80a8fcd11c5c970e11d74cb94d5042867a0f8))
- **table:** better custom css specificity for when nesting tables
  ([7acccb9](https://github.com/bootstrap-vue/bootstrap-vue/commit/7acccb990d8c1115b0c22274c30d9df4d641a6cd))
- **table:** better custom css specificity for when nesting tables
  ([4a2d121](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a2d12103496397667d596ca1fa873b1d8f810d3))
- **table:** correct fixd-top row scoped slot properties
  ([debf8e2](https://github.com/bootstrap-vue/bootstrap-vue/commit/debf8e2ee3111a0f0c223820887cb11fb46783d1))
- **table:** correct fixd-top row scoped slot properties
  ([7e042f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/7e042f140fa08d5cf3792ac7537698fcf57c1b5c))
- **table:** fix outlined table
  ([e81b107](https://github.com/bootstrap-vue/bootstrap-vue/commit/e81b107e5a12a3a42e0d4c4cf91fc2105baa1c02))
- **table:** initial busy of true always makes table busy
  ([#1400](https://github.com/bootstrap-vue/bootstrap-vue/issues/1400))
  ([029e4d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/029e4d0876fcc8cb8fd4dc613f148edc37bbe325)),
  closes [#1398](https://github.com/bootstrap-vue/bootstrap-vue/issues/1398)
- **table:** initial busy of true always makes table busy
  ([#1400](https://github.com/bootstrap-vue/bootstrap-vue/issues/1400))
  ([5daa0df](https://github.com/bootstrap-vue/bootstrap-vue/commit/5daa0df1426487a024339634619fee99798b5265)),
  closes [#1398](https://github.com/bootstrap-vue/bootstrap-vue/issues/1398)
- **table:** use stable sort algorithm to prevent SSR issues
  ([#1399](https://github.com/bootstrap-vue/bootstrap-vue/issues/1399))
  ([21b33f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/21b33f2e5e6d127380027ff3cd118512636dcd09))
- **table:** use stable sort algorithm to prevent SSR issues
  ([#1399](https://github.com/bootstrap-vue/bootstrap-vue/issues/1399))
  ([552c438](https://github.com/bootstrap-vue/bootstrap-vue/commit/552c438ed8a7cc10726a1d82f77e1e9bbfaa37a4))
- **tooltip+popover:** auto-append to `.modal-content` instead of `.modal`
  ([#1465](https://github.com/bootstrap-vue/bootstrap-vue/issues/1465))
  ([b53715c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b53715c78eab38faab839ff25d607a7f9e1e733d)),
  closes [#1464](https://github.com/bootstrap-vue/bootstrap-vue/issues/1464)
- detach clickout listener in beforeDestroy
  ([b290cad](https://github.com/bootstrap-vue/bootstrap-vue/commit/b290cad0c0f4fbff9c1dab6bdcee6dfa933c1359))
- detach clickout listener in beforeDestroy
  ([89618de](https://github.com/bootstrap-vue/bootstrap-vue/commit/89618de14f68fc9b3f930463ecdade01a73356e0))
- remove listenOnRoot handlers in beforeDestroy
  ([e594490](https://github.com/bootstrap-vue/bootstrap-vue/commit/e594490a58c332cfda3ffc56b666c545e99f307d))
- remove listenOnRoot handlers in beforeDestroy
  ([7f7eba1](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f7eba1f814202ad3200653d7f252a3ab100a0f8))
- SFC transpilation in es buld ([#1410](https://github.com/bootstrap-vue/bootstrap-vue/issues/1410))
  ([3ef9572](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ef95723d7c1d2bda5635013216630fc35fe13ce))
- SFC transpilation in es buld ([#1410](https://github.com/bootstrap-vue/bootstrap-vue/issues/1410))
  ([ce80809](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce8080936e803031585b2b9437509587624d46cc))
- **build:** use esm bundle. resolves
  [#1296](https://github.com/bootstrap-vue/bootstrap-vue/issues/1296).
  ([06d40a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/06d40a54b61f6bdd118ab2fd4c87be072e860034))
- **button:** Don't ovrwrite user supplied tabindex if not disabled
  ([#1120](https://github.com/bootstrap-vue/bootstrap-vue/issues/1120))
  ([18f5129](https://github.com/bootstrap-vue/bootstrap-vue/commit/18f512916c41965c1e388a84c541ed1362de57fb)),
  closes [#1119](https://github.com/bootstrap-vue/bootstrap-vue/issues/1119)
- **button-close:** Hardcode &times; character to prevent SSR bailing
  ([b0dd1ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0dd1ba175dad8456f931a84973c214375f9a7e7))
- **button-group:** Bootstrap V4.beta.2 CSS changes
  ([1b4618f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b4618f29dc70022b607c23002f5cff7b49d5ced))
- **carousel:** Minor adjustments to fousout/mouseout event handler
  ([#1239](https://github.com/bootstrap-vue/bootstrap-vue/issues/1239))
  ([330b70b](https://github.com/bootstrap-vue/bootstrap-vue/commit/330b70ba2361b49bbeebb238eed842d4a2a30f1e))
- **docs:** Homepage link to changelog
  ([2dd229d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dd229d679d24e8ca8e6ac736563fceac6898f52))
- **docs:** Move TOC generation inside export
  ([1267207](https://github.com/bootstrap-vue/bootstrap-vue/commit/12672079c023ecfb32fb2f9056cf87ac489173ef))
- **docs:** popover directive's broken link
  ([#1116](https://github.com/bootstrap-vue/bootstrap-vue/issues/1116))
  ([201e926](https://github.com/bootstrap-vue/bootstrap-vue/commit/201e926258acf18c85821e535796f71e9177cc73))
- **docs:** typo in Modal docs ([#1092](https://github.com/bootstrap-vue/bootstrap-vue/issues/1092))
  ([051034b](https://github.com/bootstrap-vue/bootstrap-vue/commit/051034ba3a06239d7a34ed908353afb39f6abc44))
- **dom utils:** use getBoundingClientRect() to determine element visibility
  ([#1203](https://github.com/bootstrap-vue/bootstrap-vue/issues/1203))
  ([6e2fff4](https://github.com/bootstrap-vue/bootstrap-vue/commit/6e2fff489b716fcddd4aeb0ce3a01b3f1f1e251c))
- **dropdown:** Bootstrap V4.beta.2 now has better hover/focus styling
  ([#1224](https://github.com/bootstrap-vue/bootstrap-vue/issues/1224))
  ([0b8bc67](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b8bc67f8f4726fe1bd289f001da5639dc1269ba))
- **form-check+radio mixin:** pull state from parent group
  ([6845014](https://github.com/bootstrap-vue/bootstrap-vue/commit/68450143623c7e4bdd82959f6ea769c53d25b3d7))
- **form-checkbox:** apply form state class to hidden inputs
  ([710369c](https://github.com/bootstrap-vue/bootstrap-vue/commit/710369c9f061ca9d5a7d9e7d95c36f7c9a7be7b9))
- **form-checkbox-group:** Changes to button styles
  ([431eb02](https://github.com/bootstrap-vue/bootstrap-vue/commit/431eb0229a73017e99de5d1fda5a145008455eac))
- **form-checkbox-group:** Import b-form-checkbox
  ([09187ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/09187ead52ae3c4c781584593167a6a6c3d487f5))
- **form-file:** control size not supported in BS V4
  ([#1305](https://github.com/bootstrap-vue/bootstrap-vue/issues/1305))
  ([e9a26cf](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9a26cff7fe3e16ffe75accff78e763564e8223d)),
  closes [#1304](https://github.com/bootstrap-vue/bootstrap-vue/issues/1304)
- **form-file:** Focus styling tweaks
  ([c3bc583](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3bc5839aab91f39238fd4eb0f89abb059ed7867))
- **form-input:** BS V4.beta.2 is missing width:100% on readonly plaintext
  ([#1225](https://github.com/bootstrap-vue/bootstrap-vue/issues/1225))
  ([c37cef4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c37cef4989e2e10c7ce8ee956d5d1ba0b7fce293))
- **form-options:** Handle object special cases
  ([#1099](https://github.com/bootstrap-vue/bootstrap-vue/issues/1099))
  ([1b17df3](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b17df39fe441ed55d54b77d4eb4ebe96392d223))
- **form-radio:** apply form state to hidden input element
  ([3074ecc](https://github.com/bootstrap-vue/bootstrap-vue/commit/3074ecc2dd9bb4e7c7dddf05536e947197fe2fab))
- **form-radio-group:** Add support for Boolean value
  ([4cafb27](https://github.com/bootstrap-vue/bootstrap-vue/commit/4cafb27c63a6969b397eda0b6f9cead9e26dd59f))
- **form-radio-group:** Allow number type for checked
  ([#1089](https://github.com/bootstrap-vue/bootstrap-vue/issues/1089))
  ([8eccdbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/8eccdbc0ec540f1088a496bda564f0025d28ddb0))
- **form-radio-group:** Changes to button styles
  ([063e9d8](https://github.com/bootstrap-vue/bootstrap-vue/commit/063e9d84ae68666aba02f70a8f71a6dcf29c944a))
- **form-radio-group:** Import b-form-radio
  ([82bb078](https://github.com/bootstrap-vue/bootstrap-vue/commit/82bb078883ab94b873fa1815b5d3cd2c5da82267))
- **form-select:** Custom select now supports multiple attribute in V4.beta.2 CSS
  ([#1223](https://github.com/bootstrap-vue/bootstrap-vue/issues/1223))
  ([3a4262d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a4262d8dfd52663c53680fb383145ad3f6074f2))
- **img-lazy:** alt tag was being removed when image loaded
  ([f2fb99c](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2fb99c5e418543869d6611f201fc240d284b722))
- **input-group:** BS V4.beta CSS no longer has the `has-${state}` classes
  ([#1155](https://github.com/bootstrap-vue/bootstrap-vue/issues/1155))
  ([9f4df16](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f4df169078dd543248deab741746cbdd24ee5ef))
- **input-group:** correct input-group right addon via prop
  ([#1317](https://github.com/bootstrap-vue/bootstrap-vue/issues/1317))
  ([061abc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/061abc5ed90d523b8d164780e9bfe965caefd133))
- **link:** Only set attribute aria-disabled when disabled
  ([fe2c340](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe2c34046ea7e320f652afe6646debf5947f4512))
- **link:** working href with router-link on ssr
  ([8a6f243](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a6f243f4174587888c65c360678a1fd9e74a2e9))
- **modal:** Add outer wrapper div to that lazy modal's will still have a $ref when hidden
  ([#1186](https://github.com/bootstrap-vue/bootstrap-vue/issues/1186))
  ([7f7e6a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f7e6a72fb1c1d69830d9fc52579d4b6dcf6dd95))
- **modal:** Ensure body scrollbar is removed if modal destroyed before being closed
  ([#1168](https://github.com/bootstrap-vue/bootstrap-vue/issues/1168))
  ([e0a4444](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0a4444ab04008f78e162b86ee22801b676f71b7))
- **modal:** Modal jumps when dialog height changes
  ([#1182](https://github.com/bootstrap-vue/bootstrap-vue/issues/1182))
  ([126fe95](https://github.com/bootstrap-vue/bootstrap-vue/commit/126fe950e1fdb72024e332b65f3ecf5d07c3864c)),
  closes [#1058](https://github.com/bootstrap-vue/bootstrap-vue/issues/1058)
- **nav-item-dropdown:** fix disabled in toggleClasses
  ([#1123](https://github.com/bootstrap-vue/bootstrap-vue/issues/1123))
  ([aabc54d](https://github.com/bootstrap-vue/bootstrap-vue/commit/aabc54d213fff57814f3f78a874c28d63d05de83))
- **nuxt module:** wrong relative path to package.json
  ([#1298](https://github.com/bootstrap-vue/bootstrap-vue/issues/1298))
  ([e766e75](https://github.com/bootstrap-vue/bootstrap-vue/commit/e766e75163252b69de7a802b4e30ddc2205bdebb))
- **package.json:** Move Bootstrap back to devDep and update popper.js version
  ([#1228](https://github.com/bootstrap-vue/bootstrap-vue/issues/1228))
  ([87cfab4](https://github.com/bootstrap-vue/bootstrap-vue/commit/87cfab479ab8a9681462070c1a83a3f3bf8e2de1))
- **pagination-nav:** ARIA tabing control
  ([92d0810](https://github.com/bootstrap-vue/bootstrap-vue/commit/92d08102a32345c124bc72bfc4a08fe730d49e3e))
- **popover+tooltip:** content not restored after hiding all popovers with 'bv::hide::popover'
  ([#1323](https://github.com/bootstrap-vue/bootstrap-vue/issues/1323))
  ([94488c6](https://github.com/bootstrap-vue/bootstrap-vue/commit/94488c690a746bc958d5884e552bfa43d75a2e17)),
  closes [#1322](https://github.com/bootstrap-vue/bootstrap-vue/issues/1322)
- **progress:** Apply height style correctly
  ([675c1c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/675c1c999bb205c7538793b7c3167946fcacdbbb))
- **progress:** Bootstrap V4.beta.2 missing progress bar transition
  ([1f1064f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1f1064f26fd2b052500ffbed2f68d2cf3c2193f1))
- **Progress:** Bootstrap V4.beta.2 CSS height prop change
  ([#1217](https://github.com/bootstrap-vue/bootstrap-vue/issues/1217))
  ([a963ea3](https://github.com/bootstrap-vue/bootstrap-vue/commit/a963ea33dab46e4009c740f072f09eee6c5f9ade)),
  closes [#1216](https://github.com/bootstrap-vue/bootstrap-vue/issues/1216)
- **scrollspy:** Minor CSS selector update
  ([0b58a69](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b58a691f5190e29a8526594333875a58b6bb88f))
- **scrollspy:** typo
  ([ec36379](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec3637939381f54b682d483a4cbf63b8ba5e43b3))
- **search+toc:** Make search and TOC generation work with SSR
  ([#1091](https://github.com/bootstrap-vue/bootstrap-vue/issues/1091))
  ([51db684](https://github.com/bootstrap-vue/bootstrap-vue/commit/51db68482236b0b6dd39fe1cc432469b60e101b0))
- **table:** Don't startcase field label when label explicitly given
  ([76a511f](https://github.com/bootstrap-vue/bootstrap-vue/commit/76a511f91083396b741c562ff26daa2da0e57ab4))
- **tabs:** Apply `small` class to parent `ul.nav`
  ([#1255](https://github.com/bootstrap-vue/bootstrap-vue/issues/1255))
  ([42f8a78](https://github.com/bootstrap-vue/bootstrap-vue/commit/42f8a7813a9185cc32c2bdc1bbcb313607ab435a)),
  closes [#1248](https://github.com/bootstrap-vue/bootstrap-vue/issues/1248)
- **tabs:** lazy prop regression
  ([#1372](https://github.com/bootstrap-vue/bootstrap-vue/issues/1372))
  ([844cd81](https://github.com/bootstrap-vue/bootstrap-vue/commit/844cd81c42edceba48a403d43f50dad875750d3c)),
  closes [#1371](https://github.com/bootstrap-vue/bootstrap-vue/issues/1371)
- Remove spacing between stacked buttons style
  ([554e54a](https://github.com/bootstrap-vue/bootstrap-vue/commit/554e54a5eb12153665ba8e8054135357e2e9b40d))
- **alert:** Emit dismiss-count-down at 0 seconds
  ([#839](https://github.com/bootstrap-vue/bootstrap-vue/issues/839))
  ([8dc90bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/8dc90bb628d91a284858cea65c8e40d694b2463b))
- **alert:** Fix auto-dimissing alert "bug"
  ([#897](https://github.com/bootstrap-vue/bootstrap-vue/issues/897))
  ([eccd63e](https://github.com/bootstrap-vue/bootstrap-vue/commit/eccd63e81f77387f8e570f4a6fd723c7aff9ce44))
- **alert:** show dismiss button when dismissible is true
  ([590cead](https://github.com/bootstrap-vue/bootstrap-vue/commit/590ceadbc4695b7ddaacf2b4848ad92835e8b8d3))
- **b-col:** handle bool style prop for sm,md,lg,xl
  ([#1042](https://github.com/bootstrap-vue/bootstrap-vue/issues/1042))
  ([3e7e17d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3e7e17df76b4712090772c568cf5ebebca0d7274)),
  closes [#1041](https://github.com/bootstrap-vue/bootstrap-vue/issues/1041)
- **badge:** Default variant changed
  ([8d3be9e](https://github.com/bootstrap-vue/bootstrap-vue/commit/8d3be9ec4e1e6541e96792a9a081b75e46e69249))
- **badge:** Default variant no longer exists in V4.beta
  ([#875](https://github.com/bootstrap-vue/bootstrap-vue/issues/875))
  ([5fc14d2](https://github.com/bootstrap-vue/bootstrap-vue/commit/5fc14d231eeaa02206e9504fa83d59da4f19195f))
- **carousel:** Handle older opera oTransitionEnd event
  ([#899](https://github.com/bootstrap-vue/bootstrap-vue/issues/899))
  ([5afb591](https://github.com/bootstrap-vue/bootstrap-vue/commit/5afb591f87e59db38a54087516a444d09e891939))
- **carousel:** Prevent reflow trigger from being optimised out
  ([#995](https://github.com/bootstrap-vue/bootstrap-vue/issues/995))
  ([d765976](https://github.com/bootstrap-vue/bootstrap-vue/commit/d765976d7286c0379f31d1f2209b787cb1704617))
- **carousel:** Typo in transition
  ([9693872](https://github.com/bootstrap-vue/bootstrap-vue/commit/96938725f9c0cdcfd978b5f770e55a0530564fd2))
- **coursel:** Ensure minimum interval of 1 second
  ([467ec27](https://github.com/bootstrap-vue/bootstrap-vue/commit/467ec2723503b2c91b48fb613c9b67cc30ecc97c))
- **docs:** Adjust source link if component is a functional component
  ([9cc07a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/9cc07a71b3f6335a5a901756c24657cffea9977d))
- **docs:** b-img fluid-grow example
  ([fe32515](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe325159478a5c20e449a8e422b8adcb08303b9d))
- **docs:** feedback doc in form group
  ([#934](https://github.com/bootstrap-vue/bootstrap-vue/issues/934))
  ([45881bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/45881bbaa61bc2819dbc20cf1cf699fda214371d))
- **docs:** Fix examples in b-img
  ([7607a00](https://github.com/bootstrap-vue/bootstrap-vue/commit/7607a003965f3559938c6573d612bf2848570fa3))
- **docs:** Fix modal-cancel slot name in meta.json
  ([a8772ac](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8772ac385568d299599a55940436e67f1c1354b))
- **docs:** Fix multipe collapse example
  ([65ba276](https://github.com/bootstrap-vue/bootstrap-vue/commit/65ba276899b5b0cd1ed4909c57d1d55e20656215))
- **docs:** Fix reference to modal-cancel slot in modal docs
  ([5747c6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/5747c6dcdac14f32725a864b11f2a97906ee3655))
- **docs:** Side bar navigation not accessible on small screens
  ([#946](https://github.com/bootstrap-vue/bootstrap-vue/issues/946))
  ([4666b37](https://github.com/bootstrap-vue/bootstrap-vue/commit/4666b372019d2c739c797bb8e0dbfb701aba4feb)),
  closes [#948](https://github.com/bootstrap-vue/bootstrap-vue/issues/948)
- **dropdown:** hover/focus shading for active items
  ([b2b6ad9](https://github.com/bootstrap-vue/bootstrap-vue/commit/b2b6ad9853adc030dc1d8b57d0a7094c9fb27894))
- **dropdown:** remove custom hover styling
  ([9c9c3bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c9c3bb414006a05c920871653279a75272291c4))
- **dropdown.js:** import clickout as a mixin
  ([#896](https://github.com/bootstrap-vue/bootstrap-vue/issues/896))
  ([1ba47e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/1ba47e53846c41765229db2a24869fe70b16890c))
- **dropdowns:** Allow gracefull fallback if Popper.js not defined
  ([#920](https://github.com/bootstrap-vue/bootstrap-vue/issues/920))
  ([41b5947](https://github.com/bootstrap-vue/bootstrap-vue/commit/41b59478b06ac2e88ef5e6da9b6634e945329f02))
- **dropdowns:** Migration to popper.js positioning
  ([#913](https://github.com/bootstrap-vue/bootstrap-vue/issues/913))
  ([116cb3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/116cb3e19d52c636f0c3a9d38d887a72788a4a48))
- **dropdowns:** Minor code update & comments
  ([54a2546](https://github.com/bootstrap-vue/bootstrap-vue/commit/54a2546792059a1ef68d3fd7a2682c52a8c0ada1))
- **embed:** Validate type prop
  ([993116b](https://github.com/bootstrap-vue/bootstrap-vue/commit/993116b9609f109f9d3fa0c04782ee188477cb47))
- **form-file:** Selected file name(s) not always showing
  ([565b0ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/565b0aba0e015ae4b7fd943cf931d32c545fe90c))
- **form-group:** Not applying label-for prop value
  ([#1000](https://github.com/bootstrap-vue/bootstrap-vue/issues/1000))
  ([56a4e5e](https://github.com/bootstrap-vue/bootstrap-vue/commit/56a4e5ed4430da89af27456512eb7ddd2d42d3e9))
- **form-group:** use new prop labelCols over old computedLabelCols
  ([#878](https://github.com/bootstrap-vue/bootstrap-vue/issues/878))
  ([b6aa317](https://github.com/bootstrap-vue/bootstrap-vue/commit/b6aa3173248947293c3d548b1987ebe34317b8b8))
- **form-input:** use :value instead of v-model
  ([fcff25d](https://github.com/bootstrap-vue/bootstrap-vue/commit/fcff25d73bfb9e7ed284f271575e04fd84597437))
- **form-textarea:** correct CSS value for no resize
  ([b9bff5e](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9bff5e890ddba11d2e7a8ed1632c5fd4910d9c7))
- **form-textarea:** Fix value reactivity
  ([aeb11be](https://github.com/bootstrap-vue/bootstrap-vue/commit/aeb11be9e26903263f95d5c28948561f5e7753a8))
- **form-textarea:** Max rows not respected if rows specified
  ([4762471](https://github.com/bootstrap-vue/bootstrap-vue/commit/4762471526d4b7dea9e1e242918c211d4034e8f5))
- **form-textarea:** not respecting rows when max-rows provided
  ([e8bf4b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8bf4b38aecabd0fd715cca4829a0caeb642dc25))
- **form-textarea:** Set width to 100% if in plaintext mode
  ([01735e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/01735e68d791987a57f0e662e8fba7a944e8bd33))
- **forms:** Adjustments to form-textarea and form-input
  ([#880](https://github.com/bootstrap-vue/bootstrap-vue/issues/880))
  ([79a7aa8](https://github.com/bootstrap-vue/bootstrap-vue/commit/79a7aa8fdc5d5bb13b4bc5adaa7c4322e628a386))
- **forms:** BS4.beta form/input validation styles & components
  ([#847](https://github.com/bootstrap-vue/bootstrap-vue/issues/847))
  ([00e2b6f](https://github.com/bootstrap-vue/bootstrap-vue/commit/00e2b6ff0afd18d291b6db17e836facfadef9f72))
- **jumbotron:** Accept string or number for header-level
  ([ff223a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff223a816bcf64c85fb246301f977e39f8b7e9e1))
- **lform-group:** Missing return in target ID selection
  ([3323531](https://github.com/bootstrap-vue/bootstrap-vue/commit/332353183f6e111a4d2c447c26f0856d195d06d4))
- **link:** clear router-link/href collision and remove old link mixin
  ([#1016](https://github.com/bootstrap-vue/bootstrap-vue/issues/1016))
  ([ed381f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed381f4b49f06d3d08ad08758dc3d6db77b34fcb)),
  closes [#1018](https://github.com/bootstrap-vue/bootstrap-vue/issues/1018)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#940](https://github.com/bootstrap-vue/bootstrap-vue/issues/940)
- **link:** default href to null
  ([716ce45](https://github.com/bootstrap-vue/bootstrap-vue/commit/716ce45d55fcbf42055672779ee007e09a30e100))
- **link:** ensure target is vue component before #emit
  ([200f31b](https://github.com/bootstrap-vue/bootstrap-vue/commit/200f31b0072ac2f2005639fb4dc966dc2057d4e7))
- **link:** if nothing is provided default href to #
  ([86533fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/86533fae037a99d20342e402f68b47ce42115397))
- **modal:** Fix aria hidden attr and observeDom target element
  ([f099ac7](https://github.com/bootstrap-vue/bootstrap-vue/commit/f099ac702468d7546028ce77e7271c70be4f2441))
- **modal:** fix issue with lazy loading
  ([7557f52](https://github.com/bootstrap-vue/bootstrap-vue/commit/7557f52c188bed0ea8889788a5e758f438a54c40))
- **modal:** Minor bug fixes
  ([6cfc682](https://github.com/bootstrap-vue/bootstrap-vue/commit/6cfc68271aab567a67e5d0c4f238e0bb9f76d02e))
- **nav-dropdown:** Fix right alignment in <b-nav>
  ([#962](https://github.com/bootstrap-vue/bootstrap-vue/issues/962))
  ([9598763](https://github.com/bootstrap-vue/bootstrap-vue/commit/95987631e3edca90879021aebc8d01d706a3944f))
- **nav-item-dropdown:** Fix focus/hover custom CSS
  ([e38576c](https://github.com/bootstrap-vue/bootstrap-vue/commit/e38576c057ecadc22734b6d6099570dd179bfe70))
- **nav-item-dropdown:** hover/focus shading for active items
  ([5bd2b23](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bd2b23b8fb3d6a5fa3deee08f08e78ad1393c1c))
- **nav-item-dropdown:** remove custom hover styling
  ([c794fef](https://github.com/bootstrap-vue/bootstrap-vue/commit/c794fef209605900ca6326298d1d24019f3977e6))
- **nav-toggle:** Use new namespaced collape events
  ([6f87c23](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f87c23006fa608d7f26f86c7902c1b8a421fff8))
- **navbar:** breakpoint control
  ([72cd58d](https://github.com/bootstrap-vue/bootstrap-vue/commit/72cd58d0d843799e74f26cf0a95d25046384beba))
- **navbar:** breakpoint not working
  ([42ca902](https://github.com/bootstrap-vue/bootstrap-vue/commit/42ca902c153eff1c43acd7aa8c855410b7f42883))
- **navbar-brand:** fix pluckProps call for link
  ([9dadfbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/9dadfbc45028b46c9fc1ac2b5410e2762298d0a5))
- **object mixin:** Add polyfill Object.is for IE
  ([beed2c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/beed2c3d1f4f50eb2128d1e7f8d157515b92dd91))
- **observedom:** Adjustments to mutation type detection
  ([75e92d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/75e92d3355c72ea10b7a4b6e4a1ad4a2e5a07d84))
- **observedom:** Callback not being called for changes other than childList changes
  ([#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025))
  ([88cfaef](https://github.com/bootstrap-vue/bootstrap-vue/commit/88cfaefb096f0539ad6ea0632eeb56b9b8d6f0de))
- **observedom:** Callback not being called for changes other than node inert/remove
  ([92ef7eb](https://github.com/bootstrap-vue/bootstrap-vue/commit/92ef7eb997763bcf5643e70fb75bf293a6e9f365))
- **pagination:** Change classes from .hidden-_ to .d-_
  ([#840](https://github.com/bootstrap-vue/bootstrap-vue/issues/840))
  ([0f543a1](https://github.com/bootstrap-vue/bootstrap-vue/commit/0f543a1fcea6de64a52f70ab38a4b576dfe54511))
- **pagination-nav:** Fix link-gen and page-gen
  ([6746cb1](https://github.com/bootstrap-vue/bootstrap-vue/commit/6746cb1fc4c5569ee21c434aadc929984bc15f8a))
- **pagination-nav:** Update v-model on click
  ([188adea](https://github.com/bootstrap-vue/bootstrap-vue/commit/188adea57cbc9ec8bfecf1f700790b5c694320d1))
- **popove:** tooltip import
  ([8a75d10](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a75d10b4727eb942ab0d1691e4574dda3424890))
- **popover:** getting title from title attribute
  ([685de6a](https://github.com/bootstrap-vue/bootstrap-vue/commit/685de6aea634a38f00f52515da177168d55e5245))
- **popover:** remove deprecated target-id prop
  ([472fa79](https://github.com/bootstrap-vue/bootstrap-vue/commit/472fa79e86339d20e1dd4fb89fbfa2048f4eca35))
- **popover:** Remove old tether popover mixin
  ([#947](https://github.com/bootstrap-vue/bootstrap-vue/issues/947))
  ([e500836](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5008361869411e64d99396732ba000d6960f9d4))
- **popover+tooltip:** Allow indiviual component imports
  ([#999](https://github.com/bootstrap-vue/bootstrap-vue/issues/999))
  ([dcc7504](https://github.com/bootstrap-vue/bootstrap-vue/commit/dcc7504c8015db70eb1fd5352438aa3bb97ea7ef))
- **progress:** make progress-bar respect parent show-\* props
  ([9fc726d](https://github.com/bootstrap-vue/bootstrap-vue/commit/9fc726d51f176648451da360f97e4f06af849341))
- **progress-bar:** aria-valuenow fix
  ([f0b486e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f0b486e1954321ede8850c20de7d16b66bba00ff))
- **progress-bar:** Minor adjutment to style calculation
  ([14819ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/14819efe6a5e5650f1d473ee4648c158a76988ea))
- **progress-bar:** remove unessesary this in template
  ([c04df8c](https://github.com/bootstrap-vue/bootstrap-vue/commit/c04df8c068f6ec0ebf3f9e6b51a44becc0e685dd))
- **radios checkboxes:** Parent group should emit change event
  ([#1071](https://github.com/bootstrap-vue/bootstrap-vue/issues/1071))
  ([ac7c506](https://github.com/bootstrap-vue/bootstrap-vue/commit/ac7c506ff74e1b94120c0ec2cfbfb953feeec315))
- **scrollspy:** fixes ffor various bugs
  ([#1063](https://github.com/bootstrap-vue/bootstrap-vue/issues/1063))
  ([97fccdd](https://github.com/bootstrap-vue/bootstrap-vue/commit/97fccdd116cf332d82cfbceebdfd3adf7c54803a))
- **scrollspy:** Handle .nav-link inside .nav-item active state
  ([6db094d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6db094d30ead62238b233aac127c2c772ce39f71))
- **scrollspy:** Handle nested nav-links when inside nav-item
  ([#1068](https://github.com/bootstrap-vue/bootstrap-vue/issues/1068))
  ([f4e017c](https://github.com/bootstrap-vue/bootstrap-vue/commit/f4e017ca9dc47c3f09805e39882d8971c2d45b2d))
- **scrollspy:** Make work with new nav-link functional component
  ([#909](https://github.com/bootstrap-vue/bootstrap-vue/issues/909))
  ([2ebba5d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2ebba5d90cf09bfe1454f742bff2de16fbb65df8))
- **scrollspy:** Minor updates
  ([95f0840](https://github.com/bootstrap-vue/bootstrap-vue/commit/95f08400621682218100c851c4d4a7a071331e8a))
- **scrollspy:** Minor updates
  ([ce15b69](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce15b69873d48aeedbd325573492fce3444226d8))
- **scrollspy:** Trigger refresh on transitionend event
  ([947b5e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/947b5e0facff2239a538a31c72546b1c388adf60))
- **scrollspy:** Undefined value during bind()
  ([#967](https://github.com/bootstrap-vue/bootstrap-vue/issues/967))
  ([5c35e07](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c35e079ec36e85549d5402762e84a78f33fb48a))
- **scrollspy:** Use new offset and position dom utilities
  ([dc68eef](https://github.com/bootstrap-vue/bootstrap-vue/commit/dc68eef97d5d7dbcbf1af93d2787bcb02a6723b0))
- **table:** filtered event not firing when filter cleared (issue
  [#859](https://github.com/bootstrap-vue/bootstrap-vue/issues/859))
  ([#863](https://github.com/bootstrap-vue/bootstrap-vue/issues/863))
  ([8ff2623](https://github.com/bootstrap-vue/bootstrap-vue/commit/8ff2623208eabf493e4590b8cc4e3353fe3eb19f))
- **table:** fix for row-hovered event
  ([2448666](https://github.com/bootstrap-vue/bootstrap-vue/commit/2448666487c4fb66d4ed2e9fb58db5014ee4ab0c))
- **tabs:** Better handling of active tab and transitions
  ([#903](https://github.com/bootstrap-vue/bootstrap-vue/issues/903))
  ([d5b81dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/d5b81dd9be766998a81430d5e6e0b4fc93df5fad))
- **tabs:** minor logic update
  ([add0fb6](https://github.com/bootstrap-vue/bootstrap-vue/commit/add0fb6185d056aac473e002f133c2af704f2f63))
- **tabs:** Show first tab when set to active
  ([#912](https://github.com/bootstrap-vue/bootstrap-vue/issues/912))
  ([d920b1c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d920b1c0f134d579fd1963defa66b0d5d7b79253))
- **tolltip+popover:** Hide original element title attribute
  ([#970](https://github.com/bootstrap-vue/bootstrap-vue/issues/970))
  ([82e46e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/82e46e64ce8ddc9a72ac6242b9a82cca392f2585)),
  closes [#955](https://github.com/bootstrap-vue/bootstrap-vue/issues/955)
- **tooltip:** remove deprecated target-id prop
  ([a06d5a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/a06d5a613ee1feaaaf3b7b538c8fd5c53f995d47))
- **tooltip:** ToolTip.fixTransition undefined value
  ([#960](https://github.com/bootstrap-vue/bootstrap-vue/issues/960))
  ([3c457e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c457e7e8618dc320449605aea7a7ae41c8497cd)),
  closes [#956](https://github.com/bootstrap-vue/bootstrap-vue/issues/956)
- **tooltip popover:** illegal invocation errors when tooltip inside v-if elements
  ([#1057](https://github.com/bootstrap-vue/bootstrap-vue/issues/1057))
  ([c1353a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/c1353a74c4e651487bbeab30be52b9748db559aa)),
  closes [#1032](https://github.com/bootstrap-vue/bootstrap-vue/issues/1032)
- Add lodash.startcase to dependancies
  ([febecfc](https://github.com/bootstrap-vue/bootstrap-vue/commit/febecfceb5207c191c7373598d3d76d4a5750010))
- **alert:** add missing colon for binding `aria-label`
  ([#768](https://github.com/bootstrap-vue/bootstrap-vue/issues/768))
  ([93b009f](https://github.com/bootstrap-vue/bootstrap-vue/commit/93b009fe65a610730767046e4b974b4ca0eac8c1))
- **alert:** Event args array in meta.json
  ([c9e3fd2](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9e3fd2a4808f2224520063f31289bff47f6813a))
- **alert:** use v-model to update show value
  ([#721](https://github.com/bootstrap-vue/bootstrap-vue/issues/721))
  ([9b380d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b380d076842187db1e0173db60da179109ae8ef))
- **badge:** badge default variant
  ([1403ec4](https://github.com/bootstrap-vue/bootstrap-vue/commit/1403ec402603329b815cc3acb3d739c3da7b18ea))
- **button:** Minor code update
  ([378b932](https://github.com/bootstrap-vue/bootstrap-vue/commit/378b93221e336fda809b768afe61d3d5fe77fcaf))
- **button-toolbar:** keynav better element visibility test
  ([5c33b8e](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c33b8e3f1e8c875d7e9b6af326cf5abf566fb6e))
- **button-toolbar:** Typo on property `keyNav`
  ([#600](https://github.com/bootstrap-vue/bootstrap-vue/issues/600))
  ([60b1fd8](https://github.com/bootstrap-vue/bootstrap-vue/commit/60b1fd8b75760fd1d0acaecdcca12bfbd5cffabc))
- **card:** change prop no-block to no-body
  ([#826](https://github.com/bootstrap-vue/bootstrap-vue/issues/826))
  ([664bc98](https://github.com/bootstrap-vue/bootstrap-vue/commit/664bc9814f51163c71e417684728faa843eb7430))
- **card:** Fix classes, variants, borders
  [v4-beta](<[#815](https://github.com/bootstrap-vue/bootstrap-vue/issues/815)>)
  ([fc26811](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc26811b7f7c3eec9b28f5a409a7aff12cb83082))
- **carousel:** boolean typo
  ([6a95410](https://github.com/bootstrap-vue/bootstrap-vue/commit/6a954102d13550bbf96a9c2a34f9c8e8d094ae76))
- **carousel:** Detect transitionend event name
  ([fa07949](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa0794919f54b94e5c114cf881d8da85317496bb))
- **carousel:** Ensure slideshow restarts when reaching the end
  ([e175c36](https://github.com/bootstrap-vue/bootstrap-vue/commit/e175c36599b8918db7bd79655737386f9770fc8f))
- **carousel:** ESLint
  ([8222222](https://github.com/bootstrap-vue/bootstrap-vue/commit/822222260d3928084db4ef587748afcdb94c921a))
- **carousel:** Handle changes in slide content
  ([#809](https://github.com/bootstrap-vue/bootstrap-vue/issues/809))
  ([6949e5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6949e5f764a0f0b3637257be908e92146224e763))
- **carousel:** minor fixes
  ([6b4f497](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b4f49790645af89aced04b2dc904f770d26268e))
- **carousel:** oldVal!
  ([3ae2e2e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ae2e2eb9ae40d7d203c8d40d67cb315fb2fe3de))
- **carousel:** Prevent going to slide if transitioning (issue
  [#764](https://github.com/bootstrap-vue/bootstrap-vue/issues/764))
  ([#765](https://github.com/bootstrap-vue/bootstrap-vue/issues/765))
  ([a2ab664](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2ab664a564353ac403888887aec1c18038d3d14))
- **carousel:** Typo
  ([4c80576](https://github.com/bootstrap-vue/bootstrap-vue/commit/4c80576eff2432d1ff0f428384aff740c01ce5ad))
- **carousel:** Unable to reach last slide
  ([3628bcb](https://github.com/bootstrap-vue/bootstrap-vue/commit/3628bcbaecf10d2e86d6677c82b7fbab27b3c0df))
- **collapse:** Close collapse when clicked in navbar
  ([#803](https://github.com/bootstrap-vue/bootstrap-vue/issues/803))
  ([3fdfbff](https://github.com/bootstrap-vue/bootstrap-vue/commit/3fdfbff8dd70573b9ee33acce2a47540a813fcaa))
- **collapse:** reference to this.$el
  ([eb01295](https://github.com/bootstrap-vue/bootstrap-vue/commit/eb012959ea220fbfedadf82f7a632ae5719c020a))
- **componentdoc:** Typo in required prop
  ([762d088](https://github.com/bootstrap-vue/bootstrap-vue/commit/762d08858e9825ea62cc5210e7ed1ac9f57967dc))
- **docs:** add root wrapper to templates
  ([ff6432d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff6432d2b1bfca7dad80152ad1363544d863de23))
- **docs:** Adjust header tags CSS specificity (issue
  [#753](https://github.com/bootstrap-vue/bootstrap-vue/issues/753))
  ([#755](https://github.com/bootstrap-vue/bootstrap-vue/issues/755))
  ([25280ae](https://github.com/bootstrap-vue/bootstrap-vue/commit/25280ae280127d7d69d12d770b8e4aa6958b27cc))
- **docs:** broken setup page
  ([9d60069](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d600698d2972dda0bf0e2c81676dd465a662707))
- **docs:** button update example
  ([#804](https://github.com/bootstrap-vue/bootstrap-vue/issues/804))
  ([fb375aa](https://github.com/bootstrap-vue/bootstrap-vue/commit/fb375aaf60fae17364b54f57730a688eb6045828))
- **docs:** Collapse meta.jso typo fix
  ([6191bed](https://github.com/bootstrap-vue/bootstrap-vue/commit/6191bed13b8245a8235c12138743585436c25ad4))
- **docs:** conform args and fix spelling
  ([#659](https://github.com/bootstrap-vue/bootstrap-vue/issues/659))
  ([ed9906a](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed9906ad9940a59d08fb158a1a952f24584d2159))
- **docs:** fix invalid JSON trailing commas
  ([a635176](https://github.com/bootstrap-vue/bootstrap-vue/commit/a63517644a4d9c4a7ca29b4d00f4d238c0bafc98))
- **docs:** Fix ScrollSpy example
  ([0365208](https://github.com/bootstrap-vue/bootstrap-vue/commit/036520815640bdb3f005f93ca0ade571867b5ba1))
- **docs:** Fix typo in \_component.vue
  ([b90e92a](https://github.com/bootstrap-vue/bootstrap-vue/commit/b90e92a0a1ebf0b6a84da772f7a5724e26680b13))
- **docs:** form-radio typo fix
  ([db6d5d7](https://github.com/bootstrap-vue/bootstrap-vue/commit/db6d5d7d92042e01c125395cf8249fa4ff67c6af))
- **docs:** form-select docs typo fix
  ([630e02f](https://github.com/bootstrap-vue/bootstrap-vue/commit/630e02fae24c5ce152cc8107cac10eba558d3358))
- **docs:** Minor update to file-input example
  ([763a35a](https://github.com/bootstrap-vue/bootstrap-vue/commit/763a35a4669eedc27bd3c5ebae21edadeddde4f0))
- **docs:** Minor update to navbar example
  ([4a62e1b](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a62e1bcb48c7055fc36495f6b03954b5ed30c58))
- **docs:** myToggle0
  ([a0ef988](https://github.com/bootstrap-vue/bootstrap-vue/commit/a0ef988f9d6d06f8140db97d4197f33a41af98f0))
- **docs:** serve fonts on https
  ([51209dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/51209dd9cc8b0a9d4d5d7a39e6faa57c6a183b18))
- **docs:** table example markup
  ([d3d7437](https://github.com/bootstrap-vue/bootstrap-vue/commit/d3d74371b392e5da527f1c37525c16af81114a5c))
- **docs:** typo in button docs
  ([8cd3ea1](https://github.com/bootstrap-vue/bootstrap-vue/commit/8cd3ea17b14bd875e301c192405d7a92b5a1c0f8))
- **docs:** update README.md for Bootstrap version
  ([#692](https://github.com/bootstrap-vue/bootstrap-vue/issues/692))
  ([5165531](https://github.com/bootstrap-vue/bootstrap-vue/commit/516553105f32edb86e2d5d8529560f275a938e7c))
- **docs.vue:** Fix link to edit setup doc
  ([#641](https://github.com/bootstrap-vue/bootstrap-vue/issues/641))
  ([836db33](https://github.com/bootstrap-vue/bootstrap-vue/commit/836db334861846006a7d0cbf1498dc0e14d5be42)),
  closes [#639](https://github.com/bootstrap-vue/bootstrap-vue/issues/639)
- **dropdown:** Clear leftover active state on menu open (fixes
  [#664](https://github.com/bootstrap-vue/bootstrap-vue/issues/664))
  ([80c1ceb](https://github.com/bootstrap-vue/bootstrap-vue/commit/80c1cebd001f6c109c386c3589c5fe7b6781dc0f))
- **dropdown:** Emit shown and hidden events (issue
  [#757](https://github.com/bootstrap-vue/bootstrap-vue/issues/757))
  ([814e94c](https://github.com/bootstrap-vue/bootstrap-vue/commit/814e94c1cd2bdb71c610d36751ae4aa123a5ba23))
- **dropdown:** Fix focus/hover custom CSS
  ([0cbbfb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/0cbbfb5ae436eaf8cba0817212d2750820e94b39))
- **dropdown:** focus on first item on show
  ([40a1347](https://github.com/bootstrap-vue/bootstrap-vue/commit/40a13474682fdaf729d3279f4ece478b37a62321))
- **dropdown:** twbs/bootstrap[#23329](https://github.com/bootstrap-vue/bootstrap-vue/issues/23329)
  ([fab5d22](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab5d2291f8fdfba19058f76b165ea05d275582f))
- **dropdowns:** Change how dropdown items are highlighted
  ([#717](https://github.com/bootstrap-vue/bootstrap-vue/issues/717))
  ([a02270e](https://github.com/bootstrap-vue/bootstrap-vue/commit/a02270ef2d27b21c419b5e8a9906fce2d884d7cc))
- **dropdowns:** Focus dropdown item on hover
  ([#823](https://github.com/bootstrap-vue/bootstrap-vue/issues/823))
  ([2e863d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/2e863d9296ff409a69c0f8dabcc28153e4efdaf7))
- **form:** Emit native submit on component
  ([#636](https://github.com/bootstrap-vue/bootstrap-vue/issues/636))
  ([0ba6f94](https://github.com/bootstrap-vue/bootstrap-vue/commit/0ba6f94ae91f2dc24f73e5243def7d8183700ae4)),
  closes [#588](https://github.com/bootstrap-vue/bootstrap-vue/issues/588)
- **form controls:** Apply only required props & classes
  ([#609](https://github.com/bootstrap-vue/bootstrap-vue/issues/609))
  ([c773f79](https://github.com/bootstrap-vue/bootstrap-vue/commit/c773f7991bdd432eeb2cff4a9b4d11042b30efd4))
- **form fieldset:** 'label for' prop not being applied to label - ARIA
  ([#669](https://github.com/bootstrap-vue/bootstrap-vue/issues/669))
  ([aafea81](https://github.com/bootstrap-vue/bootstrap-vue/commit/aafea81676adabdc3fd0a633658481e596f1c667))
- **form-checkbox:** Better focus handling in button mode
  ([06e1c7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/06e1c7bb895983a30288e24441da4f7ab654bc39))
- **form-checkbox:** Remove duplicate computed prop
  ([f47ab79](https://github.com/bootstrap-vue/bootstrap-vue/commit/f47ab794c7afc7294faa5b479fd00a9e4c60af17))
- **form-control-static:** change class to form-control-plaintext
  ([66eda01](https://github.com/bootstrap-vue/bootstrap-vue/commit/66eda01a74477e6710d78e18c02755b95dfa3b09))
- **form-file:** remove inputClass
  ([2415617](https://github.com/bootstrap-vue/bootstrap-vue/commit/24156177890d40277e9a14086df79be937880a38))
- **form-input:** Fix reactivity (issue
  [#817](https://github.com/bootstrap-vue/bootstrap-vue/issues/817))
  ([88e2dbb](https://github.com/bootstrap-vue/bootstrap-vue/commit/88e2dbbd78e2c0651d688fe1eb9abff93e2f806d))
- **form-input:** isTextArea varname correction
  ([#785](https://github.com/bootstrap-vue/bootstrap-vue/issues/785))
  ([cb44652](https://github.com/bootstrap-vue/bootstrap-vue/commit/cb44652f2e49b6399bd12cb31b1575f94922b666))
- **form-options:** pull out custom text field for object notation
  ([#625](https://github.com/bootstrap-vue/bootstrap-vue/issues/625))
  ([83cec54](https://github.com/bootstrap-vue/bootstrap-vue/commit/83cec5463818261ad13d5514e8d3357f24cd3b22)),
  closes [#622](https://github.com/bootstrap-vue/bootstrap-vue/issues/622)
- **form-radio:** Add missing classes in button mode
  ([#779](https://github.com/bootstrap-vue/bootstrap-vue/issues/779))
  ([ed4f4ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed4f4ef80b9ac0d7bab06998be65b672cd89f3b5))
- **form-radio:** Better focus handling in button mode
  ([#801](https://github.com/bootstrap-vue/bootstrap-vue/issues/801))
  ([a9bfbde](https://github.com/bootstrap-vue/bootstrap-vue/commit/a9bfbde2f666d9cbb7e20deb256fefbe1fa23423))
- **form-radio:** extra this in template
  ([cc4a442](https://github.com/bootstrap-vue/bootstrap-vue/commit/cc4a4421e07eaa00ad71d38327d445c8de269d0f))
- **form-radio:** isChecked to work with arrays & non-arrays.
  ([#629](https://github.com/bootstrap-vue/bootstrap-vue/issues/629))
  ([578d451](https://github.com/bootstrap-vue/bootstrap-vue/commit/578d451b820b502013c96e492c1ca01a32b7fc6a)),
  closes [#623](https://github.com/bootstrap-vue/bootstrap-vue/issues/623)
- **form-radio, form-checkbox:** Set autocomplete off
  ([#616](https://github.com/bootstrap-vue/bootstrap-vue/issues/616))
  ([e127313](https://github.com/bootstrap-vue/bootstrap-vue/commit/e127313e4c07403a160486bba9665380f93cbc7d))
- **modal:** Event args list in meta.json
  ([7b8ce01](https://github.com/bootstrap-vue/bootstrap-vue/commit/7b8ce0162e8bd4a35e3822a4c6b811aa7bc047f0))
- **modal:** meta.json property order consistency
  ([3d204a4](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d204a41ddc51c808d3557963e7018508a008c0e))
- **modal:** use listenOnRoot mixin
  ([#593](https://github.com/bootstrap-vue/bootstrap-vue/issues/593))
  ([531a6ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/531a6abff10b346079e84c9a0642ed1f83418ef1))
- **nav-item-dropdown:** add show class
  ([921dac5](https://github.com/bootstrap-vue/bootstrap-vue/commit/921dac5d7991529d1d855e9f4b88157914d5c029))
- **nav-toggle:** typo in method name
  ([5e0bb2a](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e0bb2abda48784664839e9b50a1cc97c1069b1d))
- **navbar-brand:** Refactored component logic
  ([#759](https://github.com/bootstrap-vue/bootstrap-vue/issues/759))
  ([c752fc8](https://github.com/bootstrap-vue/bootstrap-vue/commit/c752fc83c367a63e0c573ddc716ac58096d86a29))
- **navbar-brand:** Removed erroneous this in template
  ([#806](https://github.com/bootstrap-vue/bootstrap-vue/issues/806))
  ([0842043](https://github.com/bootstrap-vue/bootstrap-vue/commit/084204349863822cdabd66a7d7c07b07fdf989ab))
- **pagination:** Added missing href & ARIA adjustments
  ([#693](https://github.com/bootstrap-vue/bootstrap-vue/issues/693))
  ([7091262](https://github.com/bootstrap-vue/bootstrap-vue/commit/7091262e3cc757e0cb72a4d00472084d3aead91c))
- **pagination:** Improved ARIA roles and attributes
  ([#741](https://github.com/bootstrap-vue/bootstrap-vue/issues/741))
  ([b12b06e](https://github.com/bootstrap-vue/bootstrap-vue/commit/b12b06edb0fe349ff2aed6e1e76ca965d8e0ce45))
- **popover.js:** destroy check for trigger & classes (issue
  [#735](https://github.com/bootstrap-vue/bootstrap-vue/issues/735))
  ([30fa778](https://github.com/bootstrap-vue/bootstrap-vue/commit/30fa7789378d1d9943ba9bba94d79dff3141c15d))
- **root-listeners:** apply listen-on-root mixin to other components
  ([#684](https://github.com/bootstrap-vue/bootstrap-vue/issues/684))
  ([f2b7b44](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2b7b44a08d6ca8b8878b06b00dc430fce2d0836))
- **scrollspy:** Adjust throttle default
  ([3d6eb98](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d6eb980a4cac0d2cac5d740ac4599140675669c))
- **scrollspy:** Adjustments to the resizeThrottle scheduler
  ([#640](https://github.com/bootstrap-vue/bootstrap-vue/issues/640))
  ([bfaef7d](https://github.com/bootstrap-vue/bootstrap-vue/commit/bfaef7d7d578d5c99249786c902edc4f0181a7e3))
- **table:** aria-labeledby set to header element
  ([e13e093](https://github.com/bootstrap-vue/bootstrap-vue/commit/e13e093624f6659f9e500e3ca9cdb20a2eb893a3))
- **table:** Remove redundant ARIA roles from b-table
  ([#662](https://github.com/bootstrap-vue/bootstrap-vue/issues/662))
  ([6919cc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/6919cc5a026f1168df5ea29d98aed3d01e40afce))
- **table:** Sorting directions & arrows
  ([de1de97](https://github.com/bootstrap-vue/bootstrap-vue/commit/de1de97e8b7b4d0f99546fce9e39f790244934d7))
- **table:** workaround for Vue 2.4 SSR rendering bug
  ([ab7767f](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab7767f689a6c2b17b38ff350a448f6c888806b8))
- **table:** workaround for Vue 2.4 SSR rendering bug
  ([dc8d238](https://github.com/bootstrap-vue/bootstrap-vue/commit/dc8d23898d52a839fd3bad9ac1631b00026feb9b))
- **table demo.html:** remove deprecated fieldset prop
  ([#630](https://github.com/bootstrap-vue/bootstrap-vue/issues/630))
  ([18e8547](https://github.com/bootstrap-vue/bootstrap-vue/commit/18e85477576769b4dd564b02ffd55adb1fb70303))
- **tabs:** Default current tab to null (issue
  [#687](https://github.com/bootstrap-vue/bootstrap-vue/issues/687))
  ([#701](https://github.com/bootstrap-vue/bootstrap-vue/issues/701))
  ([bc7ca26](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc7ca26a71316b17d537b6b69d6dc58542f6d7f9))
- **tabs:** Remove aria-expanded in favor of aria-seleted
  ([5790b39](https://github.com/bootstrap-vue/bootstrap-vue/commit/5790b39bb8f470300026a294f097db01ae1cf073))
- **tabs:** Tabls not clickable (issue
  [#789](https://github.com/bootstrap-vue/bootstrap-vue/issues/789))
  ([#790](https://github.com/bootstrap-vue/bootstrap-vue/issues/790))
  ([c234580](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2345805245b2b485bd282919064feef6a6238df))
- **tabs:** update to use card-block
  ([d881c37](https://github.com/bootstrap-vue/bootstrap-vue/commit/d881c379db18f2026e6f2bb3e1f229d961965f47))
- **tests:** Set jest max workers to 1
  ([f16fd8d](https://github.com/bootstrap-vue/bootstrap-vue/commit/f16fd8deef6ce922ffb68b0c227a572fbe4d15cf))
- **toggle:** Remove $root listener on unbind (Issue
  [#680](https://github.com/bootstrap-vue/bootstrap-vue/issues/680))
  ([#698](https://github.com/bootstrap-vue/bootstrap-vue/issues/698))
  ([ec5000c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec5000c0eca49df98b0399c90f5a6d57145247bb))
- **tooltip:** Emit correct $root event name
  ([#1094](https://github.com/bootstrap-vue/bootstrap-vue/issues/1094))
  ([87e5eb2](https://github.com/bootstrap-vue/bootstrap-vue/commit/87e5eb29e889f4910cf34e77f65e467ddb6f200c))
- **tooltip:** visibility check
  ([df4a015](https://github.com/bootstrap-vue/bootstrap-vue/commit/df4a0159fd4f2b3c274d580196994a2a688e68bb))
- **tooltip-popover:** Click not triggered for elements with inner HTML elements in Chrome
  ([#1006](https://github.com/bootstrap-vue/bootstrap-vue/issues/1006))
  ([39caf8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/39caf8ad40c80e2e350a4b92de3104b8d135115f)),
  closes [#1005](https://github.com/bootstrap-vue/bootstrap-vue/issues/1005)
- **tooltip+popover:** Check if trigger element is in DOM during vsibility check
  ([55c4ff0](https://github.com/bootstrap-vue/bootstrap-vue/commit/55c4ff03a8994ddb273923d02f577935fb8d7480))
- **tooltip+popover:** Hide tooltip/popover when $route changes
  ([#965](https://github.com/bootstrap-vue/bootstrap-vue/issues/965))
  ([e403225](https://github.com/bootstrap-vue/bootstrap-vue/commit/e403225194161d9ce71e349e6d84508093549eb6)),
  closes [#964](https://github.com/bootstrap-vue/bootstrap-vue/issues/964)
- **tooltip+popover:** Remove relatedTarget on hidden event object
  ([8af36ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/8af36ba2d29a71dfb2e08553eee03f8753748f97))
- Remove usage of es2015 Array.prototype.includes
  ([#589](https://github.com/bootstrap-vue/bootstrap-vue/issues/589))
  ([b3fc095](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3fc0950f907ef9bbcac6a92c6be1d5aec2af0dd))
- this is not defined in props
  ([fe4ff06](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe4ff063fb505a0277e5cb10e93bfec54e2b9723))
- **tooltip:** inline-block element for wrappers
  ([#572](https://github.com/bootstrap-vue/bootstrap-vue/issues/572))
  ([4b680ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b680eeac32f635c9b898e1d5c6704db2401d437)),
  closes [#571](https://github.com/bootstrap-vue/bootstrap-vue/issues/571)
- **tooltip+popover:** improve blur trigger handling
  ([c08b815](https://github.com/bootstrap-vue/bootstrap-vue/commit/c08b815266976564ba5ebb3eab3df0c05e6693db))
- **tooltip+popover:** Prevent leftover tooltip/popover divs
  ([f8cdf26](https://github.com/bootstrap-vue/bootstrap-vue/commit/f8cdf2693e2aa7e00cb5a786dfb01b33fda3863d)),
  closes [#1208](https://github.com/bootstrap-vue/bootstrap-vue/issues/1208)
- **tooltip+popover components:** Delay instantiation on mounted()
  ([#969](https://github.com/bootstrap-vue/bootstrap-vue/issues/969))
  ([4fc18ec](https://github.com/bootstrap-vue/bootstrap-vue/commit/4fc18ec3c54f04ebcf207a6de2043518b86d4d83))
- **tooltip+popover components:** Emit events and minor adjustments
  ([#972](https://github.com/bootstrap-vue/bootstrap-vue/issues/972))
  ([cf7c538](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf7c53853f27856614af6790a6a8893bd8c644a0))
- **v-play:** disable vue global errorHandler
  ([9a7bdaf](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a7bdaffb5c77b4783af2ab56f87c220174a444c))

* feat, docs: update input-group to BS 4.0.0.
  ([790c0de](https://github.com/bootstrap-vue/bootstrap-vue/commit/790c0de95125f7c4b6cb9328a488c70f36007a55))
* Dropdown ARIA keyboard nav (#274)
  ([d1a676a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d1a676a873e5f73df82e564a033c5929d749a3ca)),
  closes [#274](https://github.com/bootstrap-vue/bootstrap-vue/issues/274)

### misc

- better packaging of css files
  ([87edbb9](https://github.com/bootstrap-vue/bootstrap-vue/commit/87edbb9d71bf2b5fa6b3ccb649724176fa3a1a15))

### Performance

- **alert:** convert template to render function
  ([#1308](https://github.com/bootstrap-vue/bootstrap-vue/issues/1308))
  ([8b0c7cd](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b0c7cda9f43453a964b5457b88c822f74341bb6))
- **b-link:** convert functional component to regular component (addresses
  [#3634](https://github.com/bootstrap-vue/bootstrap-vue/issues/3634))
  ([#3637](https://github.com/bootstrap-vue/bootstrap-vue/issues/3637))
  ([d3641ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/d3641ba7dd6b90929499cf099dbeb7855b8119ed))
- **b-table:** cache cell slot names each render cycle (addresses
  [#4008](https://github.com/bootstrap-vue/bootstrap-vue/issues/4008))
  ([#4011](https://github.com/bootstrap-vue/bootstrap-vue/issues/4011))
  ([78c604c](https://github.com/bootstrap-vue/bootstrap-vue/commit/78c604c6f4b5987f04ed86f272e6dc5922069bca))
- **b-table, b-table-lite:** delegate row event handlers to the tbody element
  ([#4192](https://github.com/bootstrap-vue/bootstrap-vue/issues/4192))
  ([3f0d46a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f0d46a3afb5113d60a9624729a675af1d42ccd0))
- **b-table, b-table-lite:** improve render performance (closes
  [#4211](https://github.com/bootstrap-vue/bootstrap-vue/issues/4211),
  [#4155](https://github.com/bootstrap-vue/bootstrap-vue/issues/4155))
  ([#4213](https://github.com/bootstrap-vue/bootstrap-vue/issues/4213))
  ([f3f42f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/f3f42f2780d56db2b7f6f89bd0af007f8f652668))
- **build:** reduce minified code size
  ([#1337](https://github.com/bootstrap-vue/bootstrap-vue/issues/1337))
  ([9d0ae3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d0ae3e0c28d7289ac2c45dead9516e926b02e59))
- **button-toolbar:** convert template to render function
  ([#1315](https://github.com/bootstrap-vue/bootstrap-vue/issues/1315))
  ([765bfe3](https://github.com/bootstrap-vue/bootstrap-vue/commit/765bfe3b1baff692946b432547ae048db3ed1f17))
- **carousel:** convert templates to render functions
  ([#1339](https://github.com/bootstrap-vue/bootstrap-vue/issues/1339))
  ([13f429f](https://github.com/bootstrap-vue/bootstrap-vue/commit/13f429fc7b577552ab92a3e8c1db1c8eeaf153dd))
- **collapse:** convert template to render function
  ([#1316](https://github.com/bootstrap-vue/bootstrap-vue/issues/1316))
  ([722ea12](https://github.com/bootstrap-vue/bootstrap-vue/commit/722ea128a038ee61b70029b6f88a0a28b5ef8b61))
- **docs:** Better TOC SSR generation
  ([#1080](https://github.com/bootstrap-vue/bootstrap-vue/issues/1080))
  ([b3489d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3489d0ee9811d0d668444102f84f895c5701ade))
- **docs:** lodash dependency
  ([a02f10d](https://github.com/bootstrap-vue/bootstrap-vue/commit/a02f10d6375e506377a066d7f29087934be571ef))
- **docs:** only import debounce from lodash
  ([a6abd6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/a6abd6dee748083f764bb867b13e8a568af1e0f4))
- **dom:** Improve DOM utils code for minification & tree-shaking
  ([#1284](https://github.com/bootstrap-vue/bootstrap-vue/issues/1284))
  ([e1e701b](https://github.com/bootstrap-vue/bootstrap-vue/commit/e1e701ba4ec8850117ccd5d983dc47898f961abb))
- **dropdown:** changed 'this' to 't'
  ([#1500](https://github.com/bootstrap-vue/bootstrap-vue/issues/1500))
  ([ace3e94](https://github.com/bootstrap-vue/bootstrap-vue/commit/ace3e94a0b5724ea37954d7fd784086c2fe57155))
- **dropdowns:** convert templates to render functions
  ([#1314](https://github.com/bootstrap-vue/bootstrap-vue/issues/1314))
  ([3168e93](https://github.com/bootstrap-vue/bootstrap-vue/commit/3168e93f1c70d2064a7afe8bfa2d3965ec440f65))
- **dropdowns:** use non reactive property to store popper.js instance
  ([#1416](https://github.com/bootstrap-vue/bootstrap-vue/issues/1416))
  ([379d9a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/379d9a821fbbf1b1064cc69a46c8ecf14417baac))
- **events:** use passive event listeners where possible
  ([#2435](https://github.com/bootstrap-vue/bootstrap-vue/issues/2435))
  ([a01dee4](https://github.com/bootstrap-vue/bootstrap-vue/commit/a01dee40b6282797cd51cfb3163be8928dfa6ece))
- **form-checkboxes:** convert templates to render functions
  ([#1338](https://github.com/bootstrap-vue/bootstrap-vue/issues/1338))
  ([49bc50b](https://github.com/bootstrap-vue/bootstrap-vue/commit/49bc50b65b77f4a0445ec6b7f7df32d254559341))
- **form-file:** convert template to render function
  ([#1329](https://github.com/bootstrap-vue/bootstrap-vue/issues/1329))
  ([ec96f82](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec96f820a5840c90af00b7e1f7d2859cbaee6570))
- **form-group:** convert template to render function
  ([#1332](https://github.com/bootstrap-vue/bootstrap-vue/issues/1332))
  ([f409392](https://github.com/bootstrap-vue/bootstrap-vue/commit/f4093925525876b2deea9cf428607f230aff8442))
- **form-input:** convert template to render function
  ([#1330](https://github.com/bootstrap-vue/bootstrap-vue/issues/1330))
  ([12f0423](https://github.com/bootstrap-vue/bootstrap-vue/commit/12f04236cd944a0ba0784bb5d5737840a4454d19))
- **form-radios:** convert templates to render functions
  ([#1336](https://github.com/bootstrap-vue/bootstrap-vue/issues/1336))
  ([3a2aa0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a2aa0a19024ce1454e5d62f513fd8bc9a6a4707))
- **form-select:** convert template to render function
  ([#1333](https://github.com/bootstrap-vue/bootstrap-vue/issues/1333))
  ([9adfc12](https://github.com/bootstrap-vue/bootstrap-vue/commit/9adfc1268b53d3529907bb50588fcbe2188a2f86))
- **form-textarea:** convert template to render function
  ([#1331](https://github.com/bootstrap-vue/bootstrap-vue/issues/1331))
  ([5293e71](https://github.com/bootstrap-vue/bootstrap-vue/commit/5293e7161074e73d12521b76a3270c7d4a5d6b7e))
- **id mixin:** make localId\_ a computed field
  ([873b0e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/873b0e7164a834cb5cc4f62696e453c37dcf0ce0))
- **modal:** convert template to render function
  ([#1340](https://github.com/bootstrap-vue/bootstrap-vue/issues/1340))
  ([bb7ec04](https://github.com/bootstrap-vue/bootstrap-vue/commit/bb7ec04740c148475d2595216c25ae1b705baf36))
- **modal:** Get scrollbar width just before modal opens rather than mount (fixes
  [#1800](https://github.com/bootstrap-vue/bootstrap-vue/issues/1800))
  ([#2165](https://github.com/bootstrap-vue/bootstrap-vue/issues/2165))
  ([e1729b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/e1729b476c2b29f93d8c5a6c88f64e823bc60727))
- **modal:** optimize model.resetScrollbar, resolves
  [#1831](https://github.com/bootstrap-vue/bootstrap-vue/issues/1831)
  ([#1837](https://github.com/bootstrap-vue/bootstrap-vue/issues/1837))
  ([a622358](https://github.com/bootstrap-vue/bootstrap-vue/commit/a622358444cdb494fe04c025d88b07996edfe2fc))
- **pkg:** remove lodash dependency from src
  ([#2523](https://github.com/bootstrap-vue/bootstrap-vue/issues/2523))
  ([b34ada3](https://github.com/bootstrap-vue/bootstrap-vue/commit/b34ada3c362c7fb50387f772c7b7d69860c49092))
- **progress:** use provide and inject for inter component communication
  ([#2540](https://github.com/bootstrap-vue/bootstrap-vue/issues/2540))
  ([80b7e5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/80b7e5fed6be1f14ffe30ff827afe638962b502b))
- **table:** improve provide/inject performance (addresses
  [#4155](https://github.com/bootstrap-vue/bootstrap-vue/issues/4155))
  ([#4164](https://github.com/bootstrap-vue/bootstrap-vue/issues/4164))
  ([152fefc](https://github.com/bootstrap-vue/bootstrap-vue/commit/152fefc8638008e9d0b43c80fb512ceb8e822b78))
- **tables:** make `b-th` extend `b-td` instead of using functional wrappers
  ([#4156](https://github.com/bootstrap-vue/bootstrap-vue/issues/4156))
  ([c9715a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9715a89b1d693974dff8db7e24f97cdf908ff99))
- add event KeyCode constants in utils
  ([#1346](https://github.com/bootstrap-vue/bootstrap-vue/issues/1346))
  ([714d748](https://github.com/bootstrap-vue/bootstrap-vue/commit/714d74881982bade01d0f6f0540eefaacb570f83))
- evalute slots() once in functional component render functions
  ([#1438](https://github.com/bootstrap-vue/bootstrap-vue/issues/1438))
  ([3c42477](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c42477137a4d4459c5d16b4c138426bd3121442))
- only call vueUse in main index.js entrypoint
  ([#2542](https://github.com/bootstrap-vue/bootstrap-vue/issues/2542))
  ([c0d469b](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0d469b833d42abe2f81c17dac5886ed11429942))
- remove default array/object polyfills
  ([#3641](https://github.com/bootstrap-vue/bootstrap-vue/issues/3641))
  ([8b34bf2](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b34bf21965332b6f85dc229b39e140908dcb192))
- use re-usable fade transition component
  ([#3281](https://github.com/bootstrap-vue/bootstrap-vue/issues/3281))
  ([ceeb70e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ceeb70e3509db158e3ce91318b9333ef94449056))
- **img-lazy:** convert template to render function
  ([#1309](https://github.com/bootstrap-vue/bootstrap-vue/issues/1309))
  ([1736eb9](https://github.com/bootstrap-vue/bootstrap-vue/commit/1736eb943c10f05a9df5d4ba066fb77cdd2e741e))
- **input-group:** convert to functional component
  ([#1288](https://github.com/bootstrap-vue/bootstrap-vue/issues/1288))
  ([bd4c3c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd4c3c38ce0c4317b8a95e1ab4bae3ef06bd61ea))
- **navbar-toggle:** convert template to render function
  ([#1313](https://github.com/bootstrap-vue/bootstrap-vue/issues/1313))
  ([88657fb](https://github.com/bootstrap-vue/bootstrap-vue/commit/88657fba257e2d43b9ff1d848f6fd184c1c07074))
- **navbar-toggle:** Remove unused code
  ([1e95383](https://github.com/bootstrap-vue/bootstrap-vue/commit/1e95383959e48b6f926738b4d600967879c5c354))
- **pagination:** Move common code to pagination mixin
  ([#1069](https://github.com/bootstrap-vue/bootstrap-vue/issues/1069))
  ([0d41e83](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d41e830974867fac21969bebb059174ab70c0c5))
- **pagination+pagination-nav:** convert templates to render function
  ([#1348](https://github.com/bootstrap-vue/bootstrap-vue/issues/1348))
  ([e04291f](https://github.com/bootstrap-vue/bootstrap-vue/commit/e04291f0aac2014059b27e09e1c1bb9ab825f70c))
- **popover:** convert template to render function
  ([#1311](https://github.com/bootstrap-vue/bootstrap-vue/issues/1311))
  ([de24eec](https://github.com/bootstrap-vue/bootstrap-vue/commit/de24eecd2139c88afc365235ad795f7b1818c93c))
- **progress:** convert template to render function
  ([#1312](https://github.com/bootstrap-vue/bootstrap-vue/issues/1312))
  ([20d7d0b](https://github.com/bootstrap-vue/bootstrap-vue/commit/20d7d0b1db95944f608073751244d16fa2cbce6e))
- **table:** convert template to render function
  ([#1350](https://github.com/bootstrap-vue/bootstrap-vue/issues/1350))
  ([6a1ef4f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6a1ef4f99370b34731e5e74ec48a7726714447fb))
- **table:** minor tweaks to primary key usage
  ([#2741](https://github.com/bootstrap-vue/bootstrap-vue/issues/2741))
  ([d083385](https://github.com/bootstrap-vue/bootstrap-vue/commit/d08338575590876248fb90d06d5ffa24c204d566))
- **tabs:** convert templates to render functions
  ([#1319](https://github.com/bootstrap-vue/bootstrap-vue/issues/1319))
  ([b45f550](https://github.com/bootstrap-vue/bootstrap-vue/commit/b45f550e9d5978402b1880b710c8687d75ac19fc))
- **tooltip:** convert template to render function
  ([#1310](https://github.com/bootstrap-vue/bootstrap-vue/issues/1310))
  ([c812cb0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c812cb0996993ceeea8e80a7f7084462a9929dac))
- **utils/dom:** use passive event listeners where possible
  ([#2419](https://github.com/bootstrap-vue/bootstrap-vue/issues/2419))
  ([78fe776](https://github.com/bootstrap-vue/bootstrap-vue/commit/78fe776496953c617e6dedf9be409f30245c0a21))
- Move redudant code into plugin utility
  ([#1272](https://github.com/bootstrap-vue/bootstrap-vue/issues/1272))
  ([779b70d](https://github.com/bootstrap-vue/bootstrap-vue/commit/779b70d166981906143b34e3220adb96a626c8b3))
- move repetitive plugin code to plugin.js
  ([#1285](https://github.com/bootstrap-vue/bootstrap-vue/issues/1285))
  ([6ba8c46](https://github.com/bootstrap-vue/bootstrap-vue/commit/6ba8c46da4b8abca145970bc506718c8a73b14b8))

## 3.0.0 (2024-02-01)

### ⚠ BREAKING CHANGES

- Requires changing build scripts to include css-loader when using indivitual components
- left and right changed into prepend and append. See docs.
- Prop `rightAlignment` is now just `right`, aligning with `b-dropdown.`s props

- Minor fixes

- Missing period in selector

- Fixed missing closing ]

- Minor adjustments

### Features

- **`b-overlay`:** new component `b-overlay`
  ([#4907](https://github.com/bootstrap-vue/bootstrap-vue/issues/4907))
  ([134d64d](https://github.com/bootstrap-vue/bootstrap-vue/commit/134d64d073bb64fecd74ffc521476bfd97a99fc0))
- **b-aspect:** new custom component `<b-aspect>`
  ([#5008](https://github.com/bootstrap-vue/bootstrap-vue/issues/5008))
  ([662c8e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/662c8e0709c8c73fb2119976d1906943cfe6daad))
- **b-avatar:** add `alt` prop for adding alt attribute to image and icon avatars (closes
  [#4990](https://github.com/bootstrap-vue/bootstrap-vue/issues/4990))
  ([#4991](https://github.com/bootstrap-vue/bootstrap-vue/issues/4991))
  ([d1474f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/d1474f28729e4e13ad97b75a87d56f85543d4c96))
- **b-avatar:** add size classes for `sm` and `lg` sizes (closes
  [#5592](https://github.com/bootstrap-vue/bootstrap-vue/issues/5592))
  ([#5768](https://github.com/bootstrap-vue/bootstrap-vue/issues/5768))
  ([942bf31](https://github.com/bootstrap-vue/bootstrap-vue/commit/942bf31546179abce8f0bb8252f8716c85c6de86))
- **b-avatar:** and support for badges on avatars
  ([#5124](https://github.com/bootstrap-vue/bootstrap-vue/issues/5124))
  ([a2e465b](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2e465b6457cabb88e42bcefd86a86e36c4602de))
- **b-avatar:** if img `src` fails to load, show icon or text or fallback icon
  ([#5064](https://github.com/bootstrap-vue/bootstrap-vue/issues/5064))
  ([5fc5771](https://github.com/bootstrap-vue/bootstrap-vue/commit/5fc5771deaffb5f0d4c14a5f2e93d86f2c0d3871))
- **b-avatar:** if img `src` fails to load, then show icon, text or fallback icon
  ([#5079](https://github.com/bootstrap-vue/bootstrap-vue/issues/5079))
  ([ed6704d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed6704d0971ade485393b7f711f05d93ca42ebc3))
- **b-avatar:** if variant is empty string, then remove spacing around image (closes
  [#5154](https://github.com/bootstrap-vue/bootstrap-vue/issues/5154))
  ([#5156](https://github.com/bootstrap-vue/bootstrap-vue/issues/5156))
  ([7ff87fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ff87fc560a2ad005bdca394cccf1fafa9d5e696))
- **b-avatar-group:** new helper component b-avatar-group
  ([#5272](https://github.com/bootstrap-vue/bootstrap-vue/issues/5272))
  ([c84faae](https://github.com/bootstrap-vue/bootstrap-vue/commit/c84faaebe18bbf652583d6c302447e931a4ab741))
- **b-button-close:** add `content` prop
  ([#4574](https://github.com/bootstrap-vue/bootstrap-vue/issues/4574))
  ([7379c6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7379c6dd0bac76307720645080741b3b0ed7ed99))
- **b-calendar:** add `nav-button-variant` prop (closes
  [#5702](https://github.com/bootstrap-vue/bootstrap-vue/issues/5702))
  ([#5705](https://github.com/bootstrap-vue/bootstrap-vue/issues/5705))
  ([aa291fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/aa291fce6df52df4d2396b9499c964ce0ac5962b))
- **b-calendar:** add `no-key-nav` property (closes
  [#5861](https://github.com/bootstrap-vue/bootstrap-vue/issues/5861))
  ([#5883](https://github.com/bootstrap-vue/bootstrap-vue/issues/5883))
  ([955ad63](https://github.com/bootstrap-vue/bootstrap-vue/commit/955ad631698f82a83de214ce9cd37271367d8c45))
- **b-calendar, b-form-datepicker:** add optional decade navigation buttons (addresses
  [#4976](https://github.com/bootstrap-vue/bootstrap-vue/issues/4976))
  ([#5112](https://github.com/bootstrap-vue/bootstrap-vue/issues/5112))
  ([b1f74a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/b1f74a84f4021022e606360ee6824c6645b6fbd0))
- **b-calendar, b-form-datepicker:** add prop `weekday-header-format` to specify weekday header
  length (closes [#5171](https://github.com/bootstrap-vue/bootstrap-vue/issues/5171))
  ([#5175](https://github.com/bootstrap-vue/bootstrap-vue/issues/5175))
  ([8241644](https://github.com/bootstrap-vue/bootstrap-vue/commit/8241644477b174042bb163ba1741c3066165d9f9))
- **b-calendar, b-form-datepicker:** add scoped slots for date navigation buttons (closes
  [#5117](https://github.com/bootstrap-vue/bootstrap-vue/issues/5117))
  ([#5147](https://github.com/bootstrap-vue/bootstrap-vue/issues/5147))
  ([5f69864](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f69864497a13a9b18a96b508af6b9ba89a43add))
- **b-calendar, b-form-datepicker:** allow customization of in-component displayed date format
  (closes [#4797](https://github.com/bootstrap-vue/bootstrap-vue/issues/4797))
  ([#4835](https://github.com/bootstrap-vue/bootstrap-vue/issues/4835))
  ([85c7e75](https://github.com/bootstrap-vue/bootstrap-vue/commit/85c7e759bc78d2ffb5b026cb5ee484b2567136aa))
- **b-calendar, b-form-datepicker:** new components `b-calendar` and `b-form-datepicker` (closes
  [#3676](https://github.com/bootstrap-vue/bootstrap-vue/issues/3676),
  [#1428](https://github.com/bootstrap-vue/bootstrap-vue/issues/1428))
  ([#4712](https://github.com/bootstrap-vue/bootstrap-vue/issues/4712))
  ([af0ded0](https://github.com/bootstrap-vue/bootstrap-vue/commit/af0ded0a3bdc9d69653e9c55f874d550e4909662))
- **b-calendar, b-form-datepicker:** relax `YYYY-MM-DD` string parsing (closes
  [#5232](https://github.com/bootstrap-vue/bootstrap-vue/issues/5232))
  ([#5242](https://github.com/bootstrap-vue/bootstrap-vue/issues/5242))
  ([f362802](https://github.com/bootstrap-vue/bootstrap-vue/commit/f362802b2794f0e5d294bbb004d91ccd623a1e25))
- **b-carousel:** add prop `no-wrap` for disabling wrapping to start/end (closes
  [#3902](https://github.com/bootstrap-vue/bootstrap-vue/issues/3902))
  ([#3905](https://github.com/bootstrap-vue/bootstrap-vue/issues/3905))
  ([2c8bd23](https://github.com/bootstrap-vue/bootstrap-vue/commit/2c8bd23f6702b455f0686da6e97b9edae182ed5c))
- **b-collapse:** add new prop `appear` to animate an initially visible collapse
  ([#4317](https://github.com/bootstrap-vue/bootstrap-vue/issues/4317))
  ([136a72b](https://github.com/bootstrap-vue/bootstrap-vue/commit/136a72b0352d4bb1339ab31f791087cbcda42fa5))
- **b-collapse:** add optional scoping to default slot
  ([#4405](https://github.com/bootstrap-vue/bootstrap-vue/issues/4405))
  ([8e95bac](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e95bacf9d00562f2676689d067ae0db009cbbb6))
- **b-drodpown-item-button, b-drodpown-item-button:** add `button-class` and `link-class` prop
  ([#5014](https://github.com/bootstrap-vue/bootstrap-vue/issues/5014))
  ([b39d31c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b39d31cede76b594b5608fa472d53e3dac525e2b))
- **b-dropdown:** add `block` support to toggle button (closes
  [#4266](https://github.com/bootstrap-vue/bootstrap-vue/issues/4266))
  ([#4269](https://github.com/bootstrap-vue/bootstrap-vue/issues/4269))
  ([30029e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/30029e3b01d16178cc1c43b0294ffa4ed4966574))
- **b-dropdown:** add `toggle-attrs` prop (closes
  [#3694](https://github.com/bootstrap-vue/bootstrap-vue/issues/3694))
  ([#6339](https://github.com/bootstrap-vue/bootstrap-vue/issues/6339))
  ([6cfcbb3](https://github.com/bootstrap-vue/bootstrap-vue/commit/6cfcbb300877e7e1fc03e847c540c6f2c8b0742b))
- **b-dropdown:** add splitClass property to dropdown component
  ([#4394](https://github.com/bootstrap-vue/bootstrap-vue/issues/4394))
  ([a5f342e](https://github.com/bootstrap-vue/bootstrap-vue/commit/a5f342e0e4de2186259e36e42cecda8c20e1c8ab))
- **b-dropdown-form:** add formClass prop for adding classes to the form element (closes
  [#4474](https://github.com/bootstrap-vue/bootstrap-vue/issues/4474))
  ([#4475](https://github.com/bootstrap-vue/bootstrap-vue/issues/4475))
  ([eef4200](https://github.com/bootstrap-vue/bootstrap-vue/commit/eef4200976f7921b1bb03f50c0ece8ee7c41ed0e))
- **b-form-datepicker:** add `button-content` optionally scoped slot for icon
  ([#4795](https://github.com/bootstrap-vue/bootstrap-vue/issues/4795))
  ([7a00910](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a0091099025d8bdcf953b00d8619726b54fa937))
- **b-form-datepicker:** add calendar-width prop (closes
  [#4817](https://github.com/bootstrap-vue/bootstrap-vue/issues/4817))
  ([#4822](https://github.com/bootstrap-vue/bootstrap-vue/issues/4822))
  ([91b77bc](https://github.com/bootstrap-vue/bootstrap-vue/commit/91b77bc9a6b1a4796698ce3185c0b354156ce563))
- **b-form-datepicker:** add pass through prop `date-info-fn` (closes
  [#4826](https://github.com/bootstrap-vue/bootstrap-vue/issues/4826))
  ([#5150](https://github.com/bootstrap-vue/bootstrap-vue/issues/5150))
  ([bf35f80](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf35f80d1c4619cf4494dc8a6256d093140d4052))
- **b-form-datepicker, b-form-timepicker:** add support for icon button only mode (closes
  [#4888](https://github.com/bootstrap-vue/bootstrap-vue/issues/4888))
  ([#4915](https://github.com/bootstrap-vue/bootstrap-vue/issues/4915))
  ([13660c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/13660c3ad02f6c692d306ec95f0d2b19212f9423))
- **b-form-datepicker, b-form-timepicker:** emit `shown` and `hidden` events
  ([#5004](https://github.com/bootstrap-vue/bootstrap-vue/issues/5004))
  ([eb259b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/eb259b998dfd3e88a1b04ed8d3f4c97560f69dbb))
- **b-form-file:** improved drag and drop handling (closes
  [#3673](https://github.com/bootstrap-vue/bootstrap-vue/issues/3673))
  ([#5727](https://github.com/bootstrap-vue/bootstrap-vue/issues/5727))
  ([3b12a73](https://github.com/bootstrap-vue/bootstrap-vue/commit/3b12a73d3856a0b14f630d45d236570698b75e50))
- **b-form-group:** add `content-cols` props and scoped `default` slot (closes
  [#6095](https://github.com/bootstrap-vue/bootstrap-vue/issues/6095),
  [#6118](https://github.com/bootstrap-vue/bootstrap-vue/issues/6118))
  ([#6178](https://github.com/bootstrap-vue/bootstrap-vue/issues/6178))
  ([fab6dc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab6dc57e974f14b7fb50f6f413f3fa9a4504290))
- **b-form-group:** allow setting label cols props to `auto` (closes
  [#4217](https://github.com/bootstrap-vue/bootstrap-vue/issues/4217))
  ([#4218](https://github.com/bootstrap-vue/bootstrap-vue/issues/4218))
  ([21a822b](https://github.com/bootstrap-vue/bootstrap-vue/commit/21a822b9416f996cccf828e65dc029eba849277b))
- **b-form-input, b-form-textarea:** add `lazy` modifier prop to update v-model on change/blur event
  ([#4169](https://github.com/bootstrap-vue/bootstrap-vue/issues/4169))
  ([55787dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/55787ddea56c96f6271bb9f832d33887a35919f4))
- **b-form-input, b-form-textarea:** add `v-model` debouncing feature, and deprecate `<b-table>`
  prop `filter-debounce` (closes
  [#4150](https://github.com/bootstrap-vue/bootstrap-vue/issues/4150))
  ([#4314](https://github.com/bootstrap-vue/bootstrap-vue/issues/4314))
  ([3ecdfa2](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ecdfa2a4cd24f5001c30cf7281964451848e87d))
- **b-form-rating:** add `show-value-max` prop to show possible max rating when `show-value` is
  `true` ([#5200](https://github.com/bootstrap-vue/bootstrap-vue/issues/5200))
  ([e9d54e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9d54e6c6a736b2a4f9dbf232dd2b20afa0e990c))
- **b-form-rating:** new `b-form-rating` custom component
  ([#5132](https://github.com/bootstrap-vue/bootstrap-vue/issues/5132))
  ([30ad7fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/30ad7fe746cd6187311c86319abf6e9519b81f15))
- **b-form-select:** add group/tree support and dedicated option and option-group components (closes
  [#3222](https://github.com/bootstrap-vue/bootstrap-vue/issues/3222))
  ([#4267](https://github.com/bootstrap-vue/bootstrap-vue/issues/4267))
  ([f1ed017](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1ed0177c20f9d7e7e340a8815d1b6bc66f7cb76))
- **b-form-select:** support paths for `valueField`, `textField`, `htmlField` and `disabledField`
  props ([#4386](https://github.com/bootstrap-vue/bootstrap-vue/issues/4386))
  ([ed3b736](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed3b7360af415dc3cc56f0b6662c9d48cc165781))
- **b-form-spinbutton:** new form control component `b-form-spinbutton`
  ([#4744](https://github.com/bootstrap-vue/bootstrap-vue/issues/4744))
  ([da5e473](https://github.com/bootstrap-vue/bootstrap-vue/commit/da5e473bee8866f2940e027e5e7e87e3a2ff8f11))
- **b-form-tags:** add `feedback-aria-live` prop
  ([#6347](https://github.com/bootstrap-vue/bootstrap-vue/issues/6347))
  ([5332970](https://github.com/bootstrap-vue/bootstrap-vue/commit/533297054ce98e879071b35da11a3dd5927beafe))
- **b-form-tags:** add `ignoreInputFocusSelector` prop to make input focus behavior configurable
  (closes [#5425](https://github.com/bootstrap-vue/bootstrap-vue/issues/5425))
  ([#5429](https://github.com/bootstrap-vue/bootstrap-vue/issues/5429))
  ([26d5953](https://github.com/bootstrap-vue/bootstrap-vue/commit/26d5953f834684d36b0af99da912dba08fd37bd8))
- **b-form-tags:** add `no-tags-remove` prop (closes
  [#6162](https://github.com/bootstrap-vue/bootstrap-vue/issues/6162))
  ([#6163](https://github.com/bootstrap-vue/bootstrap-vue/issues/6163))
  ([92de1f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/92de1f9f7772c595afcd16d25d8f71b54a2e077b))
- **b-form-tags:** add `reset` method
  ([#6104](https://github.com/bootstrap-vue/bootstrap-vue/issues/6104))
  ([d610291](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6102913a5f9a3295f646fad50ba58ffc31533e8))
- **b-form-tags:** adds `focusin` & `focusout` to wrapper and prevents firing multiple
  `focus`/`blur` events ([#6395](https://github.com/bootstrap-vue/bootstrap-vue/issues/6395))
  ([44e558f](https://github.com/bootstrap-vue/bootstrap-vue/commit/44e558f73c2ae0d4daafbdbc2616002c7c7a763f))
- **b-form-tags:** new option to specify input type (closes
  [#4644](https://github.com/bootstrap-vue/bootstrap-vue/issues/4644))
  ([#4645](https://github.com/bootstrap-vue/bootstrap-vue/issues/4645))
  ([b899fac](https://github.com/bootstrap-vue/bootstrap-vue/commit/b899faceb4c1fd8562454fa93432e70d7113401b))
- **b-form-tags:** new tagged input component
  ([#4409](https://github.com/bootstrap-vue/bootstrap-vue/issues/4409))
  ([00eb9d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/00eb9d9fd460adca8227b3b344284b5cc49a734f))
- **b-img-lazy:** switch IntersectionObserver to use private `v-b-visible` directive
  ([#3977](https://github.com/bootstrap-vue/bootstrap-vue/issues/3977))
  ([249ccfa](https://github.com/bootstrap-vue/bootstrap-vue/commit/249ccfa9fe7477dc094c5a48b8b9c3a64d23c455))
- **b-img, b-img-lazy:** add support for `srcset` and `sizes` props (closes
  [#4348](https://github.com/bootstrap-vue/bootstrap-vue/issues/4348))
  ([#4350](https://github.com/bootstrap-vue/bootstrap-vue/issues/4350))
  ([f419cb4](https://github.com/bootstrap-vue/bootstrap-vue/commit/f419cb4b63611adbc0e955a81dc9c9b1df4ed7bf))
- **b-link:** add support 3rd party router links such as Gridsome's `<g-link>` (closes
  [#2627](https://github.com/bootstrap-vue/bootstrap-vue/issues/2627))
  ([#5358](https://github.com/bootstrap-vue/bootstrap-vue/issues/5358))
  ([6d29e1c](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d29e1cff6c4fd42b3f60f86bd017d8601de3956))
- **b-link:** support `exact-path` and `exact-path-active-class` props for router link (fixes
  [#6434](https://github.com/bootstrap-vue/bootstrap-vue/issues/6434))
  ([#6811](https://github.com/bootstrap-vue/bootstrap-vue/issues/6811))
  ([576e67b](https://github.com/bootstrap-vue/bootstrap-vue/commit/576e67b3af434037a5ee17533a232465527d5edd))
- add `headerTag` and `footerTag` props to all componets with header and footer
  ([#6375](https://github.com/bootstrap-vue/bootstrap-vue/issues/6375))
  ([c6dd70a](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6dd70a787cdc711b3ce539a65f6aac273749874))
- **b-avatar:** new b-avatar component
  ([#4974](https://github.com/bootstrap-vue/bootstrap-vue/issues/4974))
  ([b2325a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/b2325a3f87a58207603be0bad41afb3059a575a1))
- **b-calendar, b-for-datepicker:** add new `initial-date` prop, and constrain today/current month
  buttons between `min` and `max` (closes
  [#4899](https://github.com/bootstrap-vue/bootstrap-vue/issues/4899))
  ([#4906](https://github.com/bootstrap-vue/bootstrap-vue/issues/4906))
  ([1d957eb](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d957ebd78a8693e91a8116d12c28fe24bd7c19c))
- **b-form-spinbutton:** add slots for increment and decrement button content (closes
  [#4958](https://github.com/bootstrap-vue/bootstrap-vue/issues/4958))
  ([#4963](https://github.com/bootstrap-vue/bootstrap-vue/issues/4963))
  ([5684405](https://github.com/bootstrap-vue/bootstrap-vue/commit/5684405197c8dd03b0711b0efc11ab6d76fb7714))
- **b-icon:** add proper `title` support (closes
  [#5711](https://github.com/bootstrap-vue/bootstrap-vue/issues/5711))
  ([#5724](https://github.com/bootstrap-vue/bootstrap-vue/issues/5724))
  ([3756b2c](https://github.com/bootstrap-vue/bootstrap-vue/commit/3756b2c0e07fc85f73769ea312ede8917d1e1de5))
- **b-media:** improve aside right handling
  ([#5965](https://github.com/bootstrap-vue/bootstrap-vue/issues/5965))
  ([49a3f00](https://github.com/bootstrap-vue/bootstrap-vue/commit/49a3f00420bf9958deda3a6be0ccb76cc3ea06ba))
- **b-modal:** add `ignore-enforce-focus-selector` prop (closes
  [#4537](https://github.com/bootstrap-vue/bootstrap-vue/issues/4537))
  ([#4702](https://github.com/bootstrap-vue/bootstrap-vue/issues/4702))
  ([c3ac992](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3ac99283927b5261d1df05d3c479c534011d7c5))
- **b-modal:** add scoped style support when portalled (non-static modal)
  ([#3962](https://github.com/bootstrap-vue/bootstrap-vue/issues/3962))
  ([77ad6b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/77ad6b92e5cc11454fee8fa6c86eccb8b8abcd6f))
- **b-nav:** add card header support
  ([#3883](https://github.com/bootstrap-vue/bootstrap-vue/issues/3883))
  ([4046a53](https://github.com/bootstrap-vue/bootstrap-vue/commit/4046a5307733ede9c21091600d4ba19e4bfcdf8f))
- **b-nav-item-dropdown:** add `boundary` prop, applicable when not in `b-navbar` (closes
  [#4684](https://github.com/bootstrap-vue/bootstrap-vue/issues/4684))
  ([#4691](https://github.com/bootstrap-vue/bootstrap-vue/issues/4691))
  ([3a50ad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a50ad85e85e1c6dc55a36665062180687078708))
- **b-nav-item-dropdown:** improve default handling of dropdown toggle link (closes
  [#3942](https://github.com/bootstrap-vue/bootstrap-vue/issues/3942))
  ([#5344](https://github.com/bootstrap-vue/bootstrap-vue/issues/5344))
  ([62c6105](https://github.com/bootstrap-vue/bootstrap-vue/commit/62c6105e25bc4590f9e2fa92069b77ccbc17fac6))
- **b-navbar-toggle:** add `disabled` prop
  ([#5397](https://github.com/bootstrap-vue/bootstrap-vue/issues/5397))
  ([0b7082b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b7082b792ee49847ba7c99c61758c0d9fd6d222))
- **b-navbar-toggle:** make default slot scoped
  ([#4995](https://github.com/bootstrap-vue/bootstrap-vue/issues/4995))
  ([144d45f](https://github.com/bootstrap-vue/bootstrap-vue/commit/144d45fb0e4d66bbf243b4a4df39d7f3b9b5c7cc))
- **b-overlay:** add support for overlay `click` event (closes
  [#5243](https://github.com/bootstrap-vue/bootstrap-vue/issues/5243))
  ([#5248](https://github.com/bootstrap-vue/bootstrap-vue/issues/5248))
  ([582560f](https://github.com/bootstrap-vue/bootstrap-vue/commit/582560ff97690ab1e5c1f609d76804b7b3daa104))
- **b-pagination:** if number of pages changes, try and keep current page active (closes
  [#3716](https://github.com/bootstrap-vue/bootstrap-vue/issues/3716))
  ([#3990](https://github.com/bootstrap-vue/bootstrap-vue/issues/3990))
  ([ae8ce78](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae8ce78f019a06b381a12a57d1c2e3ae8e6fe15e))
- **b-pagination, b-pagination-nav:** add `pills` style option
  ([#4236](https://github.com/bootstrap-vue/bootstrap-vue/issues/4236))
  ([605d4c4](https://github.com/bootstrap-vue/bootstrap-vue/commit/605d4c4692ef2dc961d29f4508edf7a9fc2f9b9c))
- **b-pagination, b-pagination-nav:** add page button class props and option to show first/last page
  numbers (closes [#4597](https://github.com/bootstrap-vue/bootstrap-vue/issues/4597),
  [#4533](https://github.com/bootstrap-vue/bootstrap-vue/issues/4533))
  ([#4622](https://github.com/bootstrap-vue/bootstrap-vue/issues/4622))
  ([3a3ee1d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a3ee1dc9312a1a8c530a5ea42d1d239d5a24351))
- **b-pagination, b-pagination-nav:** improve aria accessibility (closes:
  [#4811](https://github.com/bootstrap-vue/bootstrap-vue/issues/4811),
  [#4160](https://github.com/bootstrap-vue/bootstrap-vue/issues/4160))
  ([#4810](https://github.com/bootstrap-vue/bootstrap-vue/issues/4810))
  ([7ee4baa](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ee4baa9a843411cd30a3ee499fc7272b7cf48f2))
- **b-pagination/b-pagination-nav:** allow page change to be prevented (closes
  [#5679](https://github.com/bootstrap-vue/bootstrap-vue/issues/5679))
  ([#5755](https://github.com/bootstrap-vue/bootstrap-vue/issues/5755))
  ([7e18c61](https://github.com/bootstrap-vue/bootstrap-vue/commit/7e18c615fec871fb99a947ca5e247bcef04b7c6f))
- **b-row:** add Bootstrap v4.4 row columns support
  ([#4439](https://github.com/bootstrap-vue/bootstrap-vue/issues/4439))
  ([833b028](https://github.com/bootstrap-vue/bootstrap-vue/commit/833b028a2d6101d01b7012a7378359db1c801695))
- **b-sidebar:** add `header` slot
  ([#6179](https://github.com/bootstrap-vue/bootstrap-vue/issues/6179))
  ([341b7f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/341b7f07943d6079d2bf5d6ab88bbcc50f91d0c5))
- **b-sidebar:** add `noEnforceFocus` prop (closes
  [#5707](https://github.com/bootstrap-vue/bootstrap-vue/issues/5707))
  ([#5734](https://github.com/bootstrap-vue/bootstrap-vue/issues/5734))
  ([c11c237](https://github.com/bootstrap-vue/bootstrap-vue/commit/c11c237143230f533404af75933d86a2de7bfb56))
- **b-sidebar:** add optional backdrop support
  ([#5182](https://github.com/bootstrap-vue/bootstrap-vue/issues/5182))
  ([c6375e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6375e5513cb0ec33a9bc9fc894a123d74cf7768))
- **b-sidebar:** add prop `backdrop-variant`
  ([#5411](https://github.com/bootstrap-vue/bootstrap-vue/issues/5411))
  ([4b0c163](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b0c163156b6ac5be6c1b0a2801d7c169c87cb49))
- **b-sidebar:** new custom component `<b-sidebar>` (closes
  [#3324](https://github.com/bootstrap-vue/bootstrap-vue/issues/3324),
  [#3210](https://github.com/bootstrap-vue/bootstrap-vue/issues/3210),
  [#1702](https://github.com/bootstrap-vue/bootstrap-vue/issues/1702))
  ([#5021](https://github.com/bootstrap-vue/bootstrap-vue/issues/5021))
  ([a77866f](https://github.com/bootstrap-vue/bootstrap-vue/commit/a77866f6d032f1a5a22be2d12d60be507825769c))
- **b-skeleton:** add skeleton components (closes
  [#5413](https://github.com/bootstrap-vue/bootstrap-vue/issues/5413))
  ([#5575](https://github.com/bootstrap-vue/bootstrap-vue/issues/5575))
  ([31c06b5](https://github.com/bootstrap-vue/bootstrap-vue/commit/31c06b5fa697b5f13cc888a1d72effae21eb5e73))
- **b-table:** add `filter-debounce` prop for debouncing filter updates
  ([#3891](https://github.com/bootstrap-vue/bootstrap-vue/issues/3891))
  ([03536a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/03536a504208f094f205a5a2f1ab64ccbb4dbccf))
- **b-table:** add `selectAllRows()` and `clearSelected()` to thead/tfoot slot scopes (addresses
  [#3901](https://github.com/bootstrap-vue/bootstrap-vue/issues/3901))
  ([#3907](https://github.com/bootstrap-vue/bootstrap-vue/issues/3907))
  ([86c53dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/86c53dd83da9c292904e2f489b310cc59a1f31a1))
- **b-table:** add `selectRow()` and `unselectRow()` methods to cell and row-details slot scopes,
  and new prop `no-select-on-click`
  ([#4283](https://github.com/bootstrap-vue/bootstrap-vue/issues/4283))
  ([64b881f](https://github.com/bootstrap-vue/bootstrap-vue/commit/64b881fe2fa19c65a806af85b83504290277557c))
- **b-table:** add `sortKey` option for `no-local-sorting` events
  ([#5746](https://github.com/bootstrap-vue/bootstrap-vue/issues/5746))
  ([f847dae](https://github.com/bootstrap-vue/bootstrap-vue/commit/f847daeb797b84ed80b49a31294a5088fc32b59d))
- **b-table:** allow field definition properties `filterByFormatted` and `sortByFormatted` accept a
  formatter function reference (closes
  [#3892](https://github.com/bootstrap-vue/bootstrap-vue/issues/3892))
  ([#3898](https://github.com/bootstrap-vue/bootstrap-vue/issues/3898))
  ([5492b38](https://github.com/bootstrap-vue/bootstrap-vue/commit/5492b38a71d9a36314f801a40c026f0ef108cd05))
- **b-table:** better sort labeling for screen readers (closes
  [#4487](https://github.com/bootstrap-vue/bootstrap-vue/issues/4487))
  ([#4488](https://github.com/bootstrap-vue/bootstrap-vue/issues/4488))
  ([d4e66fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4e66fa48fdd1cd7fd4b93907fe999de3fc577f8))
- **b-table:** default the row select feature `selected-variant` to the `active` variant
  ([#4128](https://github.com/bootstrap-vue/bootstrap-vue/issues/4128))
  ([af372b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/af372b006e08a98fd9e53891c940b458a97e8996))
- **b-table:** new sorting icons using SVG, plus option to place icon on left of header cell (closes
  [#3687](https://github.com/bootstrap-vue/bootstrap-vue/issues/3687),
  [#3696](https://github.com/bootstrap-vue/bootstrap-vue/issues/3696),
  [#3918](https://github.com/bootstrap-vue/bootstrap-vue/issues/3918),
  [#3966](https://github.com/bootstrap-vue/bootstrap-vue/issues/3966))
  ([#3968](https://github.com/bootstrap-vue/bootstrap-vue/issues/3968))
  ([c4442f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4442f4c41231b6c5514e8ff37002088a1d15f9d))
- **b-table, b-table-lite:** add in head/foot row variant prop (addresses
  [#4215](https://github.com/bootstrap-vue/bootstrap-vue/issues/4215))
  ([#4216](https://github.com/bootstrap-vue/bootstrap-vue/issues/4216))
  ([b222c7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b222c7c01434ef073c54c55f7044c7ce0b9e4325))
- **b-table, b-table-lite:** add new scoped slot `custom-foot` to allow user to create their own
  table footer (closes [#3960](https://github.com/bootstrap-vue/bootstrap-vue/issues/3960))
  ([#4027](https://github.com/bootstrap-vue/bootstrap-vue/issues/4027))
  ([cbeeef9](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbeeef95609e9fa1a85626066b5d812db3c708bc))
- **b-table, b-table-lite:** add prop `details-td-class` for applying classes to the details row
  `<td>` ([#4276](https://github.com/bootstrap-vue/bootstrap-vue/issues/4276))
  ([702a1ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/702a1ef152d0a064dcf7dfaaa55168d2e1b82a50))
- **b-table, b-table-lite:** new `tbody-tr-attr` prop for arbitrary row attributes (closes
  [#1864](https://github.com/bootstrap-vue/bootstrap-vue/issues/1864))
  ([#4481](https://github.com/bootstrap-vue/bootstrap-vue/issues/4481))
  ([4acf6ed](https://github.com/bootstrap-vue/bootstrap-vue/commit/4acf6ed863dd5edd85897a01b099c42322097d1b))
- **b-table, b-table-lite:** switch slot name syntax to use round brackets instead of square
  brackets ([#3986](https://github.com/bootstrap-vue/bootstrap-vue/issues/3986))
  ([fca7bd5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fca7bd54c17f42ee5361cf5bf6395f3bb205c333))
- **b-table, b-table-lite:** use `aria-details` rather than `aria-describedby` when details row
  showing (addresses [#3801](https://github.com/bootstrap-vue/bootstrap-vue/issues/3801))
  ([#3992](https://github.com/bootstrap-vue/bootstrap-vue/issues/3992))
  ([f6f73c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6f73c7ac8f4a54196be5f0ee08c99c76e8f8b13))
- **b-tabs:** add ability to provide custom tab button attributes (closes:
  [#4803](https://github.com/bootstrap-vue/bootstrap-vue/issues/4803))
  ([#4806](https://github.com/bootstrap-vue/bootstrap-vue/issues/4806))
  ([c541d3d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c541d3d89ae88f3193305b61ae8ddc735aa6ec03))
- **b-tabs:** emit cancelable BvEvent before changing tabs via new `activate-tab` event (closes
  [#4273](https://github.com/bootstrap-vue/bootstrap-vue/issues/4273))
  ([#4274](https://github.com/bootstrap-vue/bootstrap-vue/issues/4274))
  ([9b195dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b195dd63f75fe3aa3565a2b37448a3e9b8140ca))
- **b-tags:** add `limit` prop ([#5543](https://github.com/bootstrap-vue/bootstrap-vue/issues/5543))
  ([caa0f1a](https://github.com/bootstrap-vue/bootstrap-vue/commit/caa0f1a2e6d96637c216eb306c77a67254af1caf))
- **b-time, b-form-timepicker:** new components `b-time` and `b-form-timepicker`
  ([#4783](https://github.com/bootstrap-vue/bootstrap-vue/issues/4783))
  ([417ef8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/417ef8f2165e68d182e942219d847511b0fd6e9c))
- **b-tooltip:** add `noninteractive` prop (closes
  [#4556](https://github.com/bootstrap-vue/bootstrap-vue/issues/4556))
  ([#4563](https://github.com/bootstrap-vue/bootstrap-vue/issues/4563))
  ([b3ad726](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3ad7264d9b10fb1b8dfba70c62eed11a56519d6))
- **chore:** configure pre-commit hook (fixes
  [#4532](https://github.com/bootstrap-vue/bootstrap-vue/issues/4532))
  ([#4552](https://github.com/bootstrap-vue/bootstrap-vue/issues/4552))
  ([1bf9e59](https://github.com/bootstrap-vue/bootstrap-vue/commit/1bf9e59e8888a7a2cd6f135665103419f603a32d))
- **config:** improved defaults handling (closes
  [#4507](https://github.com/bootstrap-vue/bootstrap-vue/issues/4507),
  [#5138](https://github.com/bootstrap-vue/bootstrap-vue/issues/5138),
  [#5291](https://github.com/bootstrap-vue/bootstrap-vue/issues/5291),
  [#5459](https://github.com/bootstrap-vue/bootstrap-vue/issues/5459),
  [#5958](https://github.com/bootstrap-vue/bootstrap-vue/issues/5958))
  ([#5981](https://github.com/bootstrap-vue/bootstrap-vue/issues/5981))
  ([7ea0cc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ea0cc4a16d27b179eca47d351eaa9fe6fdfd56e))
- **docs:** add prop descriptions to component reference tables (closes
  [#3647](https://github.com/bootstrap-vue/bootstrap-vue/issues/3647))
  ([#4161](https://github.com/bootstrap-vue/bootstrap-vue/issues/4161))
  ([fdd2a83](https://github.com/bootstrap-vue/bootstrap-vue/commit/fdd2a837de3173f28b96ad4c92cf458fc0f39816))
- **docs:** auto-detect settings props in component reference
  ([#5761](https://github.com/bootstrap-vue/bootstrap-vue/issues/5761))
  ([0ddb2e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0ddb2e051c0ce42bdd599415ba93e82e1a6584f1))
- **docs:** improve form validation examples
  ([#4584](https://github.com/bootstrap-vue/bootstrap-vue/issues/4584))
  ([aca4a5c](https://github.com/bootstrap-vue/bootstrap-vue/commit/aca4a5c8f9a9ed0d7526de396ff072f0c1f4ebdf))
- **docs:** make more concise and explain how to hide `b-toast` title
  ([#4542](https://github.com/bootstrap-vue/bootstrap-vue/issues/4542))
  ([e013dc6](https://github.com/bootstrap-vue/bootstrap-vue/commit/e013dc6d711980b6efb3cb1d0804f039c7e8224d))
- **docs:** move `@nuxtjs/google-analytics` to `buildModules`
  ([#4299](https://github.com/bootstrap-vue/bootstrap-vue/issues/4299))
  ([407c6e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/407c6e3a1035787326531348d9c7cee8ea4cea19))
- **dropdown:** add `role=presentation` to `<li>` elements for improved a11y
  ([#3996](https://github.com/bootstrap-vue/bootstrap-vue/issues/3996))
  ([464d257](https://github.com/bootstrap-vue/bootstrap-vue/commit/464d257f709c856ab04ff237a178b83e1776e9b6))
- **icons:** add stacking support
  ([#4658](https://github.com/bootstrap-vue/bootstrap-vue/issues/4658))
  ([b185cdb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b185cdb686ddddcde1b98585b1fbc48859fc541a))
- **icons:** optional icon components
  ([#4489](https://github.com/bootstrap-vue/bootstrap-vue/issues/4489))
  ([d2bef17](https://github.com/bootstrap-vue/bootstrap-vue/commit/d2bef1715636fcb83de6d51808683e6feda671d0))
- **icons:** upgrade to Bootstrap Icons 1.0.0-alpha4
  ([#5420](https://github.com/bootstrap-vue/bootstrap-vue/issues/5420))
  ([3208309](https://github.com/bootstrap-vue/bootstrap-vue/commit/3208309c649b4cce73c68643d7c911237a713ebc))
- **modal:** add prop for auto focusing one of the built in-buttons once `shown` (closes
  [#3945](https://github.com/bootstrap-vue/bootstrap-vue/issues/3945))
  ([#3979](https://github.com/bootstrap-vue/bootstrap-vue/issues/3979))
  ([6f2827e](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f2827e2e70683bbd8cb48e45a8daa4171cb43e2))
- **refactor:** code enhancements for easier Vue 3 migration (closes
  [#6124](https://github.com/bootstrap-vue/bootstrap-vue/issues/6124),
  [#6139](https://github.com/bootstrap-vue/bootstrap-vue/issues/6139))
  ([#6141](https://github.com/bootstrap-vue/bootstrap-vue/issues/6141))
  ([5bf6733](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bf6733595091cc204d3acc0641f8f0301bcbe9c))
- update `core-js` to v3 ([#5894](https://github.com/bootstrap-vue/bootstrap-vue/issues/5894))
  ([aeed981](https://github.com/bootstrap-vue/bootstrap-vue/commit/aeed9812afe770b6561c9513709e4be852250022))
- **docs:** launch themes page with first BootstrapVue theme
  ([#5549](https://github.com/bootstrap-vue/bootstrap-vue/issues/5549))
  ([ec51ef0](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec51ef062f7ed39339cde59b2d9d4cee40347dcc))
- update Bootstrap to v4.5 ([#5395](https://github.com/bootstrap-vue/bootstrap-vue/issues/5395))
  ([ba7a55e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ba7a55ea094049fd1e3ae492a5a95196252b1da9))
- **custom components:** avoid using padding/margin utility classes where possible (closes
  [#5117](https://github.com/bootstrap-vue/bootstrap-vue/issues/5117))
  ([#5121](https://github.com/bootstrap-vue/bootstrap-vue/issues/5121))
  ([8c6cfe0](https://github.com/bootstrap-vue/bootstrap-vue/commit/8c6cfe0af919a4e54667bcb4b29d2ba6b6576b67))
- **icons:** new `throb` and `fade` animations
  ([#5122](https://github.com/bootstrap-vue/bootstrap-vue/issues/5122))
  ([bc0117c](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc0117cc794c948b202daf2e17f22eb4c36235cc))
- **table:** add `no-border-collapse` prop and SCSS
  ([#3987](https://github.com/bootstrap-vue/bootstrap-vue/issues/3987))
  ([253b4f6](https://github.com/bootstrap-vue/bootstrap-vue/commit/253b4f6e0c20027b40d10e316d49a14f3e860c5d))
- **toast:** add support for scoped styles
  ([#3963](https://github.com/bootstrap-vue/bootstrap-vue/issues/3963))
  ([ca1b5de](https://github.com/bootstrap-vue/bootstrap-vue/commit/ca1b5debca5966ea032c805d544aa9274ae6ed42))
- **tooltip, popover:** overall code refactor for better reactivity and performance (fixes:
  [#1990](https://github.com/bootstrap-vue/bootstrap-vue/issues/1990),
  [#2937](https://github.com/bootstrap-vue/bootstrap-vue/issues/2937),
  [#3480](https://github.com/bootstrap-vue/bootstrap-vue/issues/3480),
  [#3717](https://github.com/bootstrap-vue/bootstrap-vue/issues/3717),
  [#3854](https://github.com/bootstrap-vue/bootstrap-vue/issues/3854), closes
  [#3451](https://github.com/bootstrap-vue/bootstrap-vue/issues/3451))
  ([#3908](https://github.com/bootstrap-vue/bootstrap-vue/issues/3908))
  ([eebab43](https://github.com/bootstrap-vue/bootstrap-vue/commit/eebab437b03528dd7fe2a2cc84e3b9cbfb336c58))
- **types:** create declarations for `<b-calendar>` and `<b-time>` context event objects (closes
  [#5366](https://github.com/bootstrap-vue/bootstrap-vue/issues/5366))
  ([#5374](https://github.com/bootstrap-vue/bootstrap-vue/issues/5374))
  ([8f3ca30](https://github.com/bootstrap-vue/bootstrap-vue/commit/8f3ca30e4d51b5e97f9c4f301c31254a8b060980))
- **v-b-hover:** new directive for reacting to hover changes
  ([#4771](https://github.com/bootstrap-vue/bootstrap-vue/issues/4771))
  ([b7adc6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/b7adc6dc726f75c0578b3de5208f112bef58b4ad))
- **v-b-toggle:** check for target ID via `href` if a link
  ([#5398](https://github.com/bootstrap-vue/bootstrap-vue/issues/5398))
  ([33e39b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/33e39b007225ba86a0c84a66e3ee60b9d2f01fed))
- support `<nuxt-link>`'s `prefetch` property (closes
  [#5125](https://github.com/bootstrap-vue/bootstrap-vue/issues/5125))
  ([#5355](https://github.com/bootstrap-vue/bootstrap-vue/issues/5355))
  ([b9416cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9416cb3824d680e297347af61a934b1536224de))
- **v-b-toggle:** support specifying target ID via directive argument, and array of target IDs via
  directive value (closes [#4834](https://github.com/bootstrap-vue/bootstrap-vue/issues/4834))
  ([#5336](https://github.com/bootstrap-vue/bootstrap-vue/issues/5336))
  ([260ef72](https://github.com/bootstrap-vue/bootstrap-vue/commit/260ef7259e46d343823767374322db0ae3a74803))
- upgrade to bootstrap icons alpha 3
  ([#4966](https://github.com/bootstrap-vue/bootstrap-vue/issues/4966))
  ([d481365](https://github.com/bootstrap-vue/bootstrap-vue/commit/d481365c9f8014e1573026881c3588f2d51999ee))
- **v-b-visible:** make `v-b-visible` directive available for public use
  ([#4318](https://github.com/bootstrap-vue/bootstrap-vue/issues/4318))
  ([5fa7e22](https://github.com/bootstrap-vue/bootstrap-vue/commit/5fa7e22cc3cca6295d226037f880074cfe841b2c))
- auto-generate file `web-types.json` for WebStorm, and files `vetur-tags.json` and
  `vetur-attributes.json` for Vetur (closes
  [#4107](https://github.com/bootstrap-vue/bootstrap-vue/issues/4107))
  ([#4110](https://github.com/bootstrap-vue/bootstrap-vue/issues/4110))
  ([1a3e6a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/1a3e6a56759bee9cc11d4405a4708dbba826fa51))
- improve `CONTRIBUTING.md` ([#4260](https://github.com/bootstrap-vue/bootstrap-vue/issues/4260))
  ([25dacb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/25dacb5ba1923c72e28c590e3b1e80192ad36e1b))
- use `emitOnRoot()` whereever possible and remove unused chainable support
  ([#5030](https://github.com/bootstrap-vue/bootstrap-vue/issues/5030))
  ([74aade1](https://github.com/bootstrap-vue/bootstrap-vue/commit/74aade19b3fe49934769111d251c5039106643bf))
- **alert:** remove need for custom CSS for fade transition
  ([#2925](https://github.com/bootstrap-vue/bootstrap-vue/issues/2925))
  ([0910b22](https://github.com/bootstrap-vue/bootstrap-vue/commit/0910b228aa0e2e527a20b80b7eca9d3463b76cfa))
- **b-container:** add support for bootstrap v4.4.x new responsive containers
  ([0e318f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e318f4755e65eb569dcc579938d0d72c02abd62))
- **b-dropdown:** new `split-button-type` prop to specify split button type (closes
  [#3694](https://github.com/bootstrap-vue/bootstrap-vue/issues/3694))
  ([#3695](https://github.com/bootstrap-vue/bootstrap-vue/issues/3695))
  ([1157589](https://github.com/bootstrap-vue/bootstrap-vue/commit/1157589fa4fad9e636e94862a196121d9054c8c1))
- **b-dropdown:** remove deprecated slot `text`
  ([#3868](https://github.com/bootstrap-vue/bootstrap-vue/issues/3868))
  ([29eb8b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/29eb8b1879462ce2dee8192c2ef203fb348baeac))
- **b-dropdown & b-nav-item-dropdown:** pass optional scope to default slot & fixes keyboard nav
  with dropdown forms ([#3242](https://github.com/bootstrap-vue/bootstrap-vue/issues/3242))
  ([3d1d777](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d1d7775dbf4846a0339021e75bcbb1c88267e5f))
- **b-dropdown, b-nav-item-dropdown:** add new lazy prop (addresses
  [#3634](https://github.com/bootstrap-vue/bootstrap-vue/issues/3634))
  ([#3639](https://github.com/bootstrap-vue/bootstrap-vue/issues/3639))
  ([f742a8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/f742a8a912a41b4b151ff1a7033e95fcaea05767))
- **b-form-file, b-form-checkbox, b-form-radio:** make input element inherit non-prop attributes
  (addresses [#3752](https://github.com/bootstrap-vue/bootstrap-vue/issues/3752))
  ([#3754](https://github.com/bootstrap-vue/bootstrap-vue/issues/3754))
  ([722f9db](https://github.com/bootstrap-vue/bootstrap-vue/commit/722f9db371634d5185db0f7fef99cc1c735b6e8d))
- **b-form-group:** remove deprecated prop `horizontal` and `breakpoint`
  ([#3879](https://github.com/bootstrap-vue/bootstrap-vue/issues/3879))
  ([b301822](https://github.com/bootstrap-vue/bootstrap-vue/commit/b301822902d30c77d06a3bfef7c5a580484cc4ed))
- **b-img-lazy:** add support for IntersectionObserver (closes
  [#3276](https://github.com/bootstrap-vue/bootstrap-vue/issues/3276))
  ([#3279](https://github.com/bootstrap-vue/bootstrap-vue/issues/3279))
  ([5cf71cf](https://github.com/bootstrap-vue/bootstrap-vue/commit/5cf71cf6017f6dce517dfd7ee587dc8f7e53a19e))
- **b-modal:** for accessibility, read only modal title and not whole header + additional A11Y
  options (addresses [#3712](https://github.com/bootstrap-vue/bootstrap-vue/issues/3712))
  ([#3715](https://github.com/bootstrap-vue/bootstrap-vue/issues/3715))
  ([1ce8c6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/1ce8c6d5ccfc6e0be93761daa428c01c61b81f62))
- **b-modal:** improved portaling - retaining parent-child hierarchy (addresses
  [#3312](https://github.com/bootstrap-vue/bootstrap-vue/issues/3312))
  ([#3326](https://github.com/bootstrap-vue/bootstrap-vue/issues/3326))
  ([3728892](https://github.com/bootstrap-vue/bootstrap-vue/commit/3728892207e4c0e8571e4014244623dc8447042c))
- **b-nav, b-nav-item-dropdown:** remove deprecated slot and props
  ([#3867](https://github.com/bootstrap-vue/bootstrap-vue/issues/3867))
  ([21fab35](https://github.com/bootstrap-vue/bootstrap-vue/commit/21fab353f2bbaa4a5698bc646bfb99213117a916))
- **b-table:** allow users to specify top-level keys to be ignored or included when filtering, plus
  add option to filter based on formatted value (closes
  [#3749](https://github.com/bootstrap-vue/bootstrap-vue/issues/3749))
  ([#3786](https://github.com/bootstrap-vue/bootstrap-vue/issues/3786))
  ([142b31b](https://github.com/bootstrap-vue/bootstrap-vue/commit/142b31bf4dec89cc3dcd935bf8b8ba6cbac1ba26))
- **b-table:** make sorting by formated value opt-in per field + add TypeScript declarations for
  locale options ([#3778](https://github.com/bootstrap-vue/bootstrap-vue/issues/3778))
  ([9716850](https://github.com/bootstrap-vue/bootstrap-vue/commit/971685060aaced1463e14cf6447021490a6d51ba))
- **b-table:** programmatic row selection (closes
  [#3064](https://github.com/bootstrap-vue/bootstrap-vue/issues/3064),
  [#3370](https://github.com/bootstrap-vue/bootstrap-vue/issues/3370))
  ([#3844](https://github.com/bootstrap-vue/bootstrap-vue/issues/3844))
  ([9a4fe24](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a4fe24a609e52b8811e9c4e224df06135978b05))
- **b-table:** sort fields that have a formatter function + support `localCompare` options (closes
  [#3178](https://github.com/bootstrap-vue/bootstrap-vue/issues/3178),
  [#1173](https://github.com/bootstrap-vue/bootstrap-vue/issues/1173))
  ([#3585](https://github.com/bootstrap-vue/bootstrap-vue/issues/3585))
  ([c0ca1fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0ca1fdc65b096653f985614befeabedc0078e15))
- **b-table-lite:** new `<b-table-lite>` light-weight table component
  ([#3447](https://github.com/bootstrap-vue/bootstrap-vue/issues/3447))
  ([0477941](https://github.com/bootstrap-vue/bootstrap-vue/commit/0477941e6a35729030b24c635436e9e23f51d644))
- **b-table-simple:** new `<table>` wrapper component that allows users to render their own
  `<thead>`, `<tfoot>`, `<body>`
  ([#3799](https://github.com/bootstrap-vue/bootstrap-vue/issues/3799))
  ([998bd4f](https://github.com/bootstrap-vue/bootstrap-vue/commit/998bd4f133f4bddf7738bdccd54c1ed78c3eb0f1))
- **b-table, b-table-lite:** new field scoped slot naming convention + new fallback scoped slots,
  deprecated old field slot convention (closes
  [#3731](https://github.com/bootstrap-vue/bootstrap-vue/issues/3731))
  ([#3741](https://github.com/bootstrap-vue/bootstrap-vue/issues/3741))
  ([f53360d](https://github.com/bootstrap-vue/bootstrap-vue/commit/f53360d5e6b06e2462f2fba296e3cdc6a31180dc))
- **b-table, b-table-lite:** place `<tfoot>` after `<tbody>` element per HTML5 spec
  ([#3807](https://github.com/bootstrap-vue/bootstrap-vue/issues/3807))
  ([e885d6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e885d6dcd76531a3ac7dbc0b48d97469bdee8dd3))
- **b-tabs:** emit `changed` event whenever tabs added, removed or re-ordered (closes
  [#3575](https://github.com/bootstrap-vue/bootstrap-vue/issues/3575))
  ([#3577](https://github.com/bootstrap-vue/bootstrap-vue/issues/3577))
  ([841419a](https://github.com/bootstrap-vue/bootstrap-vue/commit/841419af00fbc15975ea234a37883b5af66582d9))
- **b-tooltip, b-popover:** add `fallback-placement` prop (closes
  [#3348](https://github.com/bootstrap-vue/bootstrap-vue/issues/3348))
  ([#3349](https://github.com/bootstrap-vue/bootstrap-vue/issues/3349))
  ([ab42b4c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab42b4c4f8189570c62d2263aea1d40fe9d2a724))
- **b-tooltip, b-popover:** allow global `delay` customization
  ([#3426](https://github.com/bootstrap-vue/bootstrap-vue/issues/3426))
  ([2aaec76](https://github.com/bootstrap-vue/bootstrap-vue/commit/2aaec76b6bc4a39e9bc8d560f6d2ec4fd2480574))
- **breadcrumb-link:** support html
  ([#2522](https://github.com/bootstrap-vue/bootstrap-vue/issues/2522))
  ([c2ee63e](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2ee63e9ac8f72f6c1d6a81a66b073826b60ad57))
- **build:** remove deprecated `es/` build
  ([#3604](https://github.com/bootstrap-vue/bootstrap-vue/issues/3604))
  ([3828f59](https://github.com/bootstrap-vue/bootstrap-vue/commit/3828f59e4c640571ad86b4d4851d6ac31eaa9466))
- **button:** add new `squared` prop for making buttons with square corners
  ([#3387](https://github.com/bootstrap-vue/bootstrap-vue/issues/3387))
  ([004963d](https://github.com/bootstrap-vue/bootstrap-vue/commit/004963d6215ce2ccc712a3e4e1371a4cb788a2a1))
- **button:** add prop `pill` for pill style buttons
  ([#3214](https://github.com/bootstrap-vue/bootstrap-vue/issues/3214))
  ([c26298b](https://github.com/bootstrap-vue/bootstrap-vue/commit/c26298b154e51648e05d296ac8f03a6d2b544692))
- **BvEvent:** subclass BvEvent as BvModalEvent
  ([#3024](https://github.com/bootstrap-vue/bootstrap-vue/issues/3024))
  ([502eba9](https://github.com/bootstrap-vue/bootstrap-vue/commit/502eba962eb1b57e19e54eb6dc61a6fc4ada3517))
- **card:** new helper sub-components
  ([#2375](https://github.com/bootstrap-vue/bootstrap-vue/issues/2375))
  ([ff25314](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff253141aba892419ed51b62dd2319b99ba74961))
- **card-img-lazy:** new card-img-lazy sub-component
  ([#2647](https://github.com/bootstrap-vue/bootstrap-vue/issues/2647))
  ([d2e1f8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d2e1f8aec683c2349164125a1115ad7e57c192e3))
- **carousel:** add no-hover-pause prop
  ([#2888](https://github.com/bootstrap-vue/bootstrap-vue/issues/2888))
  ([8a503ec](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a503ec243bc7a06fb221681105d7c39d7fe51d2))
- **carousel:** add support for swipe on touch screens
  ([#2409](https://github.com/bootstrap-vue/bootstrap-vue/issues/2409))
  ([46a6763](https://github.com/bootstrap-vue/bootstrap-vue/commit/46a6763f23e83cc9ceca2bfd9566388e019fbb55))
- **carousel:** support crossfade animation
  ([#2406](https://github.com/bootstrap-vue/bootstrap-vue/issues/2406))
  ([15d8a2c](https://github.com/bootstrap-vue/bootstrap-vue/commit/15d8a2c40d397bf90a301653d40c02ee32c76cdd))
- **carousel:** use provide and inject for sub-component communication
  ([#2407](https://github.com/bootstrap-vue/bootstrap-vue/issues/2407))
  ([7f92318](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f92318fb64b7cefc3421f6877a4f6575006ae9e))
- **config:** add option in config to set global tooltip and popover boundary
  ([#3229](https://github.com/bootstrap-vue/bootstrap-vue/issues/3229))
  ([00e4fc9](https://github.com/bootstrap-vue/bootstrap-vue/commit/00e4fc9004bd8d91f8de83e1f1381ddb8950c25c))
- **config:** defaults for all `size` properties (closes
  [#3805](https://github.com/bootstrap-vue/bootstrap-vue/issues/3805))
  ([#3841](https://github.com/bootstrap-vue/bootstrap-vue/issues/3841))
  ([1389efa](https://github.com/bootstrap-vue/bootstrap-vue/commit/1389efaf21ed9870b68734a863a4e82f60d556dd))
- **core:** create configurable base global configuration
  ([#2905](https://github.com/bootstrap-vue/bootstrap-vue/issues/2905))
  ([8018bdf](https://github.com/bootstrap-vue/bootstrap-vue/commit/8018bdf07329e43cb4051ff2a7526176967c610f))
- **docs:** add heading anchor links
  ([#2698](https://github.com/bootstrap-vue/bootstrap-vue/issues/2698))
  ([fd6cbef](https://github.com/bootstrap-vue/bootstrap-vue/commit/fd6cbef6806fc57cd115eeb39df6f14ba5549916))
- **docs:** add home and playground links to sidebar navigation
  ([#3654](https://github.com/bootstrap-vue/bootstrap-vue/issues/3654))
  ([e5eb9fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5eb9fc01a2af362f338d066f7112987ef1b1c02))
- **docs:** algolia powered search
  ([#2952](https://github.com/bootstrap-vue/bootstrap-vue/issues/2952))
  ([0417f7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0417f7bd9ead7c7ba568a24f016db9c282e103d0))
- **docs:** get recommended `Vue.js` and `Bootstrap` version from `package.json`
  ([#2840](https://github.com/bootstrap-vue/bootstrap-vue/issues/2840))
  ([3a6702e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a6702ebbcc1c155d150232d6598300a74445ea9))
- **docs:** Improve code example markup and prettier integration
  ([#2440](https://github.com/bootstrap-vue/bootstrap-vue/issues/2440))
  ([74ad932](https://github.com/bootstrap-vue/bootstrap-vue/commit/74ad932b4f087e3a38035010c4789892b52b327b))
- **docs:** Prettify with `prettier`
  ([#2427](https://github.com/bootstrap-vue/bootstrap-vue/issues/2427))
  ([9463138](https://github.com/bootstrap-vue/bootstrap-vue/commit/94631385301ce07bc657dec6090ac4a8bf4abc17))
- **docs:** remove new/enhances/changed badges
  ([#3870](https://github.com/bootstrap-vue/bootstrap-vue/issues/3870))
  ([d46529c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d46529c3b4fcb5adbe14cd4ec16c7268d23e9585))
- **docs:** updates to the theming reference section
  ([#3790](https://github.com/bootstrap-vue/bootstrap-vue/issues/3790))
  ([e080bf7](https://github.com/bootstrap-vue/bootstrap-vue/commit/e080bf7e3a98378bf66e95d002dd3f9acf5a94f9))
- **docs/playground:** add support for exporting to CodePen and CodeSandbox
  ([#3071](https://github.com/bootstrap-vue/bootstrap-vue/issues/3071))
  ([ccb1614](https://github.com/bootstrap-vue/bootstrap-vue/commit/ccb1614cc7c6a95fc2ae6a9d01b9924bedf2396c))
- **dropdown:** additional semantic markup optimizations for A11Y
  ([#3196](https://github.com/bootstrap-vue/bootstrap-vue/issues/3196))
  ([91d893e](https://github.com/bootstrap-vue/bootstrap-vue/commit/91d893e0b9e4e8b70f19c30e372e2fb6b56c5cbc))
- **dropdown:** support for form controls and free flow text
  ([#2434](https://github.com/bootstrap-vue/bootstrap-vue/issues/2434))
  ([7e8a2d5](https://github.com/bootstrap-vue/bootstrap-vue/commit/7e8a2d5fe365d1ec185feed2f7a49e60238825a4))
- **dropdown:** use provide and inject
  ([#2431](https://github.com/bootstrap-vue/bootstrap-vue/issues/2431))
  ([3df90ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/3df90ea64e5b1bdbfe8a05ece7d588807c359813))
- **dropdown:** use semantic `<ul>` and `<li>` markup (closes
  [#3072](https://github.com/bootstrap-vue/bootstrap-vue/issues/3072))
  ([#3087](https://github.com/bootstrap-vue/bootstrap-vue/issues/3087))
  ([58ad66b](https://github.com/bootstrap-vue/bootstrap-vue/commit/58ad66be27b202310cc0d60a67ddd2d9358cc9d7))
- **es:** revert to tranforming `es/` modules into CJS, and simplify build with top-level named
  import/exports (closes [#3397](https://github.com/bootstrap-vue/bootstrap-vue/issues/3397),
  [#3393](https://github.com/bootstrap-vue/bootstrap-vue/issues/3393),
  [#3323](https://github.com/bootstrap-vue/bootstrap-vue/issues/3323))
  ([#3404](https://github.com/bootstrap-vue/bootstrap-vue/issues/3404))
  ([6c386d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/6c386d3c34cc8d9b63094d147da7edc0ac181370))
- **es build:** don't transpile import/export statements to require/exports, for better tree shaking
  (closes [#3323](https://github.com/bootstrap-vue/bootstrap-vue/issues/3323))
  ([#3358](https://github.com/bootstrap-vue/bootstrap-vue/issues/3358))
  ([3c1866d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c1866db82a36807c7d3593c2932d927d7988bb9))
- **form controls:** add `autofocus` prop
  ([#3341](https://github.com/bootstrap-vue/bootstrap-vue/issues/3341))
  ([e7eb1b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/e7eb1b40d7e295f9bca759a96e0261cb24678b02))
- **form controls:** add support for control sizing of `b-form-file`, `b-form-checkbox`, and
  `b-form-radio` (closes [#3745](https://github.com/bootstrap-vue/bootstrap-vue/issues/3745))
  ([#3794](https://github.com/bootstrap-vue/bootstrap-vue/issues/3794))
  ([18c3957](https://github.com/bootstrap-vue/bootstrap-vue/commit/18c3957486008dad5c39e42f2c321311e8407d81))
- **form-checkbox, form-radio:** add `aria-labelledby` prop (closes:
  [#3139](https://github.com/bootstrap-vue/bootstrap-vue/issues/3139))
  ([#3140](https://github.com/bootstrap-vue/bootstrap-vue/issues/3140))
  ([f82f566](https://github.com/bootstrap-vue/bootstrap-vue/commit/f82f5661bdf900790bc560b9f79a2bfe5a664c63))
- **form-checkbox/radio:** allow no label in plain mode (fixes
  [#2911](https://github.com/bootstrap-vue/bootstrap-vue/issues/2911))
  ([#2912](https://github.com/bootstrap-vue/bootstrap-vue/issues/2912))
  ([6f38d9d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f38d9dc91720b5552ad2596f4b003dfe47cb2ef))
- **form-checkbox/radio:** code improvements, test suites, and docs update (Closes
  [#2718](https://github.com/bootstrap-vue/bootstrap-vue/issues/2718))
  ([#2721](https://github.com/bootstrap-vue/bootstrap-vue/issues/2721))
  ([285a2e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/285a2e1c0ac2ce4ada2c2c3a1ac33366e418bdf8))
- **form-file:** add in prop and scoped slot for formatting selected file names
  ([#2902](https://github.com/bootstrap-vue/bootstrap-vue/issues/2902))
  ([f53b5f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/f53b5f8de2701dab527d82146951b775451257a6))
- **form-group:** make `aria-live` attribute on feedback configurable (closes
  [#3057](https://github.com/bootstrap-vue/bootstrap-vue/issues/3057))
  ([#3058](https://github.com/bootstrap-vue/bootstrap-vue/issues/3058))
  ([6161b8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/6161b8ab44e494600edf828c0dfc966b5e920e27))
- **form-input:** Added support for datalists to text form-inputs
  ([#2781](https://github.com/bootstrap-vue/bootstrap-vue/issues/2781))
  ([0339ad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/0339ad80e4621d6c1eb3eaa250f95ae7e48b746e))
- **form-textarea:** add `noAutoShrink` prop (closes
  [#2664](https://github.com/bootstrap-vue/bootstrap-vue/issues/2664))
  ([#2666](https://github.com/bootstrap-vue/bootstrap-vue/issues/2666))
  ([a29c40c](https://github.com/bootstrap-vue/bootstrap-vue/commit/a29c40c147026c0a5eba35b893caba070bde63a6))
- **forms:** add state prop to invalid and valid feedback + docs update
  ([#2611](https://github.com/bootstrap-vue/bootstrap-vue/issues/2611))
  ([9df8dac](https://github.com/bootstrap-vue/bootstrap-vue/commit/9df8dac375213f68ea1a00e60361a8eb46ab6dc2))
- **forms:** new b-form-datalist helper component
  ([#2899](https://github.com/bootstrap-vue/bootstrap-vue/issues/2899))
  ([e9a8e85](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9a8e8547b1248f01705eaa981ca35afe644bc4a))
- **link:** Add support for nuxt-link
  ([#2384](https://github.com/bootstrap-vue/bootstrap-vue/issues/2384))
  ([4bd462a](https://github.com/bootstrap-vue/bootstrap-vue/commit/4bd462ad97bcb65a694b9d1f6054df378de38ea3))
- **list-group:** support horizontal layout
  ([#2536](https://github.com/bootstrap-vue/bootstrap-vue/issues/2536))
  ([10fa210](https://github.com/bootstrap-vue/bootstrap-vue/commit/10fa21061ea0f84938375cbcf804b4864e6a748b))
- **modal:** Add `dialogClass` prop
  ([#2465](https://github.com/bootstrap-vue/bootstrap-vue/issues/2465))
  ([34ae267](https://github.com/bootstrap-vue/bootstrap-vue/commit/34ae267750d5b56d3385386315a937875149c5b2))
- **modal:** add modal-backdrop slot
  ([#2688](https://github.com/bootstrap-vue/bootstrap-vue/issues/2688))
  ([ce18ffd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce18ffd25ce13a5aeb05b2ca1267fd74a097f16f))
- **modal:** add support for scrollable modal dialog content
  ([#2535](https://github.com/bootstrap-vue/bootstrap-vue/issues/2535))
  ([5c01faf](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c01faff3d0c39293a243f87ad9da6fd7c5bc489))
- **modal:** add toggle method and root event (Closes
  [#2708](https://github.com/bootstrap-vue/bootstrap-vue/issues/2708))
  ([#2709](https://github.com/bootstrap-vue/bootstrap-vue/issues/2709))
  ([f67218e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f67218e7e35773532b4a935980674a1de75d6cc5))
- **modal:** add variant prop for header close button
  ([#2765](https://github.com/bootstrap-vue/bootstrap-vue/issues/2765))
  ([b7e95d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/b7e95d9ee0def0ec3b21eebc52f0cdaf756ccf8c))
- **modal:** auto return focus to trigger elements using document.activeElement if no return focus
  provided ([#3033](https://github.com/bootstrap-vue/bootstrap-vue/issues/3033))
  ([e5c0aa5](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5c0aa571760fe6683af844e90e3549f08fecc4a))
- **modal:** remove BvModalEvent deprecations
  ([#3864](https://github.com/bootstrap-vue/bootstrap-vue/issues/3864))
  ([90c299c](https://github.com/bootstrap-vue/bootstrap-vue/commit/90c299cd169c709ee3b0e7525039ddc974a8f6df))
- **modal:** support for optionally scoped slots and new `Vue.prototype.$bvModal` helper
  ([#3056](https://github.com/bootstrap-vue/bootstrap-vue/issues/3056))
  ([b647830](https://github.com/bootstrap-vue/bootstrap-vue/commit/b647830779954b0155c96a7396bef55872b495f0))
- **modal:** use PortalVue for modal placement
  ([#3157](https://github.com/bootstrap-vue/bootstrap-vue/issues/3157))
  ([6325528](https://github.com/bootstrap-vue/bootstrap-vue/commit/632552853df9016b61ea7f42a3a9733c3ec23446))
- **nuxt:** add `usePretranspiled` option
  ([#3048](https://github.com/bootstrap-vue/bootstrap-vue/issues/3048))
  ([8022481](https://github.com/bootstrap-vue/bootstrap-vue/commit/8022481c302d77aede311c88707fd8742a152eed))
- **nuxt:** handle edge cases where component, directive and plugin names are passed as `camelCase`
  or `kebab-case` ([#3418](https://github.com/bootstrap-vue/bootstrap-vue/issues/3418))
  ([ce3ba73](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce3ba739ae7902302bee1738d2a52cc6a534f868))
- **nuxt:** module improvements
  ([#2593](https://github.com/bootstrap-vue/bootstrap-vue/issues/2593))
  ([0795fea](https://github.com/bootstrap-vue/bootstrap-vue/commit/0795fea3f29ae3a5157af6fdb0e5fd5a7561d4c3))
- **nuxt module:** alias `esm/` and `es/` to `src/` for Nuxt prod mode
  ([#3423](https://github.com/bootstrap-vue/bootstrap-vue/issues/3423))
  ([ae2040b](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae2040b2dfa7eba75d0e6468bf7321b5ac6e8ec5))
- **nuxt module:** optimize imports into single import statements
  ([#3325](https://github.com/bootstrap-vue/bootstrap-vue/issues/3325))
  ([ef71a3b](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef71a3b04746c673c1c4c19efcee9685651b3e1a))
- **nuxt-module:** add tree-shaking support to Nuxt module
  ([#2654](https://github.com/bootstrap-vue/bootstrap-vue/issues/2654))
  ([9aaf32f](https://github.com/bootstrap-vue/bootstrap-vue/commit/9aaf32fca77826d28e239fc599292829a3b46bd2))
- **pagination-nav:** autodetect current page based on $route/URL. Add support array of links
  ([#2836](https://github.com/bootstrap-vue/bootstrap-vue/issues/2836))
  ([65e12f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/65e12f84c1d27443367cc1d6de0459c36fcf68fe))
- **popover/tooltip:** Add `boundaryPadding` prop to override Popper.js default padding
  ([#2475](https://github.com/bootstrap-vue/bootstrap-vue/issues/2475))
  ([c8ad487](https://github.com/bootstrap-vue/bootstrap-vue/commit/c8ad487c1583beead9de4b5af49d4a8a646d1b3f))
- **scrollspy:** support when vue-router is in `hash` based route mode (closes
  [#2722](https://github.com/bootstrap-vue/bootstrap-vue/issues/2722))
  ([#2953](https://github.com/bootstrap-vue/bootstrap-vue/issues/2953))
  ([a713dd4](https://github.com/bootstrap-vue/bootstrap-vue/commit/a713dd48ce5794f311b4f2ec23d51b5fe272e7b9))
- **security:** strip html tags
  ([#2479](https://github.com/bootstrap-vue/bootstrap-vue/issues/2479))
  ([3c6ba3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c6ba3e44de425120990f671436a7b163742b5cb))
- **table:** "Debounce" providerFunction and refresh methods
  ([#2393](https://github.com/bootstrap-vue/bootstrap-vue/issues/2393))
  ([d5f0462](https://github.com/bootstrap-vue/bootstrap-vue/commit/d5f04621a11cfc52c4333b12117272b5e8078654))
- **table:** add basic keyboard nav when table has row-clicked handler or is selctable (closes
  [#2869](https://github.com/bootstrap-vue/bootstrap-vue/issues/2869))
  ([#2870](https://github.com/bootstrap-vue/bootstrap-vue/issues/2870))
  ([ddcd66a](https://github.com/bootstrap-vue/bootstrap-vue/commit/ddcd66a07058d570e98a70557f2eaf871ea44949))
- **table:** add IDs to tbody > tr elements if primary-key provided (closes
  [#2693](https://github.com/bootstrap-vue/bootstrap-vue/issues/2693))
  ([#2694](https://github.com/bootstrap-vue/bootstrap-vue/issues/2694))
  ([3d72404](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d72404832d3ca99aef1d3d66f8107d8b638c631))
- **table:** add new prop `table-class` for applying classes to table root element (closes
  [#3138](https://github.com/bootstrap-vue/bootstrap-vue/issues/3138))
  ([#3148](https://github.com/bootstrap-vue/bootstrap-vue/issues/3148))
  ([5deb5db](https://github.com/bootstrap-vue/bootstrap-vue/commit/5deb5dbf81713c7834a9b1884a42de04280acf6e))
- **table:** add sticky header support (closes
  [#2085](https://github.com/bootstrap-vue/bootstrap-vue/issues/2085))
  ([#3831](https://github.com/bootstrap-vue/bootstrap-vue/issues/3831))
  ([a5f7266](https://github.com/bootstrap-vue/bootstrap-vue/commit/a5f7266589955650df8df628bdfa737d2f1187aa))
- **table:** add support for scoped empty slots
  ([#2641](https://github.com/bootstrap-vue/bootstrap-vue/issues/2641))
  ([7917557](https://github.com/bootstrap-vue/bootstrap-vue/commit/7917557db6b24fd152968bfc93bcda8370421fb5))
- **table:** add support for transitions on tbody element (Closes
  [#1821](https://github.com/bootstrap-vue/bootstrap-vue/issues/1821))
  ([#2450](https://github.com/bootstrap-vue/bootstrap-vue/issues/2450))
  ([91514af](https://github.com/bootstrap-vue/bootstrap-vue/commit/91514af445221286ef0bc55985556d58e3c54fdc))
- **table:** add table row middle click (auxclicked) event
  ([#2425](https://github.com/bootstrap-vue/bootstrap-vue/issues/2425))
  ([23250a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/23250a2ac738c73a38d4834b97756409fe1de549))
- **table:** add TypeScript definitions for table fields
  ([#2867](https://github.com/bootstrap-vue/bootstrap-vue/issues/2867))
  ([436e8c1](https://github.com/bootstrap-vue/bootstrap-vue/commit/436e8c1d4ce9e3eff2053f3a02b834687c8b32b4))
- **table:** added `thead-top` slot to table (closes
  [#2489](https://github.com/bootstrap-vue/bootstrap-vue/issues/2489))
  ([#2653](https://github.com/bootstrap-vue/bootstrap-vue/issues/2653))
  ([fbb549c](https://github.com/bootstrap-vue/bootstrap-vue/commit/fbb549cf6c77f7e60eca3f275c84b49115c90b49))
- **table:** better default rendering of unformatted object values
  ([#2733](https://github.com/bootstrap-vue/bootstrap-vue/issues/2733))
  ([ee84672](https://github.com/bootstrap-vue/bootstrap-vue/commit/ee846721ef30f688a6839e3046a7a705daaead7d))
- **table:** create table child element helper components, plus new `sort-null-last` and
  `table-variant` props. ([#3808](https://github.com/bootstrap-vue/bootstrap-vue/issues/3808))
  ([981114b](https://github.com/bootstrap-vue/bootstrap-vue/commit/981114b5d9bf8a9a31855ff4e27a59efa8818c3f))
- **table:** don't render `thead` or `tfoot` if no detected fields
  ([#3553](https://github.com/bootstrap-vue/bootstrap-vue/issues/3553))
  ([a924889](https://github.com/bootstrap-vue/bootstrap-vue/commit/a924889bd7e53f705c1f61edd5c44618a9aec21d))
- **table:** make some slots available either as scoped or unscoped
  ([#2740](https://github.com/bootstrap-vue/bootstrap-vue/issues/2740))
  ([ab7937e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab7937e04ce6f6c4d146c8374f4bec155bacbc1c))
- **table:** make table sort icons configurable via SCSS variables
  ([#3156](https://github.com/bootstrap-vue/bootstrap-vue/issues/3156))
  ([a72f134](https://github.com/bootstrap-vue/bootstrap-vue/commit/a72f134be9a8e808a16a261b0f1203f8f08d6f6f))
- **table:** remove deprecated slot names, introduce new slot names
  ([#3866](https://github.com/bootstrap-vue/bootstrap-vue/issues/3866))
  ([249efd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/249efd9a61abe129ed429fa5f50a9524589e4ed0))
- **tables:** add support for custom header attributes (closes
  [#2244](https://github.com/bootstrap-vue/bootstrap-vue/issues/2244))
  ([#3876](https://github.com/bootstrap-vue/bootstrap-vue/issues/3876))
  ([8784f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/8784f315f65bbf796dcba1e433427f0159758769))
- **tables:** add support for sticky columns
  ([#3847](https://github.com/bootstrap-vue/bootstrap-vue/issues/3847))
  ([5b5f2b8](https://github.com/bootstrap-vue/bootstrap-vue/commit/5b5f2b8bca2ee5cf95eff1e0457a581f651c9883))
- **tabs:** add `fill`, `justified` and `active-class` props (closes
  [#3053](https://github.com/bootstrap-vue/bootstrap-vue/issues/3053),
  [#2518](https://github.com/bootstrap-vue/bootstrap-vue/issues/2518))
  ([#3061](https://github.com/bootstrap-vue/bootstrap-vue/issues/3061))
  ([b6557ad](https://github.com/bootstrap-vue/bootstrap-vue/commit/b6557ad7edbd8b79b332a12979d00f1df17ee547))
- **tabs:** new named slot `tabs-start` for prepending tab buttons, deprecates `tabs` slot in favour
  of `tabs-end` (closes [#3678](https://github.com/bootstrap-vue/bootstrap-vue/issues/3678))
  ([#3679](https://github.com/bootstrap-vue/bootstrap-vue/issues/3679))
  ([0b5f552](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b5f55229593d286bce17e01caa3141fa8ce6490))
- **tabs:** remove deprecations
  ([#3863](https://github.com/bootstrap-vue/bootstrap-vue/issues/3863))
  ([0edac49](https://github.com/bootstrap-vue/bootstrap-vue/commit/0edac49addf497c9012566c9517c26f2139e0d02))
- **toast:** add Bootstrap v4.3 Toasts
  ([#3093](https://github.com/bootstrap-vue/bootstrap-vue/issues/3093))
  ([c31b4ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/c31b4ffb094f54360fa1b13c45f79005bddb1355))
- **toast:** add SCSS variable for default toast background opacity + standardize a few BootstrapVue
  SCSS variable names ([#3775](https://github.com/bootstrap-vue/bootstrap-vue/issues/3775))
  ([5799075](https://github.com/bootstrap-vue/bootstrap-vue/commit/57990753ef1c1177e29a5d9d1e136ef5b7e5e198))
- **toast:** updates to toaster SCSS and structure and enable hover-pause
  ([#3135](https://github.com/bootstrap-vue/bootstrap-vue/issues/3135))
  ([263f206](https://github.com/bootstrap-vue/bootstrap-vue/commit/263f20629c60dc5ef34de61f66d60c295a5a25c7))
- **tooltip/popover:** remove SCSS deprecations
  ([#3869](https://github.com/bootstrap-vue/bootstrap-vue/issues/3869))
  ([bea49d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/bea49d41a5b3d48856f2170a944a5b1fd9f0ed8b))
- add BOOTSTRAP_VUE_NO_WARN environment variable to hide warnings
  ([#2826](https://github.com/bootstrap-vue/bootstrap-vue/issues/2826))
  ([44d0351](https://github.com/bootstrap-vue/bootstrap-vue/commit/44d03515568ad0ab1dd5e0eb0251d25e72b4da01))
- minor code improvements ([#3682](https://github.com/bootstrap-vue/bootstrap-vue/issues/3682))
  ([2fb5ce8](https://github.com/bootstrap-vue/bootstrap-vue/commit/2fb5ce823a577fcc2414d78bd43ed9e5351cb1c0))
- **table:** don't show empty row slot if table busy and busy slot provided (Closes
  [#2565](https://github.com/bootstrap-vue/bootstrap-vue/issues/2565))
  ([#2572](https://github.com/bootstrap-vue/bootstrap-vue/issues/2572))
  ([6fd31a4](https://github.com/bootstrap-vue/bootstrap-vue/commit/6fd31a495d26f6babbe69b590029816e2db82b5d))
- **table:** new option to disable footer sorting
  ([#2802](https://github.com/bootstrap-vue/bootstrap-vue/issues/2802))
  ([bc443a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc443a3e4499bebfea7e4596c44454dfa9a1f33a))
- **tooltip:** add in SCSS support for specifying tooltip variant background color level
  ([#3653](https://github.com/bootstrap-vue/bootstrap-vue/issues/3653))
  ([d7cb071](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7cb0714d9aaf97ef2bcdd8c2526e93600e0fd12))
- **tooltip, popover:** add support for contextual variants and custom class (closes
  [#1983](https://github.com/bootstrap-vue/bootstrap-vue/issues/1983),
  [#2075](https://github.com/bootstrap-vue/bootstrap-vue/issues/2075))
  ([#3644](https://github.com/bootstrap-vue/bootstrap-vue/issues/3644))
  ([695edae](https://github.com/bootstrap-vue/bootstrap-vue/commit/695edaec5b1739703f2e9cfe7accea8ac7a7faf3))
- **tooltip, popover:** remove need for route watcher
  ([#3583](https://github.com/bootstrap-vue/bootstrap-vue/issues/3583))
  ([98844b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/98844b4feb95236811644e8139294e8272d5e06a))
- **types:** add `noCloseButton` property to `BvToastOptions` type declaration
  ([#3636](https://github.com/bootstrap-vue/bootstrap-vue/issues/3636))
  ([5aa9211](https://github.com/bootstrap-vue/bootstrap-vue/commit/5aa9211be2363997bb2d45c3b2e538d46ee2a2b3))
- add `"source": "src/index.js"` entry in package.json
  ([#3422](https://github.com/bootstrap-vue/bootstrap-vue/issues/3422))
  ([0878ca6](https://github.com/bootstrap-vue/bootstrap-vue/commit/0878ca63ea97f6425b54b9d3263e1fcfafaeb9cc))
- console warn if multiple instances of Vue detected (addresses
  [#3040](https://github.com/bootstrap-vue/bootstrap-vue/issues/3040))
  ([#3220](https://github.com/bootstrap-vue/bootstrap-vue/issues/3220))
  ([41db3e2](https://github.com/bootstrap-vue/bootstrap-vue/commit/41db3e23c40d37ccb807b2fe79fef7832426413c))
- don't warn about multiple Vue instances when testing in JSDOM (closes
  [#3303](https://github.com/bootstrap-vue/bootstrap-vue/issues/3303))
  ([#3315](https://github.com/bootstrap-vue/bootstrap-vue/issues/3315))
  ([0caa29b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0caa29b836f492ba5883f1d80c93c16ac04ed097))
- improved tree-shaking when importing individual components
  ([#3462](https://github.com/bootstrap-vue/bootstrap-vue/issues/3462))
  ([2df1ab9](https://github.com/bootstrap-vue/bootstrap-vue/commit/2df1ab9e1c42af8f630772ad1b5cc7003f8d34f9))
- **toast:** add additional options to global default config (closes
  [#3169](https://github.com/bootstrap-vue/bootstrap-vue/issues/3169))
  ([#3170](https://github.com/bootstrap-vue/bootstrap-vue/issues/3170))
  ([b01e01c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b01e01c1cb370be0a7c5f35cef36825e2ae0d23e))
- **types:** better type declarations (closes
  [#1976](https://github.com/bootstrap-vue/bootstrap-vue/issues/1976))
  ([#3283](https://github.com/bootstrap-vue/bootstrap-vue/issues/3283))
  ([a42abd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/a42abd033361a1e9445c4e9c49bd679858b915b4))
- **types:** create more typescript typings, and simplify component/directive/plugin imports.
  ([#3209](https://github.com/bootstrap-vue/bootstrap-vue/issues/3209))
  ([50bbe6a](https://github.com/bootstrap-vue/bootstrap-vue/commit/50bbe6ad381cb71e2b27d539755fb33022c2ba1e))
- make more component appearance prop defaults globally configurable (closes
  [#3173](https://github.com/bootstrap-vue/bootstrap-vue/issues/3173))
  ([#3175](https://github.com/bootstrap-vue/bootstrap-vue/issues/3175))
  ([f7cf28c](https://github.com/bootstrap-vue/bootstrap-vue/commit/f7cf28c9c1f516e137d5479c8542440512e0a834))
- **util/get, table:** handle edge case where user has dot in actual item data field key (Closes
  [#2762](https://github.com/bootstrap-vue/bootstrap-vue/issues/2762))
  ([#2764](https://github.com/bootstrap-vue/bootstrap-vue/issues/2764))
  ([ee52844](https://github.com/bootstrap-vue/bootstrap-vue/commit/ee52844465da43ed53a3bdf0cc63f1b392b259b0))
- **utils:** es6ify functions wherever possible
  ([#2825](https://github.com/bootstrap-vue/bootstrap-vue/issues/2825))
  ([e8f0ed3](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8f0ed389d9b9d8e1ea0d5fcb6a5c1e91fb94d60))
- **utils/noop:** add `noop()` util
  ([#2892](https://github.com/bootstrap-vue/bootstrap-vue/issues/2892))
  ([61b75dc](https://github.com/bootstrap-vue/bootstrap-vue/commit/61b75dc6ecee8d0d0ee83b68dbb87a88714d0e89))
- **v-b-toggle:** make targets reactive to updates (closes
  [#3165](https://github.com/bootstrap-vue/bootstrap-vue/issues/3165))
  ([#3167](https://github.com/bootstrap-vue/bootstrap-vue/issues/3167))
  ([6eff6d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/6eff6d96b1d03204d25609bd093fc56ea20be14e))
- switch to PascalCase name for all components
  ([#2305](https://github.com/bootstrap-vue/bootstrap-vue/issues/2305))
  ([6179e61](https://github.com/bootstrap-vue/bootstrap-vue/commit/6179e61b1e0b4b6310a79f67075a4fe9790f2750))
- **alert:** Add fade prop ([#1785](https://github.com/bootstrap-vue/bootstrap-vue/issues/1785))
  ([0999b4c](https://github.com/bootstrap-vue/bootstrap-vue/commit/0999b4cc4b4943741aef71367dc354af45decbc0))
- **breadcrumb-link:** support children elements
  ([#1832](https://github.com/bootstrap-vue/bootstrap-vue/issues/1832))
  ([#1833](https://github.com/bootstrap-vue/bootstrap-vue/issues/1833))
  ([42175f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/42175f80047ad7b2ad20ec5de13402d9e01c0dfe))
- **build:** replace uglify-es with terser
  ([#2238](https://github.com/bootstrap-vue/bootstrap-vue/issues/2238))
  ([bd95ad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd95ad83f5265683ad4ea75ffdf592290ed18199))
- **button:** Make button tag configurable
  ([#1929](https://github.com/bootstrap-vue/bootstrap-vue/issues/1929))
  ([afcadd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/afcadd9733daba296949c27eadf80cf924d5f86f))
- **card:** include custom styles for card-img-left and card-img-right
  ([#2292](https://github.com/bootstrap-vue/bootstrap-vue/issues/2292))
  ([a72d494](https://github.com/bootstrap-vue/bootstrap-vue/commit/a72d4949e4b8578601d5620b5d30abaf9b042145))
- **card:** support left and right image placement
  ([#1981](https://github.com/bootstrap-vue/bootstrap-vue/issues/1981))
  ([66194a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/66194a6a3c49d0ceadd90e8a2fda6b9105675236))
- **core:** Add SCSS support (fixes
  [#2201](https://github.com/bootstrap-vue/bootstrap-vue/issues/2201))
  ([#2221](https://github.com/bootstrap-vue/bootstrap-vue/issues/2221))
  ([f8326a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/f8326a2afa4eef6cfc0df00fb32c360543499deb))
- **css:** create SCSS versions of CSS
  ([#2218](https://github.com/bootstrap-vue/bootstrap-vue/issues/2218))
  ([d6ba6db](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6ba6db5fcf91873a48f3357c4e2f322df50bdea))
- **docs:** Allow sub-components to show reference info for slots and events
  ([#2132](https://github.com/bootstrap-vue/bootstrap-vue/issues/2132))
  ([52c960b](https://github.com/bootstrap-vue/bootstrap-vue/commit/52c960bf179bf78ddc4de1b0b326c78d5627173c))
- **docs:** conditionally load babel-standalone only on browsers that need transpilation
  ([#2294](https://github.com/bootstrap-vue/bootstrap-vue/issues/2294))
  ([1578732](https://github.com/bootstrap-vue/bootstrap-vue/commit/1578732fbd69c13b9411e111f8a1e68c8c3075b8))
- **docs:** use babel-standalone in playground/v-play to support IE
  ([#2286](https://github.com/bootstrap-vue/bootstrap-vue/issues/2286))
  ([46f8d4b](https://github.com/bootstrap-vue/bootstrap-vue/commit/46f8d4b14d9b0d6c9eee2aafae605b2654639d1f))
- **dropdown:** add toggleClass prop
  ([#1485](https://github.com/bootstrap-vue/bootstrap-vue/issues/1485))
  ([da16cc0](https://github.com/bootstrap-vue/bootstrap-vue/commit/da16cc0cc10df339550f2fdeb48b85919b78536d))
- **dropdown:** make show/hide events cancelable . also adds toggle event
  ([#1807](https://github.com/bootstrap-vue/bootstrap-vue/issues/1807))
  ([4136bd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/4136bd9e7c1b6469de066771a548fcb8d09588f7))
- **dropdown:** support 'href', 'to' and 'variant' in split button mode (Closes
  [#1960](https://github.com/bootstrap-vue/bootstrap-vue/issues/1960))
  ([#2301](https://github.com/bootstrap-vue/bootstrap-vue/issues/2301))
  ([31b7d19](https://github.com/bootstrap-vue/bootstrap-vue/commit/31b7d1928e8ff8e233559848f9f959b690d29e25))
- **dropdown, nav-item-dropdown:** support menuClass and extraMenuClasses
  ([#1683](https://github.com/bootstrap-vue/bootstrap-vue/issues/1683))
  ([3da5f18](https://github.com/bootstrap-vue/bootstrap-vue/commit/3da5f184f91b928cf34de4d169cf00e56f2dde4d))
- **dropdowns:** add boundary prop for controlling placement constraint
  ([#1440](https://github.com/bootstrap-vue/bootstrap-vue/issues/1440))
  ([01498cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/01498cb4066af0d65512734f531e63b4f39bcb55))
- **dropfoen:** Add `dropright` and `dropleft` direction support
  ([#2117](https://github.com/bootstrap-vue/bootstrap-vue/issues/2117))
  ([e186639](https://github.com/bootstrap-vue/bootstrap-vue/commit/e1866393dcfced84da2525307a317a49dd9e29ff)),
  closes [#2108](https://github.com/bootstrap-vue/bootstrap-vue/issues/2108)
- **form-checkbox:** support custom switch styling
  ([#2293](https://github.com/bootstrap-vue/bootstrap-vue/issues/2293))
  ([3508ea2](https://github.com/bootstrap-vue/bootstrap-vue/commit/3508ea20af413326e21c1b4ec3d0f049e12557ce))
- **form-file:** reset file input when value set to null or empty string
  ([#2170](https://github.com/bootstrap-vue/bootstrap-vue/issues/2170))
  ([ab44375](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab44375a4ac2fd4462652550c12886adca8ca8fe))
- **form-group:** Add multiple breakpoint support for label (Closes
  [#2230](https://github.com/bootstrap-vue/bootstrap-vue/issues/2230))
  ([#2258](https://github.com/bootstrap-vue/bootstrap-vue/issues/2258))
  ([5e453f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e453f9e331705ed0970f0468720495bb9413c8a))
- **form-input:** add step, min and max props for use with number type
  ([40ff380](https://github.com/bootstrap-vue/bootstrap-vue/commit/40ff38063d4cf99aa9f686322a48d729566ca037))
- **form-input:** initial SCSS file
  ([#2217](https://github.com/bootstrap-vue/bootstrap-vue/issues/2217))
  ([923d20b](https://github.com/bootstrap-vue/bootstrap-vue/commit/923d20be0d524a943cd9ee0177c945caaa8d483e))
- **form-input:** support custom-range input + validation and input styles
  ([#2120](https://github.com/bootstrap-vue/bootstrap-vue/issues/2120))
  ([013a737](https://github.com/bootstrap-vue/bootstrap-vue/commit/013a737f4f35d87cbe6b2023ae16f3d12b9cc595))
- **form-input:** Use new form-text mixin and add trim and number modifiers
  ([#2204](https://github.com/bootstrap-vue/bootstrap-vue/issues/2204))
  ([3c9936e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c9936e4cdbfb1fe961c0b34116969cb7439608e))
- **form-radio-check:** migrate to using provide/inject, add inline props
  ([#2241](https://github.com/bootstrap-vue/bootstrap-vue/issues/2241))
  ([c0a68d5](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0a68d5aa3d25f7b010b6641567124651d74b657))
- **form-select:** Expose focus and blur methods (Closes
  [#2237](https://github.com/bootstrap-vue/bootstrap-vue/issues/2237))
  ([#2257](https://github.com/bootstrap-vue/bootstrap-vue/issues/2257))
  ([ded7679](https://github.com/bootstrap-vue/bootstrap-vue/commit/ded7679c16cbe7a4700864a5c3f3da20c84dd0bc))
- **forms:** add form prop to all inputs. fixes
  [#2154](https://github.com/bootstrap-vue/bootstrap-vue/issues/2154)
  ([#2172](https://github.com/bootstrap-vue/bootstrap-vue/issues/2172))
  ([6009d72](https://github.com/bootstrap-vue/bootstrap-vue/commit/6009d723d1c408c0b8b6abc285bc5896cad6daa6))
- **forms:** add support for tooltip-style feedback text
  ([#2188](https://github.com/bootstrap-vue/bootstrap-vue/issues/2188))
  ([5203436](https://github.com/bootstrap-vue/bootstrap-vue/commit/520343685adeddeaa758a01d0e1a5c0aa31d7caf))
- **list-group:** add striped support
  ([#2313](https://github.com/bootstrap-vue/bootstrap-vue/issues/2313))
  ([3491943](https://github.com/bootstrap-vue/bootstrap-vue/commit/34919431a44a37e74708432013eec32488ef9894))
- **modal:** add 'aria-modal="true"' to modal when open.
  ([#2314](https://github.com/bootstrap-vue/bootstrap-vue/issues/2314))
  ([dbf4920](https://github.com/bootstrap-vue/bootstrap-vue/commit/dbf4920339ce01210c9796b7a4e0a1baf1a1b6cc))
- **modal:** add `modalClass` property to `bModal`
  ([#1682](https://github.com/bootstrap-vue/bootstrap-vue/issues/1682))
  ([c7a10ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7a10ef7c076e724709d13c71856fa05d321390c))
- **modal:** Make stackable optional
  ([#2259](https://github.com/bootstrap-vue/bootstrap-vue/issues/2259))
  ([2322044](https://github.com/bootstrap-vue/bootstrap-vue/commit/2322044b84a207e4fc339b006ee5d0a82607e391))
- **modal:** new props for adding classes to header, body and footer
  ([#1462](https://github.com/bootstrap-vue/bootstrap-vue/issues/1462))
  ([bc67a2d](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc67a2d7f3cbf7e115f69fdbe97e6e8b6d4b225a))
- **modal:** Support multiple modals open at once
  ([#2164](https://github.com/bootstrap-vue/bootstrap-vue/issues/2164))
  ([2709902](https://github.com/bootstrap-vue/bootstrap-vue/commit/2709902c28b8347763c8690032fb9a1ecc41ebeb))
- **nav-item-dropdown:** add extra-toggle-classes prop with tests and docs. closes
  [#1550](https://github.com/bootstrap-vue/bootstrap-vue/issues/1550).
  ([#1555](https://github.com/bootstrap-vue/bootstrap-vue/issues/1555))
  ([7967018](https://github.com/bootstrap-vue/bootstrap-vue/commit/7967018990d461b20c9d1fdf175b2eda19f90733))
- **package:** align dependencies to prevent warnings.
  ([#975](https://github.com/bootstrap-vue/bootstrap-vue/issues/975))
  ([b70a9f7](https://github.com/bootstrap-vue/bootstrap-vue/commit/b70a9f70e36db8a35a726b8e3916288e85750042))
- **pagination:** added slots for first, prev, next, last, and ellipsis. Fixes
  [#1870](https://github.com/bootstrap-vue/bootstrap-vue/issues/1870).
  ([#1980](https://github.com/bootstrap-vue/bootstrap-vue/issues/1980))
  ([1b7e7de](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b7e7de928ddcfd68f2d30d19f1e065889d1879c))
- **pkg:** update dependendencies (bootstrap 4.0.0-beta.3)
  ([afb82a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/afb82a8b4d0f7f308af85c3c5c80897cce6ace25))
- **security:** Strip HTML script tags before inserting content into DOM. Fixes
  [#1974](https://github.com/bootstrap-vue/bootstrap-vue/issues/1974),[#1665](https://github.com/bootstrap-vue/bootstrap-vue/issues/1665)
  ([#2129](https://github.com/bootstrap-vue/bootstrap-vue/issues/2129))
  ([6dde0cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/6dde0cba3f89374fea3cb09b8a6b90363bf04243))
- **security:** Strip HTML script tags before inserting content into DOM. Fixes
  [#1974](https://github.com/bootstrap-vue/bootstrap-vue/issues/1974),[#1665](https://github.com/bootstrap-vue/bootstrap-vue/issues/1665)
  ([#2134](https://github.com/bootstrap-vue/bootstrap-vue/issues/2134))
  ([ba6f3f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/ba6f3f8359e257589d744f180312c09bf9f12289)),
  closes [#1931](https://github.com/bootstrap-vue/bootstrap-vue/issues/1931)
- **spinner:** Pre-Release Bootstrap V4.2 spinners
  ([#2306](https://github.com/bootstrap-vue/bootstrap-vue/issues/2306))
  ([bf3994f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf3994ffa37c513535c3c6d724f86acca6bf4b4f))
- **table:** add borderless prop
  ([#2300](https://github.com/bootstrap-vue/bootstrap-vue/issues/2300))
  ([dabe150](https://github.com/bootstrap-vue/bootstrap-vue/commit/dabe15072ff8dccd087f6a0ad3cca06d7ccceac7))
- **table:** add field to the table column data cell slots
  ([#1705](https://github.com/bootstrap-vue/bootstrap-vue/issues/1705))
  ([e013d59](https://github.com/bootstrap-vue/bootstrap-vue/commit/e013d59373a7bbc6576b414b48c29f7f01123827))
- **table:** Add no-sort-reset prop
  ([#1784](https://github.com/bootstrap-vue/bootstrap-vue/issues/1784))
  ([26aaeab](https://github.com/bootstrap-vue/bootstrap-vue/commit/26aaeab1de439491aa4950d642d486d539b10c4e))
- **table:** Add row-unhovered event
  ([#1874](https://github.com/bootstrap-vue/bootstrap-vue/issues/1874))
  ([a87cad1](https://github.com/bootstrap-vue/bootstrap-vue/commit/a87cad14cd1e24af01da1aec2ded118ff36e74f7))
- **table:** Add table-busy slot for loading status. Closes
  [#1859](https://github.com/bootstrap-vue/bootstrap-vue/issues/1859)
  ([#2196](https://github.com/bootstrap-vue/bootstrap-vue/issues/2196))
  ([a654a61](https://github.com/bootstrap-vue/bootstrap-vue/commit/a654a61bac4a9d7444598cb41f5a80fb85e6045b))
- **table:** Add the sort-direction prop
  ([#1783](https://github.com/bootstrap-vue/bootstrap-vue/issues/1783))
  ([#1788](https://github.com/bootstrap-vue/bootstrap-vue/issues/1788))
  ([9e1959d](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e1959d0996f745967c10dfadae1bb8482d63a17))
- **table:** initial SCSS file ([#2216](https://github.com/bootstrap-vue/bootstrap-vue/issues/2216))
  ([db0b483](https://github.com/bootstrap-vue/bootstrap-vue/commit/db0b483f4c08df31fbe7de7507f00e46fac7f734))
- **table:** pass sortDesc to user provided sortCompare routine
  ([#1994](https://github.com/bootstrap-vue/bootstrap-vue/issues/1994))
  ([a8e4103](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8e410366ba38f304c0f88b64ab46a44536bd804))
- **table:** Remove need to add `click.stop` on inputs/links/buttons inside rows
  ([#2214](https://github.com/bootstrap-vue/bootstrap-vue/issues/2214))
  ([7d8662b](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d8662b532e32488a66064904137265ea06bd285))
- **table:** Selectable rows (fixes
  [#1790](https://github.com/bootstrap-vue/bootstrap-vue/issues/1790))
  ([#2260](https://github.com/bootstrap-vue/bootstrap-vue/issues/2260))
  ([5b1cb90](https://github.com/bootstrap-vue/bootstrap-vue/commit/5b1cb905217dd6fb7cea6481e610489d390f5bf9))
- **table:** Split computedItems into multiple functions
  ([#1893](https://github.com/bootstrap-vue/bootstrap-vue/issues/1893))
  ([bb1c550](https://github.com/bootstrap-vue/bootstrap-vue/commit/bb1c55031e18a18b3dd0ca8e429293f40f0ce168))
- **table:** Support contextmenu event binding for table rows
  ([#2064](https://github.com/bootstrap-vue/bootstrap-vue/issues/2064))
  ([1eced46](https://github.com/bootstrap-vue/bootstrap-vue/commit/1eced462339a381cdb6e275c0fece2ba34447b17))
- **table:** support custom attributes per table cell in a column
  ([#1760](https://github.com/bootstrap-vue/bootstrap-vue/issues/1760))
  ([fc083e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc083e563360bc447674953d9c957ede573dd229))
- **table:** support custom classes per table cell in a column
  ([d05d6b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/d05d6b6eb32a14ff4f652915968f2443da6c6b4a))
- **table:** Support sorting on nested object properties
  ([#1868](https://github.com/bootstrap-vue/bootstrap-vue/issues/1868))
  ([b699e4b](https://github.com/bootstrap-vue/bootstrap-vue/commit/b699e4b53e10ef4d6ac612dfa1cfecf86b1327fc))
- **tabs:** add key nav prop like button toolbar has
  ([#1733](https://github.com/bootstrap-vue/bootstrap-vue/issues/1733))
  ([bc3b82b](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc3b82b5808dfd25d91a4777a227a9a2158099f3))
- **tabs/noNavStyle:** added related prop and check
  ([91c7257](https://github.com/bootstrap-vue/bootstrap-vue/commit/91c7257ba43948f3a006e4625a79408cd68de29d))
- add basic typescript declarations
  ([#1721](https://github.com/bootstrap-vue/bootstrap-vue/issues/1721))
  ([3c040f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c040f0356012a642e1a94a240dda8e2462beb10))
- **test:** test against multi versions of vue
  ([25d0b13](https://github.com/bootstrap-vue/bootstrap-vue/commit/25d0b13fc78a24349a9cee5b3916a97bfe71f641))
- upgrade to bootstrap 4.0.0 ([#1507](https://github.com/bootstrap-vue/bootstrap-vue/issues/1507))
  ([1d5b230](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d5b230bd5c91c0948308ee12d7d7be90bd0e1e8))
- **badge:** Support actionable (link) badges
  ([#1226](https://github.com/bootstrap-vue/bootstrap-vue/issues/1226))
  ([ba2b5b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/ba2b5b4dc52fa8fd8ccfce63c0b7626e9fd6977f))
- **card:** add prop body-class
  ([#1250](https://github.com/bootstrap-vue/bootstrap-vue/issues/1250))
  ([23fc3be](https://github.com/bootstrap-vue/bootstrap-vue/commit/23fc3bee4af15b9c107b968434718f57b78834d3))
- **docs:** Add TOC section in right hand column
  ([#1077](https://github.com/bootstrap-vue/bootstrap-vue/issues/1077))
  ([b9d15f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9d15f8323f41d0d00c71d37ffe0eae472349cde))
- **docs:** Better ARIA when changing routes
  ([#1102](https://github.com/bootstrap-vue/bootstrap-vue/issues/1102))
  ([d2c951a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d2c951a7b003d308d14648df573b2a09c548fa8f))
- **docs:** Hide TOC sub-sections when not `active`
  ([9d5a626](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d5a6266715c4e21c0af0e839aaa237af45dfe4c))
- **docs:** Search all keywords
  ([#1105](https://github.com/bootstrap-vue/bootstrap-vue/issues/1105))
  ([3e5b56b](https://github.com/bootstrap-vue/bootstrap-vue/commit/3e5b56b10d2ff65767dedba6be0b461f00a7357a))
- **docs:** search support
  ([7916981](https://github.com/bootstrap-vue/bootstrap-vue/commit/7916981621c9fd84c4bb45ffcc65205efdd13fef))
- **docs:** TOC add scroll into iview support
  ([d72f87a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d72f87a9f286463bb92d46cc3f1ee5139522148a))
- **dropdown:** Optionally hide the dropdown toggle caret
  ([#1197](https://github.com/bootstrap-vue/bootstrap-vue/issues/1197))
  ([960877c](https://github.com/bootstrap-vue/bootstrap-vue/commit/960877c3bbf264631a607677dabeef1fec6cc6cd))
- **dropdowns:** Allow space and cursor down to trigger opening of menus
  ([#1159](https://github.com/bootstrap-vue/bootstrap-vue/issues/1159))
  ([1249f51](https://github.com/bootstrap-vue/bootstrap-vue/commit/1249f51c05769c5d6f661f9a7c0efd401f5f4d3a))
- **eslint:** update settings to remove editor errors
  ([#792](https://github.com/bootstrap-vue/bootstrap-vue/issues/792))
  ([c33d1d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c33d1d40ea9476697a619bd83505a8b36e21c3c9))
- **form-file:** Use `label` as wrapper element + name-spaced custom CSS
  ([#1353](https://github.com/bootstrap-vue/bootstrap-vue/issues/1353))
  ([e2bc891](https://github.com/bootstrap-vue/bootstrap-vue/commit/e2bc891a1cd65703a412643eba60438a2a7b1ee9))
- **form-group:** add valid feedback support
  ([#1360](https://github.com/bootstrap-vue/bootstrap-vue/issues/1360))
  ([7f3535b](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f3535b377a11605453ea17ea393ffcc56436901))
- **form-group:** new label-size prop
  ([b8311e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/b8311e5c6842b3eeeb44e0d898876cdcc6cdab9e))
- **form-group:** new label-size prop
  ([#1422](https://github.com/bootstrap-vue/bootstrap-vue/issues/1422))
  ([dcffb5c](https://github.com/bootstrap-vue/bootstrap-vue/commit/dcffb5cad095d54b8cc6d1ccc26c730defc9a1dd))
- **form-group:** new prop for label-class, deprecate prop feedback in favor of invalid-feedback
  ([#1412](https://github.com/bootstrap-vue/bootstrap-vue/issues/1412))
  ([44f13a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/44f13a5bdcb065168b00fee77b306699456c7ecc))
- **form-group:** new prop for label-class, deprecate prop feedback in favor of invalid-feedback
  ([#1412](https://github.com/bootstrap-vue/bootstrap-vue/issues/1412))
  ([7d61cb4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d61cb4018aae44bf69043e08b71d3aae6e4cabe))
- **form-group:** render label element if prop label-for set + horizontal layout optimizations
  ([#1423](https://github.com/bootstrap-vue/bootstrap-vue/issues/1423))
  ([ce164bf](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce164bf616baca8c22db6e841b376b5fbbb76174))
- **form-group:** set aria-describedby attribute on input if label-for provided
  ([#1431](https://github.com/bootstrap-vue/bootstrap-vue/issues/1431))
  ([6bd12bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/6bd12bb77da7ab27a9f0bc829d30961d644e2eb0))
- **form-group:** Switch to fieldset+legend for better semantic/ARIA markup
  ([#1129](https://github.com/bootstrap-vue/bootstrap-vue/issues/1129))
  ([7a62b75](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a62b75e8319c8052ad9e1521d222b805fe7c785))
- **form-input:** emit input event when lazy-formatter is true
  ([#1086](https://github.com/bootstrap-vue/bootstrap-vue/issues/1086))
  ([016591c](https://github.com/bootstrap-vue/bootstrap-vue/commit/016591c805fadc842df00366e491ad952b3f6cfa))
- **form-radio+form-checkbox:** Prep for BSV4.beta.3 plain checkbox/radio validation styling
  ([#1253](https://github.com/bootstrap-vue/bootstrap-vue/issues/1253))
  ([81989ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/81989abccce5f940e02fec0c26a6eba20c9aa0b1))
- **form-select:** Emit change event on user interaction
  ([3cc0f05](https://github.com/bootstrap-vue/bootstrap-vue/commit/3cc0f05c72b2a073c6a3c5a78ab25262ee32c122))
- **modal:** Add Bootstrap V4 anticipated verticaly centered modal
  ([#1246](https://github.com/bootstrap-vue/bootstrap-vue/issues/1246))
  ([4a8ce2c](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a8ce2c6a6463d2f30c2e93f3e0bff2313afca9e))
- **modal:** fix for overflowing centered modal to scroll
  ([#1363](https://github.com/bootstrap-vue/bootstrap-vue/issues/1363))
  ([3b3ba32](https://github.com/bootstrap-vue/bootstrap-vue/commit/3b3ba3287164194260e11a2bbf641e12922e32d0))
- **nav-item-dropdown:** Add shorter aliases
  ([8986543](https://github.com/bootstrap-vue/bootstrap-vue/commit/89865431e0123586a15c063d38b635110b7aef56))
- **navbar-nav:** New b-navbar-nav component
  ([#1231](https://github.com/bootstrap-vue/bootstrap-vue/issues/1231))
  ([4bdba0e](https://github.com/bootstrap-vue/bootstrap-vue/commit/4bdba0e05a331321c284bf5591620e8d8d25c90d))
- **nuxt:** add bvCSS option. resolves
  [#1351](https://github.com/bootstrap-vue/bootstrap-vue/issues/1351).
  ([3a7517f](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a7517f41e736afdcd218a4f10171993f51dd5e2))
- **package:** add lint by default for tests
  ([f1ca71e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1ca71ebaa4b3e3d381f76513cc0b2b55d8bf8c5))
- **package:** use es build by default
  ([142d517](https://github.com/bootstrap-vue/bootstrap-vue/commit/142d517ecad405c6fcb73c112ba82998ee23d63a))
- **packaging:** add nuxt module
  ([4c58c80](https://github.com/bootstrap-vue/bootstrap-vue/commit/4c58c80e61322cee9cbfa2d37bfe07240ba03d72))
- **pagination:** Better keyboard tab support + focus styling
  ([42b31da](https://github.com/bootstrap-vue/bootstrap-vue/commit/42b31da1a12823d36a562a7640ece1b3a7d36ffd))
- **pagination-nav:** Better tab/focus management
  ([adf8dcc](https://github.com/bootstrap-vue/bootstrap-vue/commit/adf8dcca592558643604e0a4deff8a0e3f340875))
- **pagination+pagination-nav:** disabled styling now works in BS V4.beta.2
  ([#1381](https://github.com/bootstrap-vue/bootstrap-vue/issues/1381))
  ([d51349f](https://github.com/bootstrap-vue/bootstrap-vue/commit/d51349f173515b26283dd910aa02da50c0ac0017))
- **pagination+pagination-nav:** remove need for custom active focus style
  ([#1384](https://github.com/bootstrap-vue/bootstrap-vue/issues/1384))
  ([ecd9b6a](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecd9b6a657e0e126c86437f80f7adf1577975e1d))
- **pagination+pagination-nav:** remove need for custom active focus style
  ([#1384](https://github.com/bootstrap-vue/bootstrap-vue/issues/1384))
  ([1e1b099](https://github.com/bootstrap-vue/bootstrap-vue/commit/1e1b09957682905556021bea8d9053394912dad6))
- **table:** add outlined option
  ([#1355](https://github.com/bootstrap-vue/bootstrap-vue/issues/1355))
  ([7ba183e](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ba183efbbc964a529a834e2741b9ef01b4e2594))
- **table:** add responsive stacked table option
  ([#1407](https://github.com/bootstrap-vue/bootstrap-vue/issues/1407))
  ([26c35ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/26c35ba0ec44f6100c7c53caa4128af3313a936d))
- **table:** add responsive stacked table option
  ([#1407](https://github.com/bootstrap-vue/bootstrap-vue/issues/1407))
  ([df23115](https://github.com/bootstrap-vue/bootstrap-vue/commit/df231152b39a3a9049c6315a7d99b584c8fd1538))
- **table:** add toggleDetails method to scoped item slots
  ([#1404](https://github.com/bootstrap-vue/bootstrap-vue/issues/1404))
  ([e02fa49](https://github.com/bootstrap-vue/bootstrap-vue/commit/e02fa494aa13d48ed93a665d692c96b84c110ce4))
- **table:** add toggleDetails method to scoped item slots
  ([#1404](https://github.com/bootstrap-vue/bootstrap-vue/issues/1404))
  ([a9c4b7d](https://github.com/bootstrap-vue/bootstrap-vue/commit/a9c4b7dc62bf93560c566bc88d51c14fe023d828))
- **table:** Allow custom attributes in table td cell
  ([#1193](https://github.com/bootstrap-vue/bootstrap-vue/issues/1193))
  ([485adbf](https://github.com/bootstrap-vue/bootstrap-vue/commit/485adbfdf218a7bb996f9999079d4569b3acc8ba))
- **table:** BS V4.beta.2 New responsive breakpoints and table-dark class
  ([#1222](https://github.com/bootstrap-vue/bootstrap-vue/issues/1222))
  ([febdfd1](https://github.com/bootstrap-vue/bootstrap-vue/commit/febdfd1517e5182e9a69f33d5f7da27fa9427423))
- **table:** caption positioning prop
  ([#1341](https://github.com/bootstrap-vue/bootstrap-vue/issues/1341))
  ([7c86e66](https://github.com/bootstrap-vue/bootstrap-vue/commit/7c86e6618d2e6a84ac2e603b3b5493292a53e4a2))
- **table:** New fixed prop, allow disable localSort, emit context-changed event, and style tweaks
  ([#1076](https://github.com/bootstrap-vue/bootstrap-vue/issues/1076))
  ([4447c7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/4447c7cee9c77f185648cbb4b6666f5d369d91b4))
- **table:** Pass computed fields array to details scoped slot
  ([#1271](https://github.com/bootstrap-vue/bootstrap-vue/issues/1271))
  ([0745ae8](https://github.com/bootstrap-vue/bootstrap-vue/commit/0745ae8a567c5a218c26c57fc89d8804d6da476c))
- **tabs:** add name to helper component for better debugging
  ([e436a1d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e436a1d9a1f848172d10f95a0b3b171a5c295638))
- **tabs:** add name to helper component for better debugging
  ([51ef9e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/51ef9e3bbc26409e196f37c6a8ef179b3c75f8c0))
- **tabs:** add no-body prop to b-tab
  ([#1385](https://github.com/bootstrap-vue/bootstrap-vue/issues/1385))
  ([af36c0e](https://github.com/bootstrap-vue/bootstrap-vue/commit/af36c0ef7dce516f9a3dcdaded921e10d299e4d7))
- **tabs:** add no-body prop to b-tab
  ([#1385](https://github.com/bootstrap-vue/bootstrap-vue/issues/1385))
  ([ef3ff06](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef3ff069314f4cd041139e5c18f1130069617ae9))
- **tabs:** New props for adding classes to nav tab
  ([#1289](https://github.com/bootstrap-vue/bootstrap-vue/issues/1289))
  ([c6d3642](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6d3642fe590c50df1e8200a436f6dfe0bd3b3d8))
- **tabs:** vertical tabs + new props for adding classes to inner elements
  ([#1362](https://github.com/bootstrap-vue/bootstrap-vue/issues/1362))
  ([51d0e03](https://github.com/bootstrap-vue/bootstrap-vue/commit/51d0e03a14ad792966f7d9bd5da95b82158dac25))
- **tooltip popover:** Don't close if focus moves between trigger element and tip/popover
  ([#1093](https://github.com/bootstrap-vue/bootstrap-vue/issues/1093))
  ([87ffb4f](https://github.com/bootstrap-vue/bootstrap-vue/commit/87ffb4f3b4ff53290bfc4670e026e6c720ba2660))
- **tooltip+popover:** ability to programmatically show and hide tooltip and popover
  ([#1366](https://github.com/bootstrap-vue/bootstrap-vue/issues/1366))
  ([360b337](https://github.com/bootstrap-vue/bootstrap-vue/commit/360b337374146fb25b98170dd80bccc6d1812dbb)),
  closes [#1369](https://github.com/bootstrap-vue/bootstrap-vue/issues/1369)
- **tooltip+popover:** add boundary element config option (positioning constraint)
  ([#1439](https://github.com/bootstrap-vue/bootstrap-vue/issues/1439))
  ([08fd7ce](https://github.com/bootstrap-vue/bootstrap-vue/commit/08fd7ceedd97c6a08f8d7ec33c98fe8e1a586f4c))
- **tooltip+popover:** Allow delay to be object in component versions
  ([#1131](https://github.com/bootstrap-vue/bootstrap-vue/issues/1131))
  ([1a47c87](https://github.com/bootstrap-vue/bootstrap-vue/commit/1a47c87b9980e7c1c837ba0c623018aa8cf92167))
- **tooltip+popover:** Eight new placement options
  ([#1081](https://github.com/bootstrap-vue/bootstrap-vue/issues/1081))
  ([dae7855](https://github.com/bootstrap-vue/bootstrap-vue/commit/dae7855bb8b77cb770cf0b87a56647d63c62c2b7))
- **tooltip+popover:** programmatically disable/enable tooltip or popover
  ([#1387](https://github.com/bootstrap-vue/bootstrap-vue/issues/1387))
  ([c83e0d5](https://github.com/bootstrap-vue/bootstrap-vue/commit/c83e0d58f52c92d50eaf2ee5410e5d003340fd67))
- **tooltip+popover:** programmatically disable/enable tooltip or popover
  ([#1387](https://github.com/bootstrap-vue/bootstrap-vue/issues/1387))
  ([8104cb4](https://github.com/bootstrap-vue/bootstrap-vue/commit/8104cb43a6091a1b2a14ed19fc1bf0c1ec925716))
- **v-b-modal:** set role="button" if trigger element is not a button
  ([aa45d3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/aa45d3e15c4cd160dbe9f220f793facbe326fe7c))
- **v-b-toggle:** add role 'button' when trigger is not a button
  ([c2dd2d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2dd2d047e70040397cace567bdc588c6bf1aa28))
- es builds
  ([8647855](https://github.com/bootstrap-vue/bootstrap-vue/commit/8647855a8bd297340ffef8a5151304d3b2343ed7))
- make all components available as .js files
  ([#1279](https://github.com/bootstrap-vue/bootstrap-vue/issues/1279))
  ([d18eb66](https://github.com/bootstrap-vue/bootstrap-vue/commit/d18eb6663728bc74ec83a7a7b2858631a6a7c0a2))
- Make Components & Directives available as Vue plugins
  ([#1267](https://github.com/bootstrap-vue/bootstrap-vue/issues/1267))
  ([13d9a42](https://github.com/bootstrap-vue/bootstrap-vue/commit/13d9a42d9e3d9b076eef5d8de86b9e6aff73551f))
- use babel
  ([5e653e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e653e6c9d4f3386514ae9bfa7ef16b84c9a80ce))
- **b-col:** restore `.offset-*` col classes + new b-container and b-row components 🍾🍻🎉
  ([#929](https://github.com/bootstrap-vue/bootstrap-vue/issues/929))
  ([023f078](https://github.com/bootstrap-vue/bootstrap-vue/commit/023f078c03b05f45f1edb80ce11a38c54140a5a8))
- **b-img:** New component ([#933](https://github.com/bootstrap-vue/bootstrap-vue/issues/933))
  ([c4358e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4358e045d6f28be5c692e3df7f1fd33033c70ed))
- **b-img-lazy:** Lazy loaded image component
  ([#943](https://github.com/bootstrap-vue/bootstrap-vue/issues/943))
  ([68138cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/68138cbdf0d3a2647e94cda073d6627e41de422c))
- **carousel:** Add img slot to carousel-slide
  ([#879](https://github.com/bootstrap-vue/bootstrap-vue/issues/879))
  ([9d789e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d789e7dcf3c47553e3676c81b282c08a5d4b8d5))
- **carousel:** Use b-img component and id Mixin
  ([#945](https://github.com/bootstrap-vue/bootstrap-vue/issues/945))
  ([d95321b](https://github.com/bootstrap-vue/bootstrap-vue/commit/d95321bbb11759c1467ca18ced22af849da52ea9))
- **col:** BS4 column component ([#906](https://github.com/bootstrap-vue/bootstrap-vue/issues/906))
  ([9de80f8](https://github.com/bootstrap-vue/bootstrap-vue/commit/9de80f8b215910543a0ade0c558b7c771efea281))
- **docs:** Add a new reference section
  ([#1050](https://github.com/bootstrap-vue/bootstrap-vue/issues/1050))
  ([7984117](https://github.com/bootstrap-vue/bootstrap-vue/commit/798411702d9d386b06933836d31ff452cd847496))
- **docs:** Add accessibility information for popovers
  ([099b1b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/099b1b67a17d7e8164a5635fe07fb51c9796664b))
- **docs:** Add aria roles to collapse accordion example
  ([2a34407](https://github.com/bootstrap-vue/bootstrap-vue/commit/2a344071d8c69e27a8303a68ec3227fa485c4fed))
- **docs:** Additional tooltip component usage docs
  ([d8bf486](https://github.com/bootstrap-vue/bootstrap-vue/commit/d8bf48609ec1afabb94b6639b7e396a7d17b69a6))
- **docs:** Expanded alert docs and examples
  ([f1730ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1730eeff209da7a8890f09a8eacdbab5983af24))
- **docs:** expanded popover component docs
  ([9f5dd75](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f5dd75271691c93adf94fbbc9354a54be3153ea))
- **docs:** Expanded popover component docs
  ([ccd1c7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ccd1c7c513fae3347d4583280a46f201da9b2450))
- **docs:** Improved collapse examples and documentation
  ([541fada](https://github.com/bootstrap-vue/bootstrap-vue/commit/541fada67a203af7f4d673b675150ac7dc6b4880))
- **docs:** New reference section wrt project relative urls and image based Bootstrap-Vue components
  ([#1072](https://github.com/bootstrap-vue/bootstrap-vue/issues/1072))
  ([7809fb2](https://github.com/bootstrap-vue/bootstrap-vue/commit/7809fb245331b01277d8464b4f35f7d0cde3e896))
- **docs:** starter examples ([#1061](https://github.com/bootstrap-vue/bootstrap-vue/issues/1061))
  ([dfc615f](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfc615f31ec33a1d3937c3277993edeec815d100))
- **docs:** Tooltip component documentation update
  ([c6b04a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6b04a66004d8c0b56435f8fa2864afb93fcb1bb))
- **docs:** Update tooltip directive example
  ([72a37b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/72a37b3bbd041ad87dec21f97b9d1a019609b106))
- **docs:** Updated b-img examples
  ([3ec187a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ec187a55001fee00d77f1eafe552c824b67f4c3))
- **docs:** Updated popover directive examples
  ([3adbcb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/3adbcb57a2dcfb30404a2451d7a6464a293babe0))
- **dom util:** new reflow, getBoundingClientRect, eventOn, eventOff methods
  ([#1052](https://github.com/bootstrap-vue/bootstrap-vue/issues/1052))
  ([346112d](https://github.com/bootstrap-vue/bootstrap-vue/commit/346112d5ac1d0a796ee034904a4d8f29862c1350)),
  closes [#1051](https://github.com/bootstrap-vue/bootstrap-vue/issues/1051)
- **dom utils:** Add getById method
  ([d73ff01](https://github.com/bootstrap-vue/bootstrap-vue/commit/d73ff01fb4be0544ede1fce52dcbd8fd31b5ce90))
- **dom utils:** Add offset and position methods
  ([baf15ca](https://github.com/bootstrap-vue/bootstrap-vue/commit/baf15caaefd9e5f55df8e33f85b7bfde2810073d))
- **dropdown:** Add auto ID generation
  ([#888](https://github.com/bootstrap-vue/bootstrap-vue/issues/888))
  ([25a20f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/25a20f2949a620bc7d2a062846a6d579eff8171b))
- **dropdowns:** Add hide() and show() methods
  ([#1012](https://github.com/bootstrap-vue/bootstrap-vue/issues/1012))
  ([a2a9bc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2a9bc4cec1ece3ae768dce3f94421186b0115c1)),
  closes [#1011](https://github.com/bootstrap-vue/bootstrap-vue/issues/1011)
- **embed:** New component b-embed for responsive video embeds
  ([#985](https://github.com/bootstrap-vue/bootstrap-vue/issues/985))
  ([e29c429](https://github.com/bootstrap-vue/bootstrap-vue/commit/e29c42975e03acd978c17add4cedc52cd779bbbf))
- **form-file:** Add focus styling for custom-file input
  ([#1033](https://github.com/bootstrap-vue/bootstrap-vue/issues/1033))
  ([72ffba9](https://github.com/bootstrap-vue/bootstrap-vue/commit/72ffba9695f568a97694e52a485607b74e4738cc))
- **form-file:** Propagate `capture` attribute to file input
  ([d7e4f8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7e4f8aa04882af9ed48ffe8e8b992f1b356e4e0))
- **forms:** Auto ID generation client side if no id prop provided
  ([#882](https://github.com/bootstrap-vue/bootstrap-vue/issues/882))
  ([da39b86](https://github.com/bootstrap-vue/bootstrap-vue/commit/da39b86c1c6988e62d7b0cf7276b4d217c5e3378))
- **forms:** New handling of form-select, form-radios and form-checkboxes
  ([#994](https://github.com/bootstrap-vue/bootstrap-vue/issues/994))
  ([0a50398](https://github.com/bootstrap-vue/bootstrap-vue/commit/0a50398cd03e9b016ea1c87a82a79268f8e5945a)),
  closes [#1038](https://github.com/bootstrap-vue/bootstrap-vue/issues/1038)
  [#995](https://github.com/bootstrap-vue/bootstrap-vue/issues/995)
  [#999](https://github.com/bootstrap-vue/bootstrap-vue/issues/999)
  [#1000](https://github.com/bootstrap-vue/bootstrap-vue/issues/1000)
  [#1004](https://github.com/bootstrap-vue/bootstrap-vue/issues/1004)
  [#1003](https://github.com/bootstrap-vue/bootstrap-vue/issues/1003)
  [#991](https://github.com/bootstrap-vue/bootstrap-vue/issues/991)
  [#1006](https://github.com/bootstrap-vue/bootstrap-vue/issues/1006)
  [#1005](https://github.com/bootstrap-vue/bootstrap-vue/issues/1005)
  [#1012](https://github.com/bootstrap-vue/bootstrap-vue/issues/1012)
  [#1011](https://github.com/bootstrap-vue/bootstrap-vue/issues/1011)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#1021](https://github.com/bootstrap-vue/bootstrap-vue/issues/1021)
  [#1016](https://github.com/bootstrap-vue/bootstrap-vue/issues/1016)
  [#1018](https://github.com/bootstrap-vue/bootstrap-vue/issues/1018)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#940](https://github.com/bootstrap-vue/bootstrap-vue/issues/940)
  [#1024](https://github.com/bootstrap-vue/bootstrap-vue/issues/1024)
  [#1033](https://github.com/bootstrap-vue/bootstrap-vue/issues/1033)
  [#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025)
  [#1037](https://github.com/bootstrap-vue/bootstrap-vue/issues/1037)
  [#1040](https://github.com/bootstrap-vue/bootstrap-vue/issues/1040)
  [#995](https://github.com/bootstrap-vue/bootstrap-vue/issues/995)
  [#999](https://github.com/bootstrap-vue/bootstrap-vue/issues/999)
  [#1000](https://github.com/bootstrap-vue/bootstrap-vue/issues/1000)
  [#1004](https://github.com/bootstrap-vue/bootstrap-vue/issues/1004)
  [#1003](https://github.com/bootstrap-vue/bootstrap-vue/issues/1003)
  [#991](https://github.com/bootstrap-vue/bootstrap-vue/issues/991)
  [#1006](https://github.com/bootstrap-vue/bootstrap-vue/issues/1006)
  [#1005](https://github.com/bootstrap-vue/bootstrap-vue/issues/1005)
  [#1012](https://github.com/bootstrap-vue/bootstrap-vue/issues/1012)
  [#1011](https://github.com/bootstrap-vue/bootstrap-vue/issues/1011)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#1021](https://github.com/bootstrap-vue/bootstrap-vue/issues/1021)
  [#1016](https://github.com/bootstrap-vue/bootstrap-vue/issues/1016)
  [#1018](https://github.com/bootstrap-vue/bootstrap-vue/issues/1018)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#940](https://github.com/bootstrap-vue/bootstrap-vue/issues/940)
  [#1024](https://github.com/bootstrap-vue/bootstrap-vue/issues/1024)
  [#1033](https://github.com/bootstrap-vue/bootstrap-vue/issues/1033)
  [#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025)
  [#1037](https://github.com/bootstrap-vue/bootstrap-vue/issues/1037)
  [#1039](https://github.com/bootstrap-vue/bootstrap-vue/issues/1039)
  [#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025)
- **img:** Add 'block' prop to set display mode to block
  ([6be7390](https://github.com/bootstrap-vue/bootstrap-vue/commit/6be73904302b89d65d1b00dbd7134644fe9aa9df))
- **input-group:** Add prop tag to change root element type
  ([800add6](https://github.com/bootstrap-vue/bootstrap-vue/commit/800add6133c9bb937775adfd5fd35f3b85fb74eb))
- **jumbotron:** Add support for variants
  ([#973](https://github.com/bootstrap-vue/bootstrap-vue/issues/973))
  ([bd9bb7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd9bb7cad48c2ba0e99f73808c193e89ec0ebb6e))
- **jumbotron:** Convert to functional component
  ([#932](https://github.com/bootstrap-vue/bootstrap-vue/issues/932))
  ([5f2df53](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f2df53df71a4ba7a831fe87730b8223aef3c223)),
  closes [#935](https://github.com/bootstrap-vue/bootstrap-vue/issues/935)
  [#934](https://github.com/bootstrap-vue/bootstrap-vue/issues/934)
  [#929](https://github.com/bootstrap-vue/bootstrap-vue/issues/929)
- **layout:** alignment utilities 🛠
  ([#941](https://github.com/bootstrap-vue/bootstrap-vue/issues/941))
  ([3435ac5](https://github.com/bootstrap-vue/bootstrap-vue/commit/3435ac55cc8df9fed616a9b7a88f25707f8a1aed))
- **list-group:** new list-group functional components
  ([#861](https://github.com/bootstrap-vue/bootstrap-vue/issues/861))
  ([c516d89](https://github.com/bootstrap-vue/bootstrap-vue/commit/c516d89ed6014836708941baa26b2c645660c0dd))
- **media:** new functional media components
  ([#872](https://github.com/bootstrap-vue/bootstrap-vue/issues/872))
  ([91ff681](https://github.com/bootstrap-vue/bootstrap-vue/commit/91ff681b8ef6b22df6fc8133c83b23ef339f36cb))
- **modal:** Add lazy loaded modal support
  ([#1046](https://github.com/bootstrap-vue/bootstrap-vue/issues/1046))
  ([7afcf81](https://github.com/bootstrap-vue/bootstrap-vue/commit/7afcf812e2943803127c3ece379ab4a892f40f24))
- **modal:** Add props to change the variant of the default modal buttons
  ([#1004](https://github.com/bootstrap-vue/bootstrap-vue/issues/1004))
  ([36acf4e](https://github.com/bootstrap-vue/bootstrap-vue/commit/36acf4e64d85046218cad8480cb22f1d1996d7df))
- **modal:** Improve modal transitions, padding adjustments, and aditional features
  ([#1024](https://github.com/bootstrap-vue/bootstrap-vue/issues/1024))
  ([dd5ddb0](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd5ddb026a123de8f3dee48656950d27a228c607))
- **nav:** new functional nav components
  ([#864](https://github.com/bootstrap-vue/bootstrap-vue/issues/864))
  ([ecec23d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecec23dda3f72dc5e311eb968003ddd731f591fe))
- **popover:** Add ability to disable fade animation in component version
  ([7161b5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/7161b5fa1ab437812ba68c08d4c4b5018a1d56f1))
- **popover:** Add deactivated hook to component to hide popover
  ([4a70215](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a702157cfb9535fb14a6ad1e439c713f8dacea6))
- **popover:** import fix
  ([b24764f](https://github.com/bootstrap-vue/bootstrap-vue/commit/b24764f65ad4ecf34e2b0ac194c37845e1b65395))
- **popover+tooltip:** Add hide event listener on $root
  ([#1003](https://github.com/bootstrap-vue/bootstrap-vue/issues/1003))
  ([6b12629](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b12629da279e7f85b4314b7f663b49cc496b5ff))
- **progress:** Support for multiple progress bars
  ([#889](https://github.com/bootstrap-vue/bootstrap-vue/issues/889))
  ([76c613c](https://github.com/bootstrap-vue/bootstrap-vue/commit/76c613cbdf4d2524b81b8e11e42271feb84f39c9))
- **readme:** add package quality badge
  ([#907](https://github.com/bootstrap-vue/bootstrap-vue/issues/907))
  ([6bd9f52](https://github.com/bootstrap-vue/bootstrap-vue/commit/6bd9f52dda7d22936e68fe25e186f3f1f7117a0c))
- **table:** Allow fields to be an array of objects
  ([#1075](https://github.com/bootstrap-vue/bootstrap-vue/issues/1075))
  ([e2f90ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/e2f90ff47619ef2e79128fd4f53bd7b30eb26768))
- **table:** easier usage
  ([019f8fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/019f8fad1eb129a85e512406f433640a215c741a))
- **table:** Include native event object with row-_ and head-_ events
  ([#892](https://github.com/bootstrap-vue/bootstrap-vue/issues/892))
  ([92d2794](https://github.com/bootstrap-vue/bootstrap-vue/commit/92d2794b2dfc67bd575eaa52b5d6fe97f6fff9fb))
- **table:** Refactor field formatter support + optimized sort-compare handling
  ([#991](https://github.com/bootstrap-vue/bootstrap-vue/issues/991))
  ([b66f994](https://github.com/bootstrap-vue/bootstrap-vue/commit/b66f994fcde9376033b55110fa395a948e4d8982))
- **table:** Scoped slots for fixed top/bottom rows
  ([#908](https://github.com/bootstrap-vue/bootstrap-vue/issues/908))
  ([3c761e2](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c761e209dc85b69b9fa6d9ed674b74032a15c1d))
- **table:** use computedFields for easier usage
  ([b9980f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9980f0c136a012ff0b2c6892398c733bca7e95a))
- **tooltip:** Add ability to disable fade animation in component version
  ([36c428a](https://github.com/bootstrap-vue/bootstrap-vue/commit/36c428aa962d970ad4cfc60cabd1152b5b68c600))
- **tooltip popover:** Better DOM change observation in component versions
  ([f723807](https://github.com/bootstrap-vue/bootstrap-vue/commit/f723807abc75d34501073e7dd8442db1b7ac1823))
- **tooltip+popover:** Create mixin for common props and methods
  ([#1021](https://github.com/bootstrap-vue/bootstrap-vue/issues/1021))
  ([edc7b20](https://github.com/bootstrap-vue/bootstrap-vue/commit/edc7b207a1ec6701aee39cf1ea2d916642cfe581))
- dom utility methods ([#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013))
  ([7ed199d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ed199d703e8664ff192345ba9d03ebcb7c3176e))
- Use dom utils ([#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017))
  ([5ca9fe3](https://github.com/bootstrap-vue/bootstrap-vue/commit/5ca9fe3ec58033725ddf766060fccb9cfd50f848))
- **tooltip:** Add deactivated hook to component
  ([ae605d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae605d39f8ab10f82ed1d607c2d946baafb4c79f))
- **tooltip+popover:** Add container prop to component versions
  ([#983](https://github.com/bootstrap-vue/bootstrap-vue/issues/983))
  ([860cb3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/860cb3cfd9c74f88b69ae3f717cb93218989a186))
- **tooltip+popover:** Allow element and component reference for target
  ([#980](https://github.com/bootstrap-vue/bootstrap-vue/issues/980))
  ([8785066](https://github.com/bootstrap-vue/bootstrap-vue/commit/8785066b16d2615c2a3d539b7221be802435cb10))
- **tooltips+popovers:** Add special blur "exit" trigger
  ([#974](https://github.com/bootstrap-vue/bootstrap-vue/issues/974))
  ([785b7a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/785b7a6cb3e23f66309abc0a371226944cec6681))
- **tooltips+popovers:** Automatically hide when trigger element is no longer visible
  ([#978](https://github.com/bootstrap-vue/bootstrap-vue/issues/978))
  ([09eaaa2](https://github.com/bootstrap-vue/bootstrap-vue/commit/09eaaa2ec9dcf03aba6cba915c4b3bb1353f41f0))
- New popper.js based tooltip/popover directives and components
  ([#923](https://github.com/bootstrap-vue/bootstrap-vue/issues/923))
  ([33c4cab](https://github.com/bootstrap-vue/bootstrap-vue/commit/33c4cab68984ca934e174e53f1f85995d003641e))
- **addEventListenerOnce:** add to utils
  ([0869ffd](https://github.com/bootstrap-vue/bootstrap-vue/commit/0869ffdc9ed80ad37645c0f550ca19e26c9817b0))
- **addEventListenerOnce:** New utility function
  ([6b4efdf](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b4efdfb559988fc278e107d65a8bb6a4fc6381f))
- **alert:** Hide dismiss button for auto-dismissing alerts
  ([#791](https://github.com/bootstrap-vue/bootstrap-vue/issues/791))
  ([080bb20](https://github.com/bootstrap-vue/bootstrap-vue/commit/080bb204318ad59fea18e56b1a18ce1cd5dc3d0a))
- **badge:** functional component
  ([#820](https://github.com/bootstrap-vue/bootstrap-vue/issues/820))
  ([8c172c1](https://github.com/bootstrap-vue/bootstrap-vue/commit/8c172c18a298b7e269526085babf17b408169db9))
- **btn-group:** functional component for button-group
  ([#822](https://github.com/bootstrap-vue/bootstrap-vue/issues/822))
  ([6891e9f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6891e9f7c3e90796c65205636cca5b280f466e5b))
- **button:** Add pressed prop to place button in active state
  ([#715](https://github.com/bootstrap-vue/bootstrap-vue/issues/715))
  ([61a104f](https://github.com/bootstrap-vue/bootstrap-vue/commit/61a104fab0d835acfcca7fce2f20b240278fcc12))
- **button:** refactor toggle button focus handler
  ([#730](https://github.com/bootstrap-vue/bootstrap-vue/issues/730))
  ([3ab3d89](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ab3d89b23b39ff29be7736004f134db47dbe993))
- **button:** set light as default variant
  ([2a72576](https://github.com/bootstrap-vue/bootstrap-vue/commit/2a725767e6828a10c58dae43392e9f3c08f00925))
- **card:** add card-body functional component & card-img fixes
  ([#843](https://github.com/bootstrap-vue/bootstrap-vue/issues/843))
  ([f88ab23](https://github.com/bootstrap-vue/bootstrap-vue/commit/f88ab23edcf65a761be3f07c553927eab92ae162))
- **card:** change card-block to card-body
  ([30d35a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/30d35a74cff8c113e41685e130d2e58fdba21c7b))
- **card:** functional components for card
  ([#827](https://github.com/bootstrap-vue/bootstrap-vue/issues/827))
  ([2089252](https://github.com/bootstrap-vue/bootstrap-vue/commit/2089252ba3b7d3a8589f772c4b6273e389608b64))
- **carousel:** Add v-model support (issue
  [#743](https://github.com/bootstrap-vue/bootstrap-vue/issues/743))
  ([#744](https://github.com/bootstrap-vue/bootstrap-vue/issues/744))
  ([028eb5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/028eb5fddf4c31406416034190213a462819c391))
- **carousel:** Transition event with setTimeout fallback
  ([8e6fc42](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e6fc42f0829c5ca0d17f207270f8984ee8cbb05))
- **carousel:** Use transitionend event instead of setTimeout
  ([192dfb8](https://github.com/bootstrap-vue/bootstrap-vue/commit/192dfb824ca806ee398cebdcc0a93a109b33d93a))
- **checkbox:** Add indeterminate state prop
  ([#720](https://github.com/bootstrap-vue/bootstrap-vue/issues/720))
  ([2271e7a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2271e7ad57206289eb6cd7e29289605a4a2e52fb))
- **collapse:** apply bootstrap classes during transition stages (issue
  [#565](https://github.com/bootstrap-vue/bootstrap-vue/issues/565))
  ([#707](https://github.com/bootstrap-vue/bootstrap-vue/issues/707))
  ([947d253](https://github.com/bootstrap-vue/bootstrap-vue/commit/947d253dad7f08a677aba095463e988624e60eee))
- **collapse:** Close navbar collapse when clicked in nav/navbar (issue
  [#712](https://github.com/bootstrap-vue/bootstrap-vue/issues/712))
  ([#714](https://github.com/bootstrap-vue/bootstrap-vue/issues/714))
  ([f104dc0](https://github.com/bootstrap-vue/bootstrap-vue/commit/f104dc04c370889db20aa7a11d0295eb5a2e05f2))
- **docs:** changelog page
  ([b2482cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b2482cb909f4e5723a3f7f8a6495309d544e01ce))
- **docs:** live demo ([#602](https://github.com/bootstrap-vue/bootstrap-vue/issues/602))
  ([843057e](https://github.com/bootstrap-vue/bootstrap-vue/commit/843057e47f71e62ec970b57c1eef4252640e13f6))
- **docs:** Native event capturing docs
  ([#605](https://github.com/bootstrap-vue/bootstrap-vue/issues/605))
  ([c2c200b](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2c200bed13966f53e71db799266ebe4abfedd15))
- **docs:** prepare for 1.0.0-beta
  ([8e46552](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e465526ae44c4ae3326a9c5526534285fdccb3d))
- **dropdowns:** functional dropdown sub-components and testing
  ([#848](https://github.com/bootstrap-vue/bootstrap-vue/issues/848))
  ([2bd562b](https://github.com/bootstrap-vue/bootstrap-vue/commit/2bd562bb0e3322522366f1d28d8e38139b49339b))
- **dropdowns:** Various optimizations for dropdown components
  ([#627](https://github.com/bootstrap-vue/bootstrap-vue/issues/627))
  ([56d29b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/56d29b0aa4270e6a9ccbe86278b7edd413970203))
- **Event:** standard evt obj emulates native Event
  ([#726](https://github.com/bootstrap-vue/bootstrap-vue/issues/726))
  ([919344b](https://github.com/bootstrap-vue/bootstrap-vue/commit/919344be16de8935472efdc69ee2b69455cec38f))
- **form:** Swith to functional component
  ([#865](https://github.com/bootstrap-vue/bootstrap-vue/issues/865))
  ([c9f054d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9f054dcd87fce9203ee09cec851da382e5250d8))
- **form controls:** Add required attribute and related ARIA support
  ([#613](https://github.com/bootstrap-vue/bootstrap-vue/issues/613))
  ([3db70a4](https://github.com/bootstrap-vue/bootstrap-vue/commit/3db70a48523fed5d992cb9fbc9d9ae2c30418a18))
- **form controls:** Optimize props
  ([#604](https://github.com/bootstrap-vue/bootstrap-vue/issues/604))
  ([35a5db6](https://github.com/bootstrap-vue/bootstrap-vue/commit/35a5db6e63f5e4bf9abac089c5bf680e7224959e))
- **form-checkbox:** Support button style checkbox
  ([#729](https://github.com/bootstrap-vue/bootstrap-vue/issues/729))
  ([740d7cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/740d7cb9f9b166ae8359884c9adda26a22d66878))
- **form-fieldset:** Add alias of b-form-group
  ([eebe36d](https://github.com/bootstrap-vue/bootstrap-vue/commit/eebe36de67fa9ef4fb6ffbc3065ffe085a198fe4))
- **form-fieldset:** label, description, and feedback slots, deprecate label-size
  ([#598](https://github.com/bootstrap-vue/bootstrap-vue/issues/598))
  ([e253dae](https://github.com/bootstrap-vue/bootstrap-vue/commit/e253daeb00d6d6d1fee1a7ae5bd9aec7de3b12f7))
- **form-input:** Add autocomplete prop
  ([#750](https://github.com/bootstrap-vue/bootstrap-vue/issues/750))
  ([d686787](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6867878a0130e4ce24d505a0b9820a328f918db))
- **form-input:** Pass input element to formatter (issue
  [#772](https://github.com/bootstrap-vue/bootstrap-vue/issues/772))
  ([#773](https://github.com/bootstrap-vue/bootstrap-vue/issues/773))
  ([da77f15](https://github.com/bootstrap-vue/bootstrap-vue/commit/da77f1569372a58c1b5851a4af38be2a2fb06f80))
- **form-input:** support aria-invalid attribute
  ([#610](https://github.com/bootstrap-vue/bootstrap-vue/issues/610))
  ([d676d8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/d676d8fc9424804b979d8d891afdf5242d472088))
- **form-radio:** Add support for aria-invalid
  ([#612](https://github.com/bootstrap-vue/bootstrap-vue/issues/612))
  ([69e449f](https://github.com/bootstrap-vue/bootstrap-vue/commit/69e449fe3990240d669772d9da185fbc7c8d2d20))
- **form-radio:** ARIA - Add IDs to individual radios
  ([#663](https://github.com/bootstrap-vue/bootstrap-vue/issues/663))
  ([1de785e](https://github.com/bootstrap-vue/bootstrap-vue/commit/1de785e4e25bab8fa94b02fd1215099a9d7b1a0e))
- **form-radio:** Support button style radios
  ([#728](https://github.com/bootstrap-vue/bootstrap-vue/issues/728))
  ([c7c150f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7c150f3814182563fc703edad31a7207097ada2))
- **form-row:** New functional component
  ([#844](https://github.com/bootstrap-vue/bootstrap-vue/issues/844))
  ([1e0f313](https://github.com/bootstrap-vue/bootstrap-vue/commit/1e0f313069e4456b3a0f5caa3116eaa277c966c8))
- **form-select:** Add aria-invalid support
  ([#611](https://github.com/bootstrap-vue/bootstrap-vue/issues/611))
  ([1d20f8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d20f8ae54ba0d58585570e54fdf18a9729b6b4d))
- **form-select:** add key for v-for
  ([299a2ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/299a2eae3993d0129fae5ceab5de486f8460fa1b))
- **form-select:** Add multiple select support (issue
  [#619](https://github.com/bootstrap-vue/bootstrap-vue/issues/619))
  ([#731](https://github.com/bootstrap-vue/bootstrap-vue/issues/731))
  ([19bf2f5](https://github.com/bootstrap-vue/bootstrap-vue/commit/19bf2f54d4ff7693429e51f4c7c61973eb24cc10))
- **form-select:** Allow selectSize to be set when not in multiple mode (Issue
  [#761](https://github.com/bootstrap-vue/bootstrap-vue/issues/761))
  ([#762](https://github.com/bootstrap-vue/bootstrap-vue/issues/762))
  ([6f04090](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f040904f51baf557a8b6265c22c844464773298))
- **form-text:** New functional component
  ([#846](https://github.com/bootstrap-vue/bootstrap-vue/issues/846))
  ([2ed7470](https://github.com/bootstrap-vue/bootstrap-vue/commit/2ed74707afeef9c1b7fc665aa2509db18c8a3f63))
- **listenonroot:** Use a constant for private property name
  ([#700](https://github.com/bootstrap-vue/bootstrap-vue/issues/700))
  ([26c8a3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/26c8a3ecde2582bc2c6cba742971d7957d16c2b9))
- **mixin:** Automate event registration & removal on root vm
  ([#581](https://github.com/bootstrap-vue/bootstrap-vue/issues/581))
  ([be5f834](https://github.com/bootstrap-vue/bootstrap-vue/commit/be5f8341b6e45863b427d6d2ab8cbdfb0d350e14))
- **modal:** Make enforceFocus configurable
  ([#706](https://github.com/bootstrap-vue/bootstrap-vue/issues/706))
  ([f1ab80b](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1ab80b42d7d02ded2c7aba310755d186a0ce3a3))
- **navbar:** change navbar-toggelable to navbar-expand-\*
  ([1fab033](https://github.com/bootstrap-vue/bootstrap-vue/commit/1fab0338250199a3229c80a4ae24459d49677c1d))
- **navbar-brand:** New component <b-navbar-brand>
  ([#710](https://github.com/bootstrap-vue/bootstrap-vue/issues/710))
  ([721292c](https://github.com/bootstrap-vue/bootstrap-vue/commit/721292cad0a107b1884a5186a102e6d3d772fb90))
- **pagination-nav:** New navigation pagination component
  ([#816](https://github.com/bootstrap-vue/bootstrap-vue/issues/816))
  ([3a4272c](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a4272cc04a6b0f2291d10d09d6877b3ba3bfc30))
- **progress:** Add height prop ([#837](https://github.com/bootstrap-vue/bootstrap-vue/issues/837))
  ([8a52b93](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a52b937e8f94d1c37376c3c14ddba7bb6ae8c9c))
- link, breadcrumb, & button functional components
  ([#830](https://github.com/bootstrap-vue/bootstrap-vue/issues/830))
  ([cdbef2d](https://github.com/bootstrap-vue/bootstrap-vue/commit/cdbef2d720282144fb87fa53c1d4aec0b0e4bf1b))
- **pagination:** Add alignment prop
  ([#745](https://github.com/bootstrap-vue/bootstrap-vue/issues/745))
  ([a8e83a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8e83a7486d4d776e10c11f4e55798ff5de35ea5))
- **readme:** add david dep badge
  ([#724](https://github.com/bootstrap-vue/bootstrap-vue/issues/724))
  ([435a857](https://github.com/bootstrap-vue/bootstrap-vue/commit/435a85736563dc740dcc018ced6ff82db8c3797f))
- **table:** add field data formatter prop
  ([#739](https://github.com/bootstrap-vue/bootstrap-vue/issues/739))
  ([9da94a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/9da94a6a72c2527c01624a3d459a0c38520a8b96))
- **table:** Add row-dblclicked event
  ([#780](https://github.com/bootstrap-vue/bootstrap-vue/issues/780))
  ([1aaf915](https://github.com/bootstrap-vue/bootstrap-vue/commit/1aaf9150480a17a35884f639a037911b2624f111))
- **table:** Add syncable sort-by and sort-desc props
  ([#742](https://github.com/bootstrap-vue/bootstrap-vue/issues/742))
  ([c8ad5a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/c8ad5a3aec719701076a5fc99c055fa7153c0ed6))
- **table:** Emit event when local filtering changes number of result items - issue
  [#650](https://github.com/bootstrap-vue/bootstrap-vue/issues/650)
  ([#652](https://github.com/bootstrap-vue/bootstrap-vue/issues/652))
  ([1b2a36a](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b2a36ab4e29fb699f99d0e6237dbf93227a7bfb))
- **toggle directives:** allow simple elements to use directive
  ([#651](https://github.com/bootstrap-vue/bootstrap-vue/issues/651))
  ([3361911](https://github.com/bootstrap-vue/bootstrap-vue/commit/3361911a5d3cb7bf427d9f010359210a23e32168))
- **utils:** transpiler friendly polyfills and methods
  ([#658](https://github.com/bootstrap-vue/bootstrap-vue/issues/658))
  ([2ee9ed6](https://github.com/bootstrap-vue/bootstrap-vue/commit/2ee9ed6815cd6d615a5654c7f1d207cdb8f8a2ee))
- **utils:** wrap-up as ES6 module
  ([#656](https://github.com/bootstrap-vue/bootstrap-vue/issues/656))
  ([b5f7cfc](https://github.com/bootstrap-vue/bootstrap-vue/commit/b5f7cfc9defaf66ff950bd578cb01ee3ea1f395b))

### Bug Fixes

- **b-alert:** handle case where dismiss countdown changes to a boolean value (closes
  [#3346](https://github.com/bootstrap-vue/bootstrap-vue/issues/3346))
  ([#3347](https://github.com/bootstrap-vue/bootstrap-vue/issues/3347))
  ([14ad833](https://github.com/bootstrap-vue/bootstrap-vue/commit/14ad8330bde33979919254361ed3a8a2cbda6f6f))
- **b-avatar:** badge `z-index` handling
  ([#5975](https://github.com/bootstrap-vue/bootstrap-vue/issues/5975))
  ([ecb33bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecb33bdb510832096bc5a5196a11c97388bf6411))
- **b-avatar:** image fit and scale (closes
  [#5610](https://github.com/bootstrap-vue/bootstrap-vue/issues/5610),
  [#5655](https://github.com/bootstrap-vue/bootstrap-vue/issues/5655))
  ([#5675](https://github.com/bootstrap-vue/bootstrap-vue/issues/5675))
  ([9812248](https://github.com/bootstrap-vue/bootstrap-vue/commit/9812248ea686e339f32604c0020a1714bb228d75))
- **b-avatar:** prevent avatar from being squished
  ([#5963](https://github.com/bootstrap-vue/bootstrap-vue/issues/5963))
  ([b3946ed](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3946ed7a7b327fb7c66b44caaf122460fc24005)),
  closes [#5962](https://github.com/bootstrap-vue/bootstrap-vue/issues/5962)
- **b-badge:** attribute inheritance
  ([#6217](https://github.com/bootstrap-vue/bootstrap-vue/issues/6217))
  ([2d31f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/2d31f31909c002faa2a9d8bd8620115ddf8ce603))
- **b-button-toolbar:** allow focus to leave toolbar by keyboard
  ([#5737](https://github.com/bootstrap-vue/bootstrap-vue/issues/5737))
  ([f54e427](https://github.com/bootstrap-vue/bootstrap-vue/commit/f54e4275881947cfb504235aa9330c03444e08bb))
- **b-calendar:** month formatting for ceratin dates
  ([#5911](https://github.com/bootstrap-vue/bootstrap-vue/issues/5911))
  ([7de1844](https://github.com/bootstrap-vue/bootstrap-vue/commit/7de1844c6d5c0014d25c930527a7fc49a2b0cc25))
- **b-card:** properly support header/footer with body image overlay
  ([#5872](https://github.com/bootstrap-vue/bootstrap-vue/issues/5872))
  ([bd8319d](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd8319da8c6166f9fe3e64d9a3ac5c490c6b2f48))
- **b-carousel:** fix glitching when switching slides fast (closes
  [#5810](https://github.com/bootstrap-vue/bootstrap-vue/issues/5810))
  ([#5845](https://github.com/bootstrap-vue/bootstrap-vue/issues/5845))
  ([761bc93](https://github.com/bootstrap-vue/bootstrap-vue/commit/761bc9381ba24aed751726c8213651e2014aa746))
- **b-dropdown:** click handling on close (closes
  [#5982](https://github.com/bootstrap-vue/bootstrap-vue/issues/5982))
  ([#6009](https://github.com/bootstrap-vue/bootstrap-vue/issues/6009))
  ([cf7a1cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf7a1cb017e2263939a64e300abbbbac35c121d4))
- **b-dropdown:** decrease delay when hiding inside a navbar on no-touch devices (closes
  [#6306](https://github.com/bootstrap-vue/bootstrap-vue/issues/6306))
  ([#6367](https://github.com/bootstrap-vue/bootstrap-vue/issues/6367))
  ([7d72605](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d726056eb40a148afbafd0710035cb306582bb6))
- **b-dropdown:** only apply `heading` role to header when not a `header` tag
  ([#6274](https://github.com/bootstrap-vue/bootstrap-vue/issues/6274))
  ([bd67da0](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd67da0c40744e6b245a4e514e2319ca7bfafe2d))
- **b-dropdown:** root events ([#6198](https://github.com/bootstrap-vue/bootstrap-vue/issues/6198))
  ([6dcd233](https://github.com/bootstrap-vue/bootstrap-vue/commit/6dcd23334f2870220ed5c4d8b30bd556e57c03d5))
- **b-dropdown:** Sets correct `aria-haspopup` attribute for the toggle button
  ([#6865](https://github.com/bootstrap-vue/bootstrap-vue/issues/6865))
  ([d92c2f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/d92c2f1237b44102f0bf6eadd26d97423b9f8c2b))
- **b-form-checkbox:** `change` event value when in multiple mode
  ([#5716](https://github.com/bootstrap-vue/bootstrap-vue/issues/5716))
  ([5150b94](https://github.com/bootstrap-vue/bootstrap-vue/commit/5150b943f25ff6b2f331aaef64321973bd60dd0e))
- **b-form-checkbox-group:** only emit `input` when value loosely changes
  ([#5432](https://github.com/bootstrap-vue/bootstrap-vue/issues/5432))
  ([e76d408](https://github.com/bootstrap-vue/bootstrap-vue/commit/e76d40874bd2a42126162101e94bb18e9042840b))
- **b-form-checkbox/b-form-radio:** `chnage` event timing
  ([#6008](https://github.com/bootstrap-vue/bootstrap-vue/issues/6008))
  ([37ec7e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/37ec7e9991b66af51ff81420da8eb88928615f9d))
- **b-form-checkbox/b-form-radio:** remove `autocomplete="off"` attribute
  ([#5764](https://github.com/bootstrap-vue/bootstrap-vue/issues/5764))
  ([443aaf1](https://github.com/bootstrap-vue/bootstrap-vue/commit/443aaf1afc38dc029e0b142c11a39d360bbc98d2))
- **b-form-datepicker:** `valueAsDate` prop handling
  ([#6159](https://github.com/bootstrap-vue/bootstrap-vue/issues/6159))
  ([5cb8e0c](https://github.com/bootstrap-vue/bootstrap-vue/commit/5cb8e0c474ab750868379b4293d0eb5d52f5dd85))
- **b-form-datepicker/b-form-timepicker:** control size
  ([#6249](https://github.com/bootstrap-vue/bootstrap-vue/issues/6249))
  ([f2ffbeb](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2ffbeb85a71f0e3ac5c6ea55622771357c703e1))
- **b-form-datepicker/b-form-timepicker:** label styles when in `button-only` mode (closes
  [#6172](https://github.com/bootstrap-vue/bootstrap-vue/issues/6172))
  ([#6186](https://github.com/bootstrap-vue/bootstrap-vue/issues/6186))
  ([e8842ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8842bae98e83d16f3429b37f219ae61890a5c38))
- **b-form-datepicker/b-form-timepicker/b-nav-item-dropdown:** dropdown positioning handling (closes
  [#5700](https://github.com/bootstrap-vue/bootstrap-vue/issues/5700),
  [#5630](https://github.com/bootstrap-vue/bootstrap-vue/issues/5630))
  ([#5765](https://github.com/bootstrap-vue/bootstrap-vue/issues/5765))
  ([7ec2205](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ec2205a96e0d14772f1ed6c047a9808a32fbf82))
- **b-form-file:** drop handling for huge amounts of files (closes
  [#5615](https://github.com/bootstrap-vue/bootstrap-vue/issues/5615))
  ([#5685](https://github.com/bootstrap-vue/bootstrap-vue/issues/5685))
  ([d54b240](https://github.com/bootstrap-vue/bootstrap-vue/commit/d54b240adeb6eadfe8736f4926384a5c4d351bde))
- **b-form-group:** accessibility when `label-for` prop not set
  ([#6006](https://github.com/bootstrap-vue/bootstrap-vue/issues/6006))
  ([16f777b](https://github.com/bootstrap-vue/bootstrap-vue/commit/16f777b14bdcf9ebb6fae0325d355c7f5272bd98))
- **b-form-group:** content element ID handling (closes
  [#5930](https://github.com/bootstrap-vue/bootstrap-vue/issues/5930))
  ([#5933](https://github.com/bootstrap-vue/bootstrap-vue/issues/5933))
  ([fecd558](https://github.com/bootstrap-vue/bootstrap-vue/commit/fecd55814c4f4553348d8016cdf0d449f22228f7))
- **b-form-group:** remove `role="alert"` from valid/invalid feedback (closes
  [#6300](https://github.com/bootstrap-vue/bootstrap-vue/issues/6300),
  [#6307](https://github.com/bootstrap-vue/bootstrap-vue/issues/6307))
  ([#6346](https://github.com/bootstrap-vue/bootstrap-vue/issues/6346))
  ([c0959c4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0959c4df2552929d7fa68e28fb700297df291f8))
- **b-form-input:** fix debounce when value does not change
  ([#5632](https://github.com/bootstrap-vue/bootstrap-vue/issues/5632))
  ([111ca65](https://github.com/bootstrap-vue/bootstrap-vue/commit/111ca65240ab6941e2173ca44806aa0a75691c95))
- **b-form-input:** modified value handling
  ([#6084](https://github.com/bootstrap-vue/bootstrap-vue/issues/6084))
  ([d6d8e3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6d8e3c0f309ca16ede0c874bb787ab2fed7b380))
- **b-form-input/b-form-textarea:** legacy browser support (closes
  [#6283](https://github.com/bootstrap-vue/bootstrap-vue/issues/6283))
  ([#6345](https://github.com/bootstrap-vue/bootstrap-vue/issues/6345))
  ([a79d98a](https://github.com/bootstrap-vue/bootstrap-vue/commit/a79d98a78f68ba3c15e626928f5e5208aba05d2f))
- **b-form-spinbutton:** button markup
  ([#6101](https://github.com/bootstrap-vue/bootstrap-vue/issues/6101))
  ([5082976](https://github.com/bootstrap-vue/bootstrap-vue/commit/5082976e90264cadd84a4c9dbf339ce90fe49456))
- **b-form-tags:** ensure same height with or without tags
  ([#5752](https://github.com/bootstrap-vue/bootstrap-vue/issues/5752))
  ([07102f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/07102f988cfe8e8290189e73f50790f70bbb4639))
- **b-form-tags:** required handling (closes
  [#6094](https://github.com/bootstrap-vue/bootstrap-vue/issues/6094))
  ([#6103](https://github.com/bootstrap-vue/bootstrap-vue/issues/6103))
  ([2dc6b9d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dc6b9d5bc5fcb3cf1febda7d9e5b03d1ee9a3d0))
- **b-form-tags:** unit test ([#5586](https://github.com/bootstrap-vue/bootstrap-vue/issues/5586))
  ([f4d509a](https://github.com/bootstrap-vue/bootstrap-vue/commit/f4d509af647eaf87e2b635d08ff9431b25150650))
- **b-form-textarea:** `setStyle()` util usage
  ([bf7a65f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf7a65f87caf0d725033c35ee85c1e32ced82adc))
- **b-icon:** local component lookup
  ([edb6ed6](https://github.com/bootstrap-vue/bootstrap-vue/commit/edb6ed66757299a81e5fd1cc1cb2b4fc20ce2b5e))
- **b-icon:** local component lookup
  ([#5939](https://github.com/bootstrap-vue/bootstrap-vue/issues/5939))
  ([4586b49](https://github.com/bootstrap-vue/bootstrap-vue/commit/4586b49d99e4239dbebe2518f57022d6e4e20224))
- **b-icon:** title render handling
  ([#6233](https://github.com/bootstrap-vue/bootstrap-vue/issues/6233))
  ([b025047](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0250477e6b4228f1f228c2776c8c211d8a57f00))
- **b-icon:** use `aria-label` attribute instead of `alt`
  ([#5581](https://github.com/bootstrap-vue/bootstrap-vue/issues/5581))
  ([72a1363](https://github.com/bootstrap-vue/bootstrap-vue/commit/72a13635b94aedfab1fb6800f2a297fa306f63ef))
- **b-img:** Allow empty `alt` prop (fixes
  [#5524](https://github.com/bootstrap-vue/bootstrap-vue/issues/5524))
  ([#5545](https://github.com/bootstrap-vue/bootstrap-vue/issues/5545))
  ([b22829d](https://github.com/bootstrap-vue/bootstrap-vue/commit/b22829d064b6e3820ef66168ec766a57520f31eb))
- **b-img-lazy:** `blank` placeholder for Firefox (closes
  [#6320](https://github.com/bootstrap-vue/bootstrap-vue/issues/6320))
  ([#6349](https://github.com/bootstrap-vue/bootstrap-vue/issues/6349))
  ([9b297c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b297c9415744ddb7bd3d50bbe5957859a61123e))
- **b-img-lazy:** fix blank-src not work error
  ([#6302](https://github.com/bootstrap-vue/bootstrap-vue/issues/6302))
  ([a6ace2f](https://github.com/bootstrap-vue/bootstrap-vue/commit/a6ace2f229680e13b0f91c17458461b8afda9f7b))
- **b-input-tags:** not respecting custom `$input-color` (closes
  [#6388](https://github.com/bootstrap-vue/bootstrap-vue/issues/6388))
  ([#6389](https://github.com/bootstrap-vue/bootstrap-vue/issues/6389))
  ([9f045d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f045d47b1eae4036910a1e397ed17b664e259c5))
- **b-link:** `href` handling inconsistencies to `<router-link>` (closes
  [#5820](https://github.com/bootstrap-vue/bootstrap-vue/issues/5820))
  ([#5876](https://github.com/bootstrap-vue/bootstrap-vue/issues/5876))
  ([daea0e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/daea0e5c638de9ec45d39af5aa1e9f8a9e455422))
- **b-link:** `href` handling with live router (closes
  [#5927](https://github.com/bootstrap-vue/bootstrap-vue/issues/5927))
  ([#5934](https://github.com/bootstrap-vue/bootstrap-vue/issues/5934))
  ([8a367b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a367b6296b0aa9700f67633fd60fb351e2f7373))
- **b-link:** remove default values from `vue-router` pass-down props (closes
  [#6373](https://github.com/bootstrap-vue/bootstrap-vue/issues/6373))
  ([#6374](https://github.com/bootstrap-vue/bootstrap-vue/issues/6374))
  ([0a14828](https://github.com/bootstrap-vue/bootstrap-vue/commit/0a14828961846b907cf8243e1a14954911f802cf))
- **b-modal:** solve body padding not being removed
  ([#5771](https://github.com/bootstrap-vue/bootstrap-vue/issues/5771))
  ([78d51f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/78d51f1e7146cbed756853003a93b991c9f0d8bc))
- **b-nav-item-dropdown:** `boundary` handling in `<b-navbar>` (closes
  [#5789](https://github.com/bootstrap-vue/bootstrap-vue/issues/5789))
  ([#5794](https://github.com/bootstrap-vue/bootstrap-vue/issues/5794))
  ([73383bf](https://github.com/bootstrap-vue/bootstrap-vue/commit/73383bfd935c097604bf5ad39a9cc2d18961ba87))
- **b-pagination:** don't set initial page count twice
  ([#6200](https://github.com/bootstrap-vue/bootstrap-vue/issues/6200))
  ([d7394e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7394e3426e5b06797caef070137ec47b25ef62a))
- **b-pagination:** properly calculate number of links with `hide-ellipsis` option (closes
  [#5514](https://github.com/bootstrap-vue/bootstrap-vue/issues/5514))
  ([#5678](https://github.com/bootstrap-vue/bootstrap-vue/issues/5678))
  ([98e17ca](https://github.com/bootstrap-vue/bootstrap-vue/commit/98e17ca85588b858f5d74e217c48fa82f11f487f))
- **b-sekelton:** animation overflow issue for Safari
  ([#5863](https://github.com/bootstrap-vue/bootstrap-vue/issues/5863))
  ([bfd4f96](https://github.com/bootstrap-vue/bootstrap-vue/commit/bfd4f960d7056edcd2ccb1ae3930639d543d8b34))
- **b-sidebar:** make sure to not exceed 100% in height (closes
  [#6176](https://github.com/bootstrap-vue/bootstrap-vue/issues/6176))
  ([#6234](https://github.com/bootstrap-vue/bootstrap-vue/issues/6234))
  ([782e11d](https://github.com/bootstrap-vue/bootstrap-vue/commit/782e11dedf8ed9f362a1c44772d660adf24975a5))
- **b-skeleton:** accepts custom attributes
  ([#6858](https://github.com/bootstrap-vue/bootstrap-vue/issues/6858))
  ([9b1edc9](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b1edc978f7029facaf5a4f2a512b13cd43987a8))
- **b-skeleton:** add missing component exports
  ([#5806](https://github.com/bootstrap-vue/bootstrap-vue/issues/5806))
  ([871ce22](https://github.com/bootstrap-vue/bootstrap-vue/commit/871ce22504c4e64348b844c0e4306161317abf60))
- **b-table:** add missing `role="grid"` when selectable (closes
  [#6305](https://github.com/bootstrap-vue/bootstrap-vue/issues/6305))
  ([#6372](https://github.com/bootstrap-vue/bootstrap-vue/issues/6372))
  ([bc02fb8](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc02fb86198701f8f2ef7b05dadf59cd2c0381cd))
- **b-table:** add missing `sortKey` field type and correct a typo
  ([#6355](https://github.com/bootstrap-vue/bootstrap-vue/issues/6355))
  ([f5ca62f](https://github.com/bootstrap-vue/bootstrap-vue/commit/f5ca62faec6d5fb9e873b362b6efb153d419a7cc))
- **b-table:** allow `responsive` and `stacked` props together
  ([#6266](https://github.com/bootstrap-vue/bootstrap-vue/issues/6266))
  ([fa977a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa977a83cf21dd118e30f81aacf80d1c25b5c484))
- **b-table:** default `role` to `grid` when `selectable` and `table` otherwise
  ([#6383](https://github.com/bootstrap-vue/bootstrap-vue/issues/6383))
  ([3f5a309](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f5a3095500c706a75f0f0d6015b0b2777051e1f)),
  closes [#6326](https://github.com/bootstrap-vue/bootstrap-vue/issues/6326)
- **b-table:** fix range selection of b-table
  ([#6606](https://github.com/bootstrap-vue/bootstrap-vue/issues/6606))
  ([c11f0db](https://github.com/bootstrap-vue/bootstrap-vue/commit/c11f0db211aa2c45209a4081ae4e02337ec55015))
- **b-table:** header cell overflow for `.sr-only` sort label
  ([#6371](https://github.com/bootstrap-vue/bootstrap-vue/issues/6371))
  ([11617b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/11617b4c78d06a0f48306983621fdb4ec1aa9932))
- **b-table:** make sure to apply all formatters of field configuration (closes
  [#5672](https://github.com/bootstrap-vue/bootstrap-vue/issues/5672))
  ([#5674](https://github.com/bootstrap-vue/bootstrap-vue/issues/5674))
  ([c7c14ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7c14ea1d023b26af8a12c12dbc2c3d8220b7f67))
- **b-table:** only set `aria-describedby` when caption really exists
  ([#6251](https://github.com/bootstrap-vue/bootstrap-vue/issues/6251))
  ([b980017](https://github.com/bootstrap-vue/bootstrap-vue/commit/b980017139613db5d7c8df4293a4d80673c9e646))
- **b-table:** only set `tabindex="0"` for sortable TH's
  ([#6102](https://github.com/bootstrap-vue/bootstrap-vue/issues/6102))
  ([dd23742](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd237425e4e7a7e73d5c17210780b02dab2110e2))
- **b-table:** prefer user-provided `role` attribute
  ([#6382](https://github.com/bootstrap-vue/bootstrap-vue/issues/6382))
  ([9e25a3b](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e25a3b97e911e84473991def78c9b4307b6f822))
- **b-table:** prevent endless reevaluation when using v-model and object/array literal prop values
  ([#5554](https://github.com/bootstrap-vue/bootstrap-vue/issues/5554))
  ([f127d91](https://github.com/bootstrap-vue/bootstrap-vue/commit/f127d916d1ddd3a3da37bcb081150f86b356a7a4))
- **b-table:** properly handle empty included/excluded filter fields (closes
  [#5775](https://github.com/bootstrap-vue/bootstrap-vue/issues/5775))
  ([#5780](https://github.com/bootstrap-vue/bootstrap-vue/issues/5780))
  ([78ac383](https://github.com/bootstrap-vue/bootstrap-vue/commit/78ac383c0c727be4f970874e73bf05e3f23b1a3b))
- **b-table:** selected table header text no longer prevents table row selection
  ([#6645](https://github.com/bootstrap-vue/bootstrap-vue/issues/6645))
  ([010ab31](https://github.com/bootstrap-vue/bootstrap-vue/commit/010ab3180eaeb9f43e9c922fb6e47419504b8f99))
- **b-table:** set `aria-sort` when using `sortKey` and `no-local-sorting` (closes
  [#6602](https://github.com/bootstrap-vue/bootstrap-vue/issues/6602))
  ([#6603](https://github.com/bootstrap-vue/bootstrap-vue/issues/6603))
  ([2438137](https://github.com/bootstrap-vue/bootstrap-vue/commit/2438137c3757b28657e7185432805079ee25c559))
- **b-table:** sort handling for numeric string values (closes
  [#6092](https://github.com/bootstrap-vue/bootstrap-vue/issues/6092))
  ([#6105](https://github.com/bootstrap-vue/bootstrap-vue/issues/6105))
  ([29fbcb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/29fbcb58c5efed0dbbafa8b0bb5fc1d1651079cd))
- **b-tabs:** cleanup rendering logic
  ([#6154](https://github.com/bootstrap-vue/bootstrap-vue/issues/6154))
  ([8aeb9e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/8aeb9e941e84ec45a3415ab7238729458f56e427))
- **b-tabs:** restore correct active tab detection logic (closes
  [#6205](https://github.com/bootstrap-vue/bootstrap-vue/issues/6205))
  ([#6208](https://github.com/bootstrap-vue/bootstrap-vue/issues/6208))
  ([6d92a43](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d92a4376c227a02a7c24e19c04e437bb8909c1c))
- **b-tags:** replace spacing utility with static CSS (fixes
  [#5523](https://github.com/bootstrap-vue/bootstrap-vue/issues/5523))
  ([#5544](https://github.com/bootstrap-vue/bootstrap-vue/issues/5544))
  ([e0de687](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0de6871640db405e7b0bfa23f3c33f348894cea))
- **b-tooltip, b-popover:** fix `title` not being reset on hide
  ([#5793](https://github.com/bootstrap-vue/bootstrap-vue/issues/5793))
  ([31eeb0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/31eeb0ab5ef262c33579f43969c7d6ee6c802e3d))
- **bv-tooltip:** hide the tooltip when the title is set to empty (closes
  [#5648](https://github.com/bootstrap-vue/bootstrap-vue/issues/5648))
  ([#5677](https://github.com/bootstrap-vue/bootstrap-vue/issues/5677))
  ([5363a31](https://github.com/bootstrap-vue/bootstrap-vue/commit/5363a3132df898cb5f0cac172c0510aead62d66e))
- **compat:** correctly handle undefined in slots
  ([725d31b](https://github.com/bootstrap-vue/bootstrap-vue/commit/725d31b9a9fed29e0e7d0e2685ab89d8f1b9e98a))
- **docs:** completing the url so that the link is correct
  ([#6545](https://github.com/bootstrap-vue/bootstrap-vue/issues/6545))
  ([c9c85a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9c85a92460c583439f96b61095e2fa0f3c41378))
- **nav-item-dropdown:** update dropdown to set correct aria-controls
  ([97bb97b](https://github.com/bootstrap-vue/bootstrap-vue/commit/97bb97b004b28bc34a49fc20dcc5b247f228404f))
- **perf:** reactivity issues with `bvAttrs` and `bvListeners` (closes
  [#5520](https://github.com/bootstrap-vue/bootstrap-vue/issues/5520))
  ([#5753](https://github.com/bootstrap-vue/bootstrap-vue/issues/5753))
  ([d83a2b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/d83a2b179cac2f7449a7138fce71e07139e18c94))
- **table:** default sort compare logic for date strings
  ([#6153](https://github.com/bootstrap-vue/bootstrap-vue/issues/6153))
  ([3696a1f](https://github.com/bootstrap-vue/bootstrap-vue/commit/3696a1f888f2462a428431a593e235fd89bf54d4))
- **util:** retain parent-child relationship for Vue 2
  ([58e2d7e](https://github.com/bootstrap-vue/bootstrap-vue/commit/58e2d7e4f5e883207c4f7baa856532d3ae924a0c))
- **utils/dom:** bind `requestAF()` to `window`
  ([#6508](https://github.com/bootstrap-vue/bootstrap-vue/issues/6508))
  ([#6511](https://github.com/bootstrap-vue/bootstrap-vue/issues/6511))
  ([f8caaec](https://github.com/bootstrap-vue/bootstrap-vue/commit/f8caaec837b184d3f2736a6fdb4b8ceea28942ae))
- **v-b-toggle:** prevent scroll anchoring behavior (closes
  [#5715](https://github.com/bootstrap-vue/bootstrap-vue/issues/5715))
  ([#5769](https://github.com/bootstrap-vue/bootstrap-vue/issues/5769))
  ([390a5c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/390a5c7045432c98999ae8bf9259fb9ae03bcb19))
- **v-tooltip, v-popover:** render data-\* attributes on root components (closes
  [#5836](https://github.com/bootstrap-vue/bootstrap-vue/issues/5836))
  ([#5882](https://github.com/bootstrap-vue/bootstrap-vue/issues/5882))
  ([f6b51e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6b51e04f074e45e98650034e88c2b5629ad25f6))
- **vue3:** do not rely on \_\_vueParentComponent in tooltip
  ([fe13503](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe13503f7aa6d0bd6f7e1ed4f4a2e7acff421106))
- clean up props inheritance ([#6265](https://github.com/bootstrap-vue/bootstrap-vue/issues/6265))
  ([79784ae](https://github.com/bootstrap-vue/bootstrap-vue/commit/79784ae6e03f90ee14ce90f8f5e02d0249eb5c4a))
- CodeSandbox integration ([#5381](https://github.com/bootstrap-vue/bootstrap-vue/issues/5381))
  ([a948846](https://github.com/bootstrap-vue/bootstrap-vue/commit/a948846400c37fca0fa3ed673b1c4684fc6f69e1))
- component destroy handling on parent destroy
  ([#5749](https://github.com/bootstrap-vue/bootstrap-vue/issues/5749))
  ([e67d341](https://github.com/bootstrap-vue/bootstrap-vue/commit/e67d34190358cb5e9d3e6d45ec74f045bf20caef))
- don't display BootstrapVue warning messages when in production
  ([bf8966f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf8966f6de725bf2828ca4609056c27dd4a96399))
- don't display warning messages when in production (closes
  [#5598](https://github.com/bootstrap-vue/bootstrap-vue/issues/5598))
  ([#5763](https://github.com/bootstrap-vue/bootstrap-vue/issues/5763))
  ([4b5d916](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b5d9162b8a6531c0ada66f646498b0ba40a0e9b))
- environment detection based on `userAgent`
  ([#6226](https://github.com/bootstrap-vue/bootstrap-vue/issues/6226))
  ([cdfd16c](https://github.com/bootstrap-vue/bootstrap-vue/commit/cdfd16c32296072e49596a8acf722c77709f1b93))
- replace sass division with multiplication
  ([#6834](https://github.com/bootstrap-vue/bootstrap-vue/issues/6834))
  ([dd051e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd051e93cbb2ce41d3060eda2b5a82ce28fe183c))
- update refs inside v-for to work for @vue/compat
  ([ae4bac8](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae4bac8a4327a1f293afbcf571e84ed1de4497f8))
- user supplied prop function detection (closes
  [#6112](https://github.com/bootstrap-vue/bootstrap-vue/issues/6112))
  ([#6113](https://github.com/bootstrap-vue/bootstrap-vue/issues/6113))
  ([1d85839](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d85839fa76c88f1a411a81945d03a4c895b3f4f))
- **ssr:** avoid tree missmatches by either using `domProps` or `children` (closes
  [#5453](https://github.com/bootstrap-vue/bootstrap-vue/issues/5453),
  [#5557](https://github.com/bootstrap-vue/bootstrap-vue/issues/5557))
  ([#5723](https://github.com/bootstrap-vue/bootstrap-vue/issues/5723))
  ([5e8dad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e8dad84c094ff1f7810f69293418b81e676af26))
- **table:** use original value for fallback when number parsing fails in `defaultSortCompare()`
  ([c375ce9](https://github.com/bootstrap-vue/bootstrap-vue/commit/c375ce9093ed91060b4ab199ad771dd667a68589))
- **v-b-toggle:** handle component updates on click listeners
  ([#5690](https://github.com/bootstrap-vue/bootstrap-vue/issues/5690))
  ([156b1d6](https://github.com/bootstrap-vue/bootstrap-vue/commit/156b1d6a3a1ebb6548ea0dbfac346d61a92f6ed9))
- ensure all intervals/timeouts/observers are cleared when component is destroyed
  ([#5362](https://github.com/bootstrap-vue/bootstrap-vue/issues/5362))
  ([064cdf4](https://github.com/bootstrap-vue/bootstrap-vue/commit/064cdf4f7e7c6b779c1bd689a6d300efdf81bc0d))
- properly handle HTML props render order (closes
  [#5363](https://github.com/bootstrap-vue/bootstrap-vue/issues/5363))
  ([#5365](https://github.com/bootstrap-vue/bootstrap-vue/issues/5365))
  ([844ecda](https://github.com/bootstrap-vue/bootstrap-vue/commit/844ecda654a2db50d9b84c193f1ab031e291d024))
- properly handle special characters in user-provided IDs (closes
  [#4927](https://github.com/bootstrap-vue/bootstrap-vue/issues/4927),
  [#5561](https://github.com/bootstrap-vue/bootstrap-vue/issues/5561))
  ([#5564](https://github.com/bootstrap-vue/bootstrap-vue/issues/5564))
  ([1fabd68](https://github.com/bootstrap-vue/bootstrap-vue/commit/1fabd68bb44b28a9127810f35bd07e1fdf3d12ec))
- user supplied prop function detection
  ([#6070](https://github.com/bootstrap-vue/bootstrap-vue/issues/6070))
  ([cea6051](https://github.com/bootstrap-vue/bootstrap-vue/commit/cea6051efc901325d63c22f65381242bd6e774e7))
- **b-alert:** memory leak by using the correct method to clear the countdown timeout
  ([#5158](https://github.com/bootstrap-vue/bootstrap-vue/issues/5158))
  ([7a7f33d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a7f33d74f906e5feecf2bf177636c7f85bc4537))
- **b-avatar:** fix button type font size inheritance
  ([#5177](https://github.com/bootstrap-vue/bootstrap-vue/issues/5177))
  ([441ebdc](https://github.com/bootstrap-vue/bootstrap-vue/commit/441ebdc8a262c6c6ed494ddc6a6c0c06604045ef))
- **b-avatar:** remove default padding when in button mode (fixes
  [#5073](https://github.com/bootstrap-vue/bootstrap-vue/issues/5073))
  ([#5076](https://github.com/bootstrap-vue/bootstrap-vue/issues/5076))
  ([26377b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/26377b3479f323baa2d702fab7f5200949ed680d))
- **b-avatar:** remove duplicate button variant class
  ([#5056](https://github.com/bootstrap-vue/bootstrap-vue/issues/5056))
  ([9f78f32](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f78f32d964b187f35a1feffb7aa4bc264587923))
- **b-avatar:** set `align-items: center` for default slot content (fixes:
  [#5205](https://github.com/bootstrap-vue/bootstrap-vue/issues/5205))
  ([#5207](https://github.com/bootstrap-vue/bootstrap-vue/issues/5207))
  ([c4981fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4981fd098253840a37e731331de65b0e732fc79))
- **b-button:** when `href` is "#" add `role=button` and appropriate keydown handlers for A11Y
  ([#4768](https://github.com/bootstrap-vue/bootstrap-vue/issues/4768))
  ([087a128](https://github.com/bootstrap-vue/bootstrap-vue/commit/087a1283977061c44d5b059c203f13d2326dabae))
- **b-calendar:** use `Intl.NumberFormat` for formatting the number in the date buttons (closes
  [#5171](https://github.com/bootstrap-vue/bootstrap-vue/issues/5171))
  ([#5179](https://github.com/bootstrap-vue/bootstrap-vue/issues/5179))
  ([cbf2cd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbf2cd007cce81a5f664fa649b08af6735fe16e4))
- **b-calendar, b-form-datepicker:** handle keyboard navigation when selected date is out of range
  (fixes [#5057](https://github.com/bootstrap-vue/bootstrap-vue/issues/5057))
  ([#5108](https://github.com/bootstrap-vue/bootstrap-vue/issues/5108))
  ([6ed09f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/6ed09f40ae1594c7ad96dedc8c3d7c2a54d4d9c7))
- **b-calendar, b-form-datepicker:** minor adjustments to styling and example updates
  ([#5211](https://github.com/bootstrap-vue/bootstrap-vue/issues/5211))
  ([f0d8ffe](https://github.com/bootstrap-vue/bootstrap-vue/commit/f0d8ffe4253079939008108fe86529a2f69553f1))
- **b-card:** handle `header-html` and `footer-html` props correctly (fixes
  [#5038](https://github.com/bootstrap-vue/bootstrap-vue/issues/5038))
  ([#5039](https://github.com/bootstrap-vue/bootstrap-vue/issues/5039))
  ([f378aef](https://github.com/bootstrap-vue/bootstrap-vue/commit/f378aeffdebdc7922f6ad4c5d513642dfb93cf1d))
- **b-collapse:** fix memory leak from `$root` listener (fixes
  [#3607](https://github.com/bootstrap-vue/bootstrap-vue/issues/3607))
  ([#3608](https://github.com/bootstrap-vue/bootstrap-vue/issues/3608))
  ([10cb3a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/10cb3a9bda50668497e47172f7e17796f0144409))
- **b-dropdown:** close when clicking on nested elements inside items with `to` prop
  ([#3476](https://github.com/bootstrap-vue/bootstrap-vue/issues/3476))
  ([8ec2eb1](https://github.com/bootstrap-vue/bootstrap-vue/commit/8ec2eb12d67f4b30f45f62b9a886ea202ae82cf3))
- **b-dropdown:** delay show of dropdown when calling `show()` (closes
  [#3366](https://github.com/bootstrap-vue/bootstrap-vue/issues/3366))
  ([#3367](https://github.com/bootstrap-vue/bootstrap-vue/issues/3367))
  ([1604022](https://github.com/bootstrap-vue/bootstrap-vue/commit/1604022f9866456e9da3c627e3613f56cca1f700))
- **b-dropdown:** focus-in handling for Safari and Firefox on macOS/iOS (closes
  [#4328](https://github.com/bootstrap-vue/bootstrap-vue/issues/4328))
  ([#4426](https://github.com/bootstrap-vue/bootstrap-vue/issues/4426))
  ([2eab55b](https://github.com/bootstrap-vue/bootstrap-vue/commit/2eab55b4672a35a487b30f0f64c63b887b361473))
- **b-dropdown:** handle issue with touch devices on MacOS using Safari/Firefox (Fixes
  [#4328](https://github.com/bootstrap-vue/bootstrap-vue/issues/4328),
  [#4344](https://github.com/bootstrap-vue/bootstrap-vue/issues/4344))
  ([#4329](https://github.com/bootstrap-vue/bootstrap-vue/issues/4329))
  ([2779a0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2779a0aeeebe0797bb38f3f17c83fb463ee41624))
- **b-dropdown-\*:** ensure class bindings are placed on root element for all dropdown
  sub-components (closes [#4022](https://github.com/bootstrap-vue/bootstrap-vue/issues/4022))
  ([#4024](https://github.com/bootstrap-vue/bootstrap-vue/issues/4024))
  ([81efb89](https://github.com/bootstrap-vue/bootstrap-vue/commit/81efb8981d38ffd3d154c4eedbfdea550676c000))
- **b-dropdown-form:** fix SCSS styling when placed in a nav dropdown (fixes
  [#4220](https://github.com/bootstrap-vue/bootstrap-vue/issues/4220))
  ([#4223](https://github.com/bootstrap-vue/bootstrap-vue/issues/4223))
  ([b852bba](https://github.com/bootstrap-vue/bootstrap-vue/commit/b852bba99c866f977af0b330167a9d49341392b4))
- **b-form-datepicker:** make datepicker respect `no-highlight-today` prop
  ([#5159](https://github.com/bootstrap-vue/bootstrap-vue/issues/5159))
  ([c4ead33](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4ead3302b176e4a90fbfcfe6380de0edc22640f))
- **b-form-datepicker:** menu focus handling for Firefox and Safari on MacOS (closes
  [#4814](https://github.com/bootstrap-vue/bootstrap-vue/issues/4814))
  ([#4824](https://github.com/bootstrap-vue/bootstrap-vue/issues/4824))
  ([09fa920](https://github.com/bootstrap-vue/bootstrap-vue/commit/09fa920e4a904c6340c60586b40451dce94efc44))
- **b-form-datepicker, b-form-timepicker:** adjust scss to support input-groups
  ([#5231](https://github.com/bootstrap-vue/bootstrap-vue/issues/5231))
  ([7b1adc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7b1adc460f11c2ee54466fe0d204579f3f6f1bd2))
- **b-form-datepicker, b-form-timepicker:** fix menu padding in button only mode (fixes
  [#5251](https://github.com/bootstrap-vue/bootstrap-vue/issues/5251))
  ([#5252](https://github.com/bootstrap-vue/bootstrap-vue/issues/5252))
  ([d57a643](https://github.com/bootstrap-vue/bootstrap-vue/commit/d57a643f0c6b5e805a42a3387fb0db4443bfc01f))
- **b-form-datepicker, b-form-timepicker:** prevent duplicate validation icons (fixes
  [#5237](https://github.com/bootstrap-vue/bootstrap-vue/issues/5237))
  ([#5238](https://github.com/bootstrap-vue/bootstrap-vue/issues/5238))
  ([6354e6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/6354e6eb90b93e668c2794b3b4c2117a7cfc0ab0))
- **b-form-file:** fix prop type checking for `value` prop
  ([#4168](https://github.com/bootstrap-vue/bootstrap-vue/issues/4168))
  ([a8e2e56](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8e2e566f34fa40614292f6192d8b322a2ed2877))
- **b-form-file:** fix value prop validation when using directory mode (fixes
  [#4912](https://github.com/bootstrap-vue/bootstrap-vue/issues/4912))
  ([#4913](https://github.com/bootstrap-vue/bootstrap-vue/issues/4913))
  ([498a262](https://github.com/bootstrap-vue/bootstrap-vue/commit/498a26219571bb6108aaa7134dc25c8e1ff6c98f))
- **b-form-file:** make sure to catch all errors when resetting the input
  ([#4936](https://github.com/bootstrap-vue/bootstrap-vue/issues/4936))
  ([682bc46](https://github.com/bootstrap-vue/bootstrap-vue/commit/682bc46028cacfdb570fe416a051160ee9789fe2))
- **b-form-input, b-form-textarea:** handle change event for all mobile device keyboards (closes
  [#4724](https://github.com/bootstrap-vue/bootstrap-vue/issues/4724))
  ([#4739](https://github.com/bootstrap-vue/bootstrap-vue/issues/4739))
  ([166a932](https://github.com/bootstrap-vue/bootstrap-vue/commit/166a932fb11fa552714aba7df67992e1265b9047))
- **b-form-input, b-form-textarea:** properly handle out-of-sync values (closes
  [#4695](https://github.com/bootstrap-vue/bootstrap-vue/issues/4695))
  ([#4701](https://github.com/bootstrap-vue/bootstrap-vue/issues/4701))
  ([954176d](https://github.com/bootstrap-vue/bootstrap-vue/commit/954176d733dccdd074f5b6cb31c4041081a3b206))
- **b-form-spinbutton:** prevent buttons from re-ordering when parent element is RTL
  ([#4802](https://github.com/bootstrap-vue/bootstrap-vue/issues/4802))
  ([ae2cce9](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae2cce9d593bd310b3d2256ade41df0243447970))
- **b-form-spinbutton:** prevent double increment/decrement on mobile (fixes
  [#4838](https://github.com/bootstrap-vue/bootstrap-vue/issues/4838))
  ([#4842](https://github.com/bootstrap-vue/bootstrap-vue/issues/4842))
  ([9c2c700](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c2c700a91d7a6e57572f579f68996eaceda5c00))
- **b-form-spinbutton:** respect step value for initial decrement when `wrap` enabled (closes
  [#4884](https://github.com/bootstrap-vue/bootstrap-vue/issues/4884))
  ([#4885](https://github.com/bootstrap-vue/bootstrap-vue/issues/4885))
  ([28e7245](https://github.com/bootstrap-vue/bootstrap-vue/commit/28e724536be4762382328648f203bd46d8f52fdc))
- **b-form-tags:** improve accessibility for screen reader users
  ([#4775](https://github.com/bootstrap-vue/bootstrap-vue/issues/4775))
  ([2328630](https://github.com/bootstrap-vue/bootstrap-vue/commit/2328630542defc395912165a964a95107f8a4ba9))
- **b-form-textarea:** handle initial auto-height when in modal, tabs, or other component with
  transition or which uses `v-show` (fixes
  [#3936](https://github.com/bootstrap-vue/bootstrap-vue/issues/3936),
  [#3702](https://github.com/bootstrap-vue/bootstrap-vue/issues/3702))
  ([#3937](https://github.com/bootstrap-vue/bootstrap-vue/issues/3937))
  ([be3ac62](https://github.com/bootstrap-vue/bootstrap-vue/commit/be3ac62b81d43c434d03bd833db22e99bd1da3f4))
- **b-img-lazy:** better initial inView check + new show prop (fixes
  [#1755](https://github.com/bootstrap-vue/bootstrap-vue/issues/1755))
  ([#2382](https://github.com/bootstrap-vue/bootstrap-vue/issues/2382))
  ([2416bad](https://github.com/bootstrap-vue/bootstrap-vue/commit/2416bad6a57a02f4144eb131412370410ff2597d))
- **b-input-group:** fix kebab-case prop names for `prepend-html` and `append-html` (fixes
  [#3565](https://github.com/bootstrap-vue/bootstrap-vue/issues/3565))
  ([#3567](https://github.com/bootstrap-vue/bootstrap-vue/issues/3567))
  ([e48d3dc](https://github.com/bootstrap-vue/bootstrap-vue/commit/e48d3dc350c4767df9d53e3e2173b6bf125523dd))
- **b-link:** default new `<nuxt-link>` prop `prefetch` to `null` for true tri-state prop
  ([#5357](https://github.com/bootstrap-vue/bootstrap-vue/issues/5357))
  ([3f41c91](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f41c91961c29988ba13ca11f4dc8f81810e761f))
- **b-link:** don't render `target` or `rel` attrs when `router-tag` other than `a` or `area`
  provided ([#5107](https://github.com/bootstrap-vue/bootstrap-vue/issues/5107))
  ([33c6cef](https://github.com/bootstrap-vue/bootstrap-vue/commit/33c6cefc2f46ab8110e39f110d984f230d525c86))
- **b-link:** only add the `nativeOn` property to componentData when rendering a router link
  ([#3976](https://github.com/bootstrap-vue/bootstrap-vue/issues/3976))
  ([62fb0b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/62fb0b68aa059d5c827072f569026222eaa9ad4b))
- **b-media:** fix vertical align class when top or bottom selected (fixes
  [#4052](https://github.com/bootstrap-vue/bootstrap-vue/issues/4052))
  ([#4055](https://github.com/bootstrap-vue/bootstrap-vue/issues/4055))
  ([9ccfe4c](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ccfe4ca61914d23bd1da0e33550e6a1af83bb18))
- **b-modal:** additional fixes for show transition behaviour (closes
  [#4761](https://github.com/bootstrap-vue/bootstrap-vue/issues/4761))
  ([#4777](https://github.com/bootstrap-vue/bootstrap-vue/issues/4777))
  ([1113c6f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1113c6f951d86b7e6e6ba2161f935d2b6e0b5ce8))
- **b-modal:** ensure header is read for accessibility with JAWS (closes
  [#3712](https://github.com/bootstrap-vue/bootstrap-vue/issues/3712))
  ([#3713](https://github.com/bootstrap-vue/bootstrap-vue/issues/3713))
  ([6a9d0ce](https://github.com/bootstrap-vue/bootstrap-vue/commit/6a9d0ceb363a40ff9e23d0aaf6a9185a3384f268))
- **b-modal:** ensure non-prop attributes are transferred to the modal outer wrapper `div` (closes
  [#3896](https://github.com/bootstrap-vue/bootstrap-vue/issues/3896))
  ([#3921](https://github.com/bootstrap-vue/bootstrap-vue/issues/3921))
  ([8bf3a55](https://github.com/bootstrap-vue/bootstrap-vue/commit/8bf3a55a01811671fee223011dd90903faf1b79b))
- **b-modal:** prevent page scroll when tabbing to bottom of modal + better tab containment in
  enforceFocus (closes [#3842](https://github.com/bootstrap-vue/bootstrap-vue/issues/3842))
  ([#3846](https://github.com/bootstrap-vue/bootstrap-vue/issues/3846))
  ([ed99f9c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed99f9c67793a3a8895812a514717b9c10d9012e))
- **b-modal:** remove `role="document"` from `.modal-content`
  ([#5345](https://github.com/bootstrap-vue/bootstrap-vue/issues/5345))
  ([0c2b406](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c2b406e8dadc274e8433d3a4c414e799d0fa228))
- **b-modal:** transition timing
  ([#4766](https://github.com/bootstrap-vue/bootstrap-vue/issues/4766))
  ([968c957](https://github.com/bootstrap-vue/bootstrap-vue/commit/968c95758e45610a8c002507790c79d87d8fe956))
- **b-nav-form, b-nav-text:** ensure these sub-components have `<li>` as root element for
  accessibility ([#4100](https://github.com/bootstrap-vue/bootstrap-vue/issues/4100))
  ([6774800](https://github.com/bootstrap-vue/bootstrap-vue/commit/677480035f34ee735d0aa3ac98323aea2cbad732))
- **b-nav-item-dropdown:** clicking toggle a second time should close menu (closes
  [#3707](https://github.com/bootstrap-vue/bootstrap-vue/issues/3707))
  ([#3706](https://github.com/bootstrap-vue/bootstrap-vue/issues/3706))
  ([629951e](https://github.com/bootstrap-vue/bootstrap-vue/commit/629951e4763dcdc625d31484495e17f4a9e39f68))
- **b-pagination-nav:** attempt to auto-detect current page when `pages` array or `number of pages`
  changes (closes [#3443](https://github.com/bootstrap-vue/bootstrap-vue/issues/3443))
  ([#3444](https://github.com/bootstrap-vue/bootstrap-vue/issues/3444))
  ([88b95c6](https://github.com/bootstrap-vue/bootstrap-vue/commit/88b95c6d0e97372ad9a2d59b06df1975b5aad338))
- **b-pagination, b-pagination-nav:** add UP/DOWN keyboard navigation support for JAWS (fixes
  [#4322](https://github.com/bootstrap-vue/bootstrap-vue/issues/4322))
  ([#4325](https://github.com/bootstrap-vue/bootstrap-vue/issues/4325))
  ([c686088](https://github.com/bootstrap-vue/bootstrap-vue/commit/c686088f939328eb30d0bf089d077584e2988b70))
- **b-popover, b-tooltip:** ensure `boundary-padding` is passed to popper instance (fixes
  [#4131](https://github.com/bootstrap-vue/bootstrap-vue/issues/4131))
  ([#4133](https://github.com/bootstrap-vue/bootstrap-vue/issues/4133))
  ([a54a647](https://github.com/bootstrap-vue/bootstrap-vue/commit/a54a647d64dc1251c2667f2179f6e8d648dccd40))
- **b-table:** add clearfix to table cells in case label wraps in stacked mode
  ([#3652](https://github.com/bootstrap-vue/bootstrap-vue/issues/3652))
  ([3115dae](https://github.com/bootstrap-vue/bootstrap-vue/commit/3115daeedf334479b79623a58bc0d9a2bcc7f242))
- **b-table:** ensure `ctx.sortBy` is an empty string when no sorting
  ([#3534](https://github.com/bootstrap-vue/bootstrap-vue/issues/3534))
  ([d451687](https://github.com/bootstrap-vue/bootstrap-vue/commit/d451687ffcb8bfdbf90ed7d2a79bcf1c1e18b23a))
- **b-table:** handle filter as an object when using providers and prevent duplicate provider calls
  on mount (fixes [#4065](https://github.com/bootstrap-vue/bootstrap-vue/issues/4065))
  ([#4068](https://github.com/bootstrap-vue/bootstrap-vue/issues/4068))
  ([9ddd115](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ddd1151a316b47d26ca91319f0f9eba630c5538))
- **b-table:** IE11 edge case where custom inputs were not clickable in clickable/sortable cells
  (fixes [#3693](https://github.com/bootstrap-vue/bootstrap-vue/issues/3693))
  ([#3697](https://github.com/bootstrap-vue/bootstrap-vue/issues/3697))
  ([fce8b5b](https://github.com/bootstrap-vue/bootstrap-vue/commit/fce8b5bc78e47462f5831584b0bfde9f2329293d))
- **b-table:** minor code optimizations to filter debouncing
  ([#4167](https://github.com/bootstrap-vue/bootstrap-vue/issues/4167))
  ([018eef1](https://github.com/bootstrap-vue/bootstrap-vue/commit/018eef139ee9a49dd08a5da01157412adccb4486))
- **b-table:** remove extra slashes in mixins imports
  ([#4087](https://github.com/bootstrap-vue/bootstrap-vue/issues/4087))
  ([77f5be1](https://github.com/bootstrap-vue/bootstrap-vue/commit/77f5be15c08f4ce73b015592b55ee01239d7eaa1))
- **b-table-lite:** add checks to helper mixins for existence of stopIfBusy (closes
  [#3518](https://github.com/bootstrap-vue/bootstrap-vue/issues/3518))
  ([#3520](https://github.com/bootstrap-vue/bootstrap-vue/issues/3520))
  ([285cf94](https://github.com/bootstrap-vue/bootstrap-vue/commit/285cf94608c5be7c9a4f5a3d89e9970734fafb03))
- **b-table, b-table-lite:** handle edge case where field slot returns no vNodes (fixes
  [#3919](https://github.com/bootstrap-vue/bootstrap-vue/issues/3919))
  ([#3920](https://github.com/bootstrap-vue/bootstrap-vue/issues/3920))
  ([a392059](https://github.com/bootstrap-vue/bootstrap-vue/commit/a39205940f6ccf777e92c54d680e9ed0008abd77))
- **b-table, b-table-lite:** handle edge case with row events when table is removed from dom.
  instantiate row event handlers only when listeners are registered (fixes
  [#4384](https://github.com/bootstrap-vue/bootstrap-vue/issues/4384))
  ([#4388](https://github.com/bootstrap-vue/bootstrap-vue/issues/4388))
  ([9a81cd4](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a81cd414a2c534b96de0d82c3d00d94651e5a7b))
- **b-table, b-table-lite:** render header when not always stacked mode (fixes
  [#3886](https://github.com/bootstrap-vue/bootstrap-vue/issues/3886))
  ([#3887](https://github.com/bootstrap-vue/bootstrap-vue/issues/3887))
  ([2302b31](https://github.com/bootstrap-vue/bootstrap-vue/commit/2302b31d63290abcf72b52d3ddb5d6a6767ec356))
- **b-table, b-table-lite:** use `:key` for row details based on the primary key value if available
  ([#4025](https://github.com/bootstrap-vue/bootstrap-vue/issues/4025))
  ([c7cb16f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7cb16fee8d3a4d884490f4cb41298c597b0bfa5))
- **b-table, b-table-lite, b-table-simple:** handle header variant for sticky columns (fixes
  [#5278](https://github.com/bootstrap-vue/bootstrap-vue/issues/5278))
  ([#5279](https://github.com/bootstrap-vue/bootstrap-vue/issues/5279))
  ([53e309e](https://github.com/bootstrap-vue/bootstrap-vue/commit/53e309e947b4710fcf8d989cc9ef0f31c58487ae))
- **b-table, b-table-lite, b-tbody:** fix delegated event handlers when transition + minor
  adjustment to row `key` generation (fixes
  [#4370](https://github.com/bootstrap-vue/bootstrap-vue/issues/4370))
  ([#4372](https://github.com/bootstrap-vue/bootstrap-vue/issues/4372))
  ([030a3d8](https://github.com/bootstrap-vue/bootstrap-vue/commit/030a3d8c9a89b253c0bb8dbf9be98151bd020176))
- **b-tabs:** allow space to trigger tab activation when `no-key-nav` is enabled (fixes
  [#4323](https://github.com/bootstrap-vue/bootstrap-vue/issues/4323))
  ([#4326](https://github.com/bootstrap-vue/bootstrap-vue/issues/4326))
  ([731365b](https://github.com/bootstrap-vue/bootstrap-vue/commit/731365b27f290fd2266709865b51307edd04e54e))
- **b-tabs:** improve child b-tab detection routine (closes
  [#3260](https://github.com/bootstrap-vue/bootstrap-vue/issues/3260))
  ([#3442](https://github.com/bootstrap-vue/bootstrap-vue/issues/3442))
  ([4a54e8d](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a54e8dcb941590b28ebe7bf40805cc1ce5f1f5e))
- **b-toast:** fix ensureToaster method call when toaster name changes
  ([#4468](https://github.com/bootstrap-vue/bootstrap-vue/issues/4468))
  ([744bb7a](https://github.com/bootstrap-vue/bootstrap-vue/commit/744bb7a77092a04184af31bf285e432110e1ab44))
- **b-tooltip:** fix arrow margin
  ([#4727](https://github.com/bootstrap-vue/bootstrap-vue/issues/4727))
  ([865a655](https://github.com/bootstrap-vue/bootstrap-vue/commit/865a6557fbf49115c05326f9a96c4f9fdf135e96))
- **b-tooltip/b-popover:** add `SVGElement` as acceptable prop type (closes
  [#4173](https://github.com/bootstrap-vue/bootstrap-vue/issues/4173))
  ([#4174](https://github.com/bootstrap-vue/bootstrap-vue/issues/4174))
  ([fab7fea](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab7fea0a69b36b95f0c9606122140fe771e8ac8))
- **breadcrumb-item:** correctly set domProps when no children provided
  ([523e3a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/523e3a2e6bc997d83e2379de27e2504a73de0dfe))
- **breadcrumb-item:** Fix `to` prop handling
  ([#2578](https://github.com/bootstrap-vue/bootstrap-vue/issues/2578))
  ([fba9df3](https://github.com/bootstrap-vue/bootstrap-vue/commit/fba9df350789e7bc58dccd6d795a65465dd66713))
- **breadcrumb-link:** correctly use html/text
  ([8b086a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b086a99a5878eabdc55ecae694f72b310287517))
- **build:** don't include babel runtime
  ([#2590](https://github.com/bootstrap-vue/bootstrap-vue/issues/2590))
  ([20828fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/20828fab7acf5d6fc60b699e5eb2529f8992dbe4))
- **card:** Drop `img-fluid` property
  ([#2548](https://github.com/bootstrap-vue/bootstrap-vue/issues/2548))
  ([cfc685f](https://github.com/bootstrap-vue/bootstrap-vue/commit/cfc685fab151899b47775b83a54815b34cbad635))
- **carousel:** disable the next/prev controls when the carousel is sliding (closes
  [#4210](https://github.com/bootstrap-vue/bootstrap-vue/issues/4210))
  ([#4212](https://github.com/bootstrap-vue/bootstrap-vue/issues/4212))
  ([64d556d](https://github.com/bootstrap-vue/bootstrap-vue/commit/64d556d452ed8feefdb56a7f40ceb9a08b5e617f))
- **carousel:** fix touchmove handler to re-enable swipe gestures
  ([#2844](https://github.com/bootstrap-vue/bootstrap-vue/issues/2844))
  ([a067f8c](https://github.com/bootstrap-vue/bootstrap-vue/commit/a067f8c03c511d3886a17576cab47ae59a3733af))
- **carousel:** reset `touchDeltaX` to prevent click transformed in swipe
  ([#3734](https://github.com/bootstrap-vue/bootstrap-vue/issues/3734))
  ([0e54839](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e548398e530687a6ec9ec35c89e97ed4cd913c6))
- **carousel:** setInterval memory leak when no slides provided
  ([#2399](https://github.com/bootstrap-vue/bootstrap-vue/issues/2399))
  ([ac2a708](https://github.com/bootstrap-vue/bootstrap-vue/commit/ac2a708194fdec9afca971cae1a8145ca8f591e6))
- **carousel-slide:** do not render `carousel-caption` wrapper if no content
  ([#3662](https://github.com/bootstrap-vue/bootstrap-vue/issues/3662))
  ([615a719](https://github.com/bootstrap-vue/bootstrap-vue/commit/615a719d8f7754be5cd1940a66fdf8bca469d6e8))
- **changelog:** correct typos ([#3950](https://github.com/bootstrap-vue/bootstrap-vue/issues/3950))
  ([2efd38a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2efd38ac3022a1e4a8503513b1094dd57bfdeb3c))
- **ci:** remove test-beta
  ([1076f3f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1076f3f392d5b22abce67f80783c94b09b69c036))
- **ci:** remove test-beta
  ([0fec992](https://github.com/bootstrap-vue/bootstrap-vue/commit/0fec9920a00ebb4aab0c4ae5df1662d36cb85cd5))
- **ci:** test on current vue
  ([e3282bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3282bdff9913e12f3292629002af878ffa2a321))
- **collapse:** don't make `id` prop required
  ([#4109](https://github.com/bootstrap-vue/bootstrap-vue/issues/4109))
  ([4f935ce](https://github.com/bootstrap-vue/bootstrap-vue/commit/4f935ced9371aac7e18bb65c591791ec7f76430c))
- **collapse/toggle:** persist toggle state on element and prevent multiple state emits (closes
  [#2923](https://github.com/bootstrap-vue/bootstrap-vue/issues/2923))
  ([#2924](https://github.com/bootstrap-vue/bootstrap-vue/issues/2924))
  ([6f899fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f899fcff1550e2109002ee6b3121fbd72c12a60))
- **config:** avoid using `of` operator (closes
  [#3525](https://github.com/bootstrap-vue/bootstrap-vue/issues/3525))
  ([#3526](https://github.com/bootstrap-vue/bootstrap-vue/issues/3526))
  ([17ec8d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/17ec8d0d2d9e280a4de9aaa25ec4385fcbb31a13))
- **deps:** Add @babel/runtime to devDependencies
  ([#2569](https://github.com/bootstrap-vue/bootstrap-vue/issues/2569))
  ([83a253b](https://github.com/bootstrap-vue/bootstrap-vue/commit/83a253b2f92a1d52a8ead6fb2064c08bf7d864c1))
- **docs:** add back missing leading slash to search urls
  ([#2947](https://github.com/bootstrap-vue/bootstrap-vue/issues/2947))
  ([fff8795](https://github.com/bootstrap-vue/bootstrap-vue/commit/fff8795aca5e574c3deab8ce5f09cc7571822075))
- **docs:** always use array format for `<b-form-select>` options
  ([#4841](https://github.com/bootstrap-vue/bootstrap-vue/issues/4841))
  ([6308a0f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6308a0f5c07aee3267c21bc5ca60746b7fab7cf0))
- **docs:** broken links and sync layout docs with Bootstrap's
  ([#4261](https://github.com/bootstrap-vue/bootstrap-vue/issues/4261))
  ([c7bc62c](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7bc62cb22e0b6d0d0363e3170890c497a1a8d36))
- **docs:** broken Twitter link
  ([#3912](https://github.com/bootstrap-vue/bootstrap-vue/issues/3912))
  ([611a507](https://github.com/bootstrap-vue/bootstrap-vue/commit/611a5072a5ae87ff56da67a0d39286549233cd4a))
- **docs:** change [@include](https://github.com/include) to [@import](https://github.com/import) in
  the Nuxt plugin module section
  ([4fad60a](https://github.com/bootstrap-vue/bootstrap-vue/commit/4fad60a200d5bbf24b2990fdc7ee9ac10b08f6a8))
- **docs:** correct and validate component meta information (closes
  [#2665](https://github.com/bootstrap-vue/bootstrap-vue/issues/2665))
  ([#2650](https://github.com/bootstrap-vue/bootstrap-vue/issues/2650))
  ([29147ca](https://github.com/bootstrap-vue/bootstrap-vue/commit/29147caba02b99ed32ba8f078b62bab063ea6395))
- **docs:** correct formatting of <b-modal> `ok-only` prop
  ([#4517](https://github.com/bootstrap-vue/bootstrap-vue/issues/4517))
  ([988653e](https://github.com/bootstrap-vue/bootstrap-vue/commit/988653ef626ca53535900634a62ccba289ac51a3))
- **docs:** correct modal directive name
  ([#3335](https://github.com/bootstrap-vue/bootstrap-vue/issues/3335))
  ([d4dcc35](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4dcc35718ed9f98171e6abc37d3b7318ddcb525))
- **docs:** correct polyfilling suggestions
  ([#3605](https://github.com/bootstrap-vue/bootstrap-vue/issues/3605))
  ([35806e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/35806e763bdd7f5689934b5db605668b6c3c76a5))
- **docs:** correct spelling error in `b-form-file` property description
  ([#4551](https://github.com/bootstrap-vue/bootstrap-vue/issues/4551))
  ([2f9b14a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2f9b14a105fa12e68299c101cd794023ed79eb7b))
- **docs:** correct typo on intro page
  ([#3827](https://github.com/bootstrap-vue/bootstrap-vue/issues/3827))
  ([986f5c0](https://github.com/bootstrap-vue/bootstrap-vue/commit/986f5c041e701e96f1d573aed793b94a14d1e884))
- **docs:** correct typos ([#2592](https://github.com/bootstrap-vue/bootstrap-vue/issues/2592))
  ([9883f8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/9883f8f9a18b72d541c40b67847aaac09501833e))
- **docs:** Correct typos in carousel docs
  ([#2585](https://github.com/bootstrap-vue/bootstrap-vue/issues/2585))
  ([87a721f](https://github.com/bootstrap-vue/bootstrap-vue/commit/87a721ff61b98a55d14ea8ef3c6c7b3ad5c3fb51))
- **docs:** create local marked-loader.js
  ([#2380](https://github.com/bootstrap-vue/bootstrap-vue/issues/2380))
  ([06cfb47](https://github.com/bootstrap-vue/bootstrap-vue/commit/06cfb47552fdacbdb05ee2e358aec1f126b5163a))
- **docs:** drop self-closing tags + build system improvements (fixes
  [#2882](https://github.com/bootstrap-vue/bootstrap-vue/issues/2882))
  ([#2893](https://github.com/bootstrap-vue/bootstrap-vue/issues/2893))
  ([310c7dc](https://github.com/bootstrap-vue/bootstrap-vue/commit/310c7dc94c1dc415c7f6db3d7296b277e8368021))
- **docs:** fix broken link ([#5341](https://github.com/bootstrap-vue/bootstrap-vue/issues/5341))
  ([562be51](https://github.com/bootstrap-vue/bootstrap-vue/commit/562be515608c777db0fb1b0b35ce6836e2951fad))
- **docs:** fix broken link in form-textarea docs
  ([#2598](https://github.com/bootstrap-vue/bootstrap-vue/issues/2598))
  ([07162e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/07162e17ac0f32791905a2571c2309b37fda54f5))
- **docs:** fix broken links ([#2635](https://github.com/bootstrap-vue/bootstrap-vue/issues/2635))
  ([fa90f3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa90f3ea38ef36a37915ead17b14a84299f1242c))
- **docs:** Fix broken links. Closes
  [#2517](https://github.com/bootstrap-vue/bootstrap-vue/issues/2517)
  ([#2528](https://github.com/bootstrap-vue/bootstrap-vue/issues/2528))
  ([c4b7e1e](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4b7e1ef7e69dbb082d939de0769eabd00956a80))
- **docs:** Fix directive import paths
  ([#2570](https://github.com/bootstrap-vue/bootstrap-vue/issues/2570))
  ([2475542](https://github.com/bootstrap-vue/bootstrap-vue/commit/2475542679ea9407d42463149a35d63c4cf3d70a))
- **docs:** fix grid options table layout issue
  ([#2630](https://github.com/bootstrap-vue/bootstrap-vue/issues/2630))
  ([86a882f](https://github.com/bootstrap-vue/bootstrap-vue/commit/86a882f6951fe8e8c9a4b2758e39e27577c1c4c7))
- **docs:** fix issue with table docs page (closes
  [#2939](https://github.com/bootstrap-vue/bootstrap-vue/issues/2939))
  ([#2940](https://github.com/bootstrap-vue/bootstrap-vue/issues/2940))
  ([c6abfd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6abfd00fb8f78137d6ed7356d5ba47dc52d0fd2))
- **docs:** fix modal docs typo
  ([#2507](https://github.com/bootstrap-vue/bootstrap-vue/issues/2507))
  ([524db85](https://github.com/bootstrap-vue/bootstrap-vue/commit/524db85567fbb95fb769197d2379316cd79d894f))
- **docs:** fix typo ([#2864](https://github.com/bootstrap-vue/bootstrap-vue/issues/2864))
  ([ec6951d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec6951d8dbdd60a12ab68c216c48868590f3205f))
- **docs:** fix typo in modal ([#3413](https://github.com/bootstrap-vue/bootstrap-vue/issues/3413))
  ([510577f](https://github.com/bootstrap-vue/bootstrap-vue/commit/510577f1b6e87be8e02c51e9ef612a8d2928ec3e))
- **docs:** guarantee css load order
  ([#2274](https://github.com/bootstrap-vue/bootstrap-vue/issues/2274))
  ([8841f6b](https://github.com/bootstrap-vue/bootstrap-vue/commit/8841f6bc158ada1bc93c97cb4019ccdcfdb69039))
- **docs:** hading before margin
  ([#4029](https://github.com/bootstrap-vue/bootstrap-vue/issues/4029))
  ([4b8a8c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b8a8c71744bcfa36bc1fd65610e2e25a2c3d39b))
- **docs:** handle undocumented breaking changes in babel-standalone for IE11
  ([#4484](https://github.com/bootstrap-vue/bootstrap-vue/issues/4484))
  ([56f8bb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/56f8bb5af7fb7188da035210e8be28d7ae1c7bc1))
- **docs:** Improve wording in footer
  ([#2576](https://github.com/bootstrap-vue/bootstrap-vue/issues/2576))
  ([af7e36e](https://github.com/bootstrap-vue/bootstrap-vue/commit/af7e36e1ff3777ef147e879dc24f98ae02727ae2))
- **docs:** route generation + `b-progress-bar` label HTML support examples (closes
  [#3333](https://github.com/bootstrap-vue/bootstrap-vue/issues/3333))
  ([#3336](https://github.com/bootstrap-vue/bootstrap-vue/issues/3336))
  ([526f274](https://github.com/bootstrap-vue/bootstrap-vue/commit/526f274096327b9fe9ca1dbda0e3372dc1ab008b))
- **docs:** tabs lazy examples ([#4362](https://github.com/bootstrap-vue/bootstrap-vue/issues/4362))
  ([a858523](https://github.com/bootstrap-vue/bootstrap-vue/commit/a85852330a1dfa0cc33a424b6378e887a58b2881))
- **docs:** Update Bootstrap links to v4.3
  ([#2556](https://github.com/bootstrap-vue/bootstrap-vue/issues/2556))
  ([b5d5499](https://github.com/bootstrap-vue/bootstrap-vue/commit/b5d54994f667b7aba5a3deb6c027b79ac4a71651))
- **docs:** Update links to Bootstrap V4.2
  ([#2370](https://github.com/bootstrap-vue/bootstrap-vue/issues/2370))
  ([470a083](https://github.com/bootstrap-vue/bootstrap-vue/commit/470a0835c985fb1e0ec5665e3fbdbe68b8e17229))
- **docs:** update Vuelidate links
  ([#2841](https://github.com/bootstrap-vue/bootstrap-vue/issues/2841))
  ([84ed139](https://github.com/bootstrap-vue/bootstrap-vue/commit/84ed139aafda86b6e4b9609581882a4b93e6e1f9))
- **dom-utils:** check for `el.classList` existence (closes
  [#2713](https://github.com/bootstrap-vue/bootstrap-vue/issues/2713))
  ([#2714](https://github.com/bootstrap-vue/bootstrap-vue/issues/2714))
  ([4ff8b05](https://github.com/bootstrap-vue/bootstrap-vue/commit/4ff8b0561807bc47f6220e69118e321bc452b999))
- **dropdown:** Add back missing `click` events
  ([#2460](https://github.com/bootstrap-vue/bootstrap-vue/issues/2460))
  ([c5d858f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c5d858f0e2286070beac3c953977df41c9712935))
- **dropdown:** fix `no-caret` prop when dropleft (fixes
  [#2909](https://github.com/bootstrap-vue/bootstrap-vue/issues/2909))
  ([#2910](https://github.com/bootstrap-vue/bootstrap-vue/issues/2910))
  ([3bef981](https://github.com/bootstrap-vue/bootstrap-vue/commit/3bef9812f007ba4b575b7fd3936f0a19d3983856))
- **dropdown:** focus menu container before emitting shown event. Closes
  [#2520](https://github.com/bootstrap-vue/bootstrap-vue/issues/2520)
  ([#2527](https://github.com/bootstrap-vue/bootstrap-vue/issues/2527))
  ([1649c00](https://github.com/bootstrap-vue/bootstrap-vue/commit/1649c00f8473818967a01f33e973dae66df22f75))
- **dropdown:** focus-out handling when new focus comes from another `dropdown-toggle` (closes
  [#4113](https://github.com/bootstrap-vue/bootstrap-vue/issues/4113))
  ([#4139](https://github.com/bootstrap-vue/bootstrap-vue/issues/4139))
  ([9c37875](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c37875ea08a9cadf348fb42f78f576b1b3848d6))
- **dropdown:** Menu focusout close handling
  ([#2252](https://github.com/bootstrap-vue/bootstrap-vue/issues/2252))
  ([1853954](https://github.com/bootstrap-vue/bootstrap-vue/commit/1853954b0afefbc747f3b68f69ae45123393918b))
- **env:** check for undefined on process (closes
  [#2958](https://github.com/bootstrap-vue/bootstrap-vue/issues/2958))
  ([#2959](https://github.com/bootstrap-vue/bootstrap-vue/issues/2959))
  ([0c3a7b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c3a7b0211ac741f2be37056951bd9c5583d1821))
- **form control:** handle autofocus inside modal or when inside a transition
  ([#3386](https://github.com/bootstrap-vue/bootstrap-vue/issues/3386))
  ([c4a8edb](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4a8edb0e98ea6fbbac46c6445d31e76a7cd631f))
- **form-control:** remove interim class fixes from bootstrap 4.0.x (fixes
  [#1896](https://github.com/bootstrap-vue/bootstrap-vue/issues/1896))
  ([#2265](https://github.com/bootstrap-vue/bootstrap-vue/issues/2265))
  ([64bdf69](https://github.com/bootstrap-vue/bootstrap-vue/commit/64bdf69d3a920408ac6a304d4d13e82c8555b48b))
- **form-file:** `input` event loop on `reset()` in multiple mode
  ([#2289](https://github.com/bootstrap-vue/bootstrap-vue/issues/2289))
  ([f483c7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/f483c7bc49db84920b4ec5b45ea9e50bffe2d440))
- **form-file:** fix v-model update watcher
  ([#2695](https://github.com/bootstrap-vue/bootstrap-vue/issues/2695))
  ([abf9d6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/abf9d6e7b4feee6e773a58897f3d63b176bd9ea1))
- **form-group:** allow label alignment on label when not horizontal
  ([#2284](https://github.com/bootstrap-vue/bootstrap-vue/issues/2284))
  ([c306b18](https://github.com/bootstrap-vue/bootstrap-vue/commit/c306b185d81b54ef188744242a944af520599efb))
- **form-group:** don't render aria-labelledby on group when label-for provided (fixes
  [#2933](https://github.com/bootstrap-vue/bootstrap-vue/issues/2933))
  ([#2936](https://github.com/bootstrap-vue/bootstrap-vue/issues/2936))
  ([8058c03](https://github.com/bootstrap-vue/bootstrap-vue/commit/8058c03d04b80b503f88b47f8e86aee6d7cc58d7))
- **form-input:** Allow number as value type
  ([#2583](https://github.com/bootstrap-vue/bootstrap-vue/issues/2583))
  ([dfaf34e](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfaf34e0350b2ac9a170ad5f9a2654802c91af9b))
- **form-input:** allow number type for form-inputs via form-text mixin
  ([#2738](https://github.com/bootstrap-vue/bootstrap-vue/issues/2738))
  ([ec91788](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec9178840914ae008b14d9eabce4e8b223f9ad28))
- **form-input, form-textarea:** handle case where input has been removed from document (closes
  [#3498](https://github.com/bootstrap-vue/bootstrap-vue/issues/3498))
  ([#3501](https://github.com/bootstrap-vue/bootstrap-vue/issues/3501))
  ([9a62e44](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a62e4447aba0c2f07a700d62a0cb41f2e0c54b7))
- **form-radio/form-checkbox:** ensure required prop propagated in group mode (fixes
  [#2839](https://github.com/bootstrap-vue/bootstrap-vue/issues/2839))
  ([#2842](https://github.com/bootstrap-vue/bootstrap-vue/issues/2842))
  ([fc24589](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc24589841b77e010b84927ac435575a657928c2))
- **icons:** make icon transform props work with IE11 (closes
  [#4607](https://github.com/bootstrap-vue/bootstrap-vue/issues/4607))
  ([#4608](https://github.com/bootstrap-vue/bootstrap-vue/issues/4608))
  ([899779f](https://github.com/bootstrap-vue/bootstrap-vue/commit/899779f20015f719198a763136137eea01aa11ea))
- **link:** support handling multiple click event listeners (fixes
  [#2938](https://github.com/bootstrap-vue/bootstrap-vue/issues/2938))
  ([#2943](https://github.com/bootstrap-vue/bootstrap-vue/issues/2943))
  ([97e8ece](https://github.com/bootstrap-vue/bootstrap-vue/commit/97e8ecee5f03d4a486ca31ee9b7ef088ea537d15))
- **link:** use `active` class when manually placed into active state
  ([#2405](https://github.com/bootstrap-vue/bootstrap-vue/issues/2405))
  ([8f13ede](https://github.com/bootstrap-vue/bootstrap-vue/commit/8f13edecade085646b759bae7d3c0249fa07998a))
- **modal:** better backdrop clickout handling (Closes:
  [#2597](https://github.com/bootstrap-vue/bootstrap-vue/issues/2597))
  ([#2608](https://github.com/bootstrap-vue/bootstrap-vue/issues/2608))
  ([11c7524](https://github.com/bootstrap-vue/bootstrap-vue/commit/11c75244b907f32adb68bb7e8c7b91b91b6079ca))
- **modal:** ensure `ignoreBackdropClick` flag is cleared in `clickOutHandler`
  ([#3488](https://github.com/bootstrap-vue/bootstrap-vue/issues/3488))
  ([afb4680](https://github.com/bootstrap-vue/bootstrap-vue/commit/afb46801475181d2b26da177b0df7a19f04f12cf))
- **modal:** fix IE11 issue with copy/paste from modal into MS Word (fixes
  [#3457](https://github.com/bootstrap-vue/bootstrap-vue/issues/3457))
  ([#3489](https://github.com/bootstrap-vue/bootstrap-vue/issues/3489))
  ([16dbdf1](https://github.com/bootstrap-vue/bootstrap-vue/commit/16dbdf1c9916c59b03acbc0de51ac0099306ff97))
- **modal:** fix scroll to top issue when modal has `no-fade` set
  ([#4004](https://github.com/bootstrap-vue/bootstrap-vue/issues/4004))
  ([332b79f](https://github.com/bootstrap-vue/bootstrap-vue/commit/332b79fe8511c0f2b8401c34c80abfb0f4138920))
- **modal:** handle edge cases where modal is shown/hidden in rapid succession (fixes
  [#2236](https://github.com/bootstrap-vue/bootstrap-vue/issues/2236))
  ([#2270](https://github.com/bootstrap-vue/bootstrap-vue/issues/2270))
  ([e4a7bab](https://github.com/bootstrap-vue/bootstrap-vue/commit/e4a7babfb02632793bfcc97f6262752176b98b7b))
- **modal:** modal stacking position fix (Closes
  [#2677](https://github.com/bootstrap-vue/bootstrap-vue/issues/2677))
  ([#2681](https://github.com/bootstrap-vue/bootstrap-vue/issues/2681))
  ([ff4c4c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff4c4c983c562199895fa507ef4534943b6a6455))
- **modal:** prevent page scroll as modal opens
  ([#2963](https://github.com/bootstrap-vue/bootstrap-vue/issues/2963))
  ([3bf3622](https://github.com/bootstrap-vue/bootstrap-vue/commit/3bf3622842852ad96b2afe714403cdfa585d90a7))
- **modal:** properly render `*-html` props if provided (closes
  [#3491](https://github.com/bootstrap-vue/bootstrap-vue/issues/3491))
  ([#3492](https://github.com/bootstrap-vue/bootstrap-vue/issues/3492))
  ([c1ada9f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c1ada9f48e31905555e64d14df6d2f7fd7344991))
- **modal:** Show/Hide when once prevented
  ([#2275](https://github.com/bootstrap-vue/bootstrap-vue/issues/2275))
  ([9758dfd](https://github.com/bootstrap-vue/bootstrap-vue/commit/9758dfd365e0f66a0b9be690b3d07e703d839572))
- **modal:** use `safeId()` when comparing `id` received by hide/show handler (closes
  [#3389](https://github.com/bootstrap-vue/bootstrap-vue/issues/3389)
  ([#3394](https://github.com/bootstrap-vue/bootstrap-vue/issues/3394))
  ([fae3d25](https://github.com/bootstrap-vue/bootstrap-vue/commit/fae3d25092d9537ac1ce6f2addf27b85c422d622))
- **modal, tooltips, popovers:** remove no longer needed `nextTick` delay when updating content in
  transporter portal (closes [#4589](https://github.com/bootstrap-vue/bootstrap-vue/issues/4589))
  ([#4604](https://github.com/bootstrap-vue/bootstrap-vue/issues/4604))
  ([0e3e7e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e3e7e03370685367ac69949e596c9fff5c68163))
- **nav-item:** move listeners to link element
  ([#2755](https://github.com/bootstrap-vue/bootstrap-vue/issues/2755))
  ([40b19a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/40b19a73492a9870121908a019e0fe4cfbea3fcf))
- **nuxt:** correct transformAssetUrls value for `b-card-img` (closes
  [#3521](https://github.com/bootstrap-vue/bootstrap-vue/issues/3521))
  ([#3523](https://github.com/bootstrap-vue/bootstrap-vue/issues/3523))
  ([db8c6fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/db8c6fd4863e1ca01f86b59c14997ac3846b07a4))
- **nuxt:** use bundle for development mode (closes
  [#3397](https://github.com/bootstrap-vue/bootstrap-vue/issues/3397))
  ([#3399](https://github.com/bootstrap-vue/bootstrap-vue/issues/3399))
  ([f43097e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f43097ea27c4362dafe96fa8b52dac4eda39e271))
- **nuxt plugin:** fix typo with bootstrap vue css import properties
  ([#2618](https://github.com/bootstrap-vue/bootstrap-vue/issues/2618))
  ([8581090](https://github.com/bootstrap-vue/bootstrap-vue/commit/858109099f5e0b6c31ebed4eecec4164535492b2))
- **nuxt-module:** fix default inclusion of CSS files (closes
  [#2629](https://github.com/bootstrap-vue/bootstrap-vue/issues/2629))
  ([#2701](https://github.com/bootstrap-vue/bootstrap-vue/issues/2701))
  ([afbb650](https://github.com/bootstrap-vue/bootstrap-vue/commit/afbb650f94f036fce79458ddbc6ba3100bcd8cc8))
- **package.json:** prevent css and scss from being tree shaken out in docs
  ([#2271](https://github.com/bootstrap-vue/bootstrap-vue/issues/2271))
  ([44fd864](https://github.com/bootstrap-vue/bootstrap-vue/commit/44fd8643efec30484a6c136ac34eb1d48717f10b))
- **package.json:** flag most of bootstrap-vue as being side effect free
  ([#2268](https://github.com/bootstrap-vue/bootstrap-vue/issues/2268))
  ([5a77532](https://github.com/bootstrap-vue/bootstrap-vue/commit/5a7753284b2a7fe315e71340604f08f801668310))
- **pagination:** adjust aria label defaults. Fixes
  [#2508](https://github.com/bootstrap-vue/bootstrap-vue/issues/2508)
  ([#2529](https://github.com/bootstrap-vue/bootstrap-vue/issues/2529))
  ([9790dc2](https://github.com/bootstrap-vue/bootstrap-vue/commit/9790dc2b93bec614e76ef43f02007c2b819f66bc))
- **pagination:** avoid using domProps innerText (Addresses
  [#2744](https://github.com/bootstrap-vue/bootstrap-vue/issues/2744))
  ([#2757](https://github.com/bootstrap-vue/bootstrap-vue/issues/2757))
  ([d10f804](https://github.com/bootstrap-vue/bootstrap-vue/commit/d10f804e204078534bed0901f7bc7a33d93191bd))
- **pagination:** Component name in `package.json`
  ([#2541](https://github.com/bootstrap-vue/bootstrap-vue/issues/2541))
  ([331dc46](https://github.com/bootstrap-vue/bootstrap-vue/commit/331dc46842df94d223dfb4ea669f7ab55793d762))
- **pagination:** correct pagination props/slots/event docs and fix ellipsis slot
  ([#2699](https://github.com/bootstrap-vue/bootstrap-vue/issues/2699))
  ([25e04e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/25e04e166e28fae7c22511c5145715fa8ec05ba0))
- **pagination:** fx esxaped chars (fixes
  [#2479](https://github.com/bootstrap-vue/bootstrap-vue/issues/2479))
  ([1efd59c](https://github.com/bootstrap-vue/bootstrap-vue/commit/1efd59c844891a47afb8c4657a9caf710aae3dfc))
- **pagination:** set default total rows to 0 (fixes
  [#2498](https://github.com/bootstrap-vue/bootstrap-vue/issues/2498))
  ([#2526](https://github.com/bootstrap-vue/bootstrap-vue/issues/2526))
  ([c3227a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3227a6863a93b881af4629d5e668042c6afa250))
- **pagination pagination-nav:** v-model active class fix + keypress click fix (Fixes
  [#1985](https://github.com/bootstrap-vue/bootstrap-vue/issues/1985),
  [#1629](https://github.com/bootstrap-vue/bootstrap-vue/issues/1629))
  ([#2299](https://github.com/bootstrap-vue/bootstrap-vue/issues/2299))
  ([9afba6c](https://github.com/bootstrap-vue/bootstrap-vue/commit/9afba6c58be8a52242397f78217bd979ab90c186))
- **pagination-nav:** fix incorrect name in component package.json file (closes
  [#3458](https://github.com/bootstrap-vue/bootstrap-vue/issues/3458))
  ([#3459](https://github.com/bootstrap-vue/bootstrap-vue/issues/3459))
  ([ef252df](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef252df3da9a612dbbfd1b80aa469f5694089722))
- **pagination-nav:** fix race condition with clicking prev/next buttons
  ([#2834](https://github.com/bootstrap-vue/bootstrap-vue/issues/2834))
  ([42f14e1](https://github.com/bootstrap-vue/bootstrap-vue/commit/42f14e1d8c12534c530e4d440e825139b88547c8))
- **perf:** avoid useless re-renders of component on parent update
  ([#4825](https://github.com/bootstrap-vue/bootstrap-vue/issues/4825))
  ([2cb3fe0](https://github.com/bootstrap-vue/bootstrap-vue/commit/2cb3fe0fa822a8284e023ccf71f8e451f124016a))
- **playground:** fix undefined variable error in IE 11
  ([#3606](https://github.com/bootstrap-vue/bootstrap-vue/issues/3606))
  ([b3f7053](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3f70535fe02e295ac9d44709e045b4ab6dcf8df))
- **radio/check group:** remove redundant size class from the group container (Closes
  [#2743](https://github.com/bootstrap-vue/bootstrap-vue/issues/2743))
  ([#2761](https://github.com/bootstrap-vue/bootstrap-vue/issues/2761))
  ([0639588](https://github.com/bootstrap-vue/bootstrap-vue/commit/063958890ab8161645dede0f04fec0a19b10bb2c))
- **router-link:** remove default values for active-class and exact-active-class (Fixes
  [#2387](https://github.com/bootstrap-vue/bootstrap-vue/issues/2387))
  ([#2388](https://github.com/bootstrap-vue/bootstrap-vue/issues/2388))
  ([e3e30b8](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3e30b887af155fd36ae928705813f8b90c24519))
- **table:** adjustments to sort icon positioning SCSS (closes
  [#3563](https://github.com/bootstrap-vue/bootstrap-vue/issues/3563))
  ([#3568](https://github.com/bootstrap-vue/bootstrap-vue/issues/3568))
  ([5c572e8](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c572e8dce46d71ef5bbddea70ac484f2350e198))
- **table:** allow filtering on false values and sorting date objects. Fixes
  [#2485](https://github.com/bootstrap-vue/bootstrap-vue/issues/2485)
  ([#2544](https://github.com/bootstrap-vue/bootstrap-vue/issues/2544))
  ([79315d6](https://github.com/bootstrap-vue/bootstrap-vue/commit/79315d630614f77b829eada9a5bf577e4be0e10f))
- **table:** allow string for pagination prop types
  ([#2824](https://github.com/bootstrap-vue/bootstrap-vue/issues/2824))
  ([31d2044](https://github.com/bootstrap-vue/bootstrap-vue/commit/31d20446d5a1acb6d777c941177d660070f348f1))
- **table:** better detection of active text selection during click events
  ([#3763](https://github.com/bootstrap-vue/bootstrap-vue/issues/3763))
  ([1a9c688](https://github.com/bootstrap-vue/bootstrap-vue/commit/1a9c6883ace162878d44281ad53eceabd2c3c238))
- **table:** Clear selection when data change
  ([#2267](https://github.com/bootstrap-vue/bootstrap-vue/issues/2267))
  ([e381f38](https://github.com/bootstrap-vue/bootstrap-vue/commit/e381f38e5770bb90b77f16ae8b2c0c904dfdad56))
- **table:** disable sticky header max-height on printers
  ([#4147](https://github.com/bootstrap-vue/bootstrap-vue/issues/4147))
  ([24c62c5](https://github.com/bootstrap-vue/bootstrap-vue/commit/24c62c5b5624b68b16b3729144b16c3e5ea052c1))
- **table:** don't emit row-clicked when user is selecting text (Closes
  [#2791](https://github.com/bootstrap-vue/bootstrap-vue/issues/2791))
  ([ecf0689](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecf0689f3bde07300e57640d441e53d4f2c7ac3b))
- **table:** don't use css `grid` for stacked table SCSS - for IE11 compatibility (closes
  [#3307](https://github.com/bootstrap-vue/bootstrap-vue/issues/3307))
  ([#3383](https://github.com/bootstrap-vue/bootstrap-vue/issues/3383))
  ([ce19fc7](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce19fc7caa90ff1a53cdd3bee7d27dd5eaacc292))
- **table:** ensure provider is refreshed when filter is an object (closes
  [#3428](https://github.com/bootstrap-vue/bootstrap-vue/issues/3428))
  ([#3429](https://github.com/bootstrap-vue/bootstrap-vue/issues/3429))
  ([b95c614](https://github.com/bootstrap-vue/bootstrap-vue/commit/b95c6141744b9b853a4def5e946c0a13bb177a52))
- **table:** fix broken aria-labels for sortable columns + break out code into additional mixins +
  tests ([#2884](https://github.com/bootstrap-vue/bootstrap-vue/issues/2884))
  ([ddc2006](https://github.com/bootstrap-vue/bootstrap-vue/commit/ddc20060f6e0704043fa711308350e4f5e43f74b))
- **table:** fix detection of text selection
  ([#2804](https://github.com/bootstrap-vue/bootstrap-vue/issues/2804))
  ([c7e68f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7e68f0b931e0be1aca11684cd2467bb2ff34e3e))
- **table:** fix range selection
  ([#2865](https://github.com/bootstrap-vue/bootstrap-vue/issues/2865))
  ([da49558](https://github.com/bootstrap-vue/bootstrap-vue/commit/da49558a8f05889ef09fa469575365519e46b833))
- **table:** fix SSR mismatch errors
  ([#2897](https://github.com/bootstrap-vue/bootstrap-vue/issues/2897))
  ([6c1940d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6c1940d4a9660425fc80bea55445e047844a772a))
- **tables:** add in missing Bootstrap variant class `bg-active` for dark tables
  ([#4098](https://github.com/bootstrap-vue/bootstrap-vue/issues/4098))
  ([d9900ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/d9900ab12555540987eb130b4b0300e3c810e247))
- **tables:** ensure row variant `active` (class `table-active`) takes precedence over other row
  variants (addresses [#3008](https://github.com/bootstrap-vue/bootstrap-vue/issues/3008))
  ([#4127](https://github.com/bootstrap-vue/bootstrap-vue/issues/4127))
  ([fdb8bb6](https://github.com/bootstrap-vue/bootstrap-vue/commit/fdb8bb60f4c92cbc1dc742d3e0e4fdeb609bd3cb))
- **tables:** fix issue with sticky columns when table is not responsive but has sticky headers
  (fixes [#4354](https://github.com/bootstrap-vue/bootstrap-vue/issues/4354))
  ([#4356](https://github.com/bootstrap-vue/bootstrap-vue/issues/4356))
  ([56b3958](https://github.com/bootstrap-vue/bootstrap-vue/commit/56b395899ed9c6606e5757a2fd222a8c9aecf362))
- **tabs:** add detection of when registered tabs change order
  ([#3513](https://github.com/bootstrap-vue/bootstrap-vue/issues/3513))
  ([130f8ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/130f8ffe85305a4f6eb9f38e199562edeabf72ea))
- **tabs:** Emit click on b-tab instance when button clicked. Fixes
  [#2512](https://github.com/bootstrap-vue/bootstrap-vue/issues/2512)
  ([#2530](https://github.com/bootstrap-vue/bootstrap-vue/issues/2530))
  ([8e129a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e129a31dc841e2a919febbff13e1bbbb197e18f))
- **tabs:** fix initial value handling (closes
  [#2656](https://github.com/bootstrap-vue/bootstrap-vue/issues/2656))
  ([#2661](https://github.com/bootstrap-vue/bootstrap-vue/issues/2661))
  ([2708c74](https://github.com/bootstrap-vue/bootstrap-vue/commit/2708c74780b9b290bcd95354e0b24eded63dc617))
- **tabs:** fix regression of tabs in lazy modals - use DOM query for probing tabs after mount
  (closes: [#3361](https://github.com/bootstrap-vue/bootstrap-vue/issues/3361))
  ([#3375](https://github.com/bootstrap-vue/bootstrap-vue/issues/3375))
  ([2b188a2](https://github.com/bootstrap-vue/bootstrap-vue/commit/2b188a246ba9c6beddacb942c4a8e9d297b0fafc))
- **tabs:** fix regression with dynamically added tabs (fixes
  [#3395](https://github.com/bootstrap-vue/bootstrap-vue/issues/3395))
  ([#3396](https://github.com/bootstrap-vue/bootstrap-vue/issues/3396))
  ([f254f90](https://github.com/bootstrap-vue/bootstrap-vue/commit/f254f9002e52d6539d0ed01355f529fb4358fe04))
- **tabs:** nav item `id` and `aria-controls`
  ([#3832](https://github.com/bootstrap-vue/bootstrap-vue/issues/3832))
  ([06c6119](https://github.com/bootstrap-vue/bootstrap-vue/commit/06c61198c739aab313fb0afaf6fb0c2518522159))
- **tabs:** prevent double input event on mount, and add additional tests
  ([#2748](https://github.com/bootstrap-vue/bootstrap-vue/issues/2748))
  ([c462e0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/c462e0a7e12d8e06600036eae8bf75034507da12))
- **toast:** accessibility - prevent duplicate toast announcements for screen readers (closes
  [#3322](https://github.com/bootstrap-vue/bootstrap-vue/issues/3322))
  ([#3329](https://github.com/bootstrap-vue/bootstrap-vue/issues/3329))
  ([d44fba5](https://github.com/bootstrap-vue/bootstrap-vue/commit/d44fba5f12ee5665707984c10cdb0b291b9e744c))
- **tooltip, popover:** check `document.body` instead of `document` for IE11 support (fixes
  [#4074](https://github.com/bootstrap-vue/bootstrap-vue/issues/4074))
  ([#4075](https://github.com/bootstrap-vue/bootstrap-vue/issues/4075))
  ([1eda4fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/1eda4fe8b13690a12735404924295c8be4800e05))
- **tooltip, popover:** handle case where tooltips are applied to dropdown root elements (closes
  [#3703](https://github.com/bootstrap-vue/bootstrap-vue/issues/3703))
  ([#3704](https://github.com/bootstrap-vue/bootstrap-vue/issues/3704))
  ([39df4f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/39df4f10c7f07f471585d24b59699977ff4c1a7a))
- **tooltip, popover:** hide trigger element title attribute during show delay (fixes
  [#4114](https://github.com/bootstrap-vue/bootstrap-vue/issues/4114))
  ([#4120](https://github.com/bootstrap-vue/bootstrap-vue/issues/4120))
  ([2dd8d5a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dd8d5a6b1e70157f7127021ec160630eeb9cd59))
- **tooltips, popovers:** fix memory leak (closes
  [#4400](https://github.com/bootstrap-vue/bootstrap-vue/issues/4400))
  ([#4401](https://github.com/bootstrap-vue/bootstrap-vue/issues/4401))
  ([c71352d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c71352d674347e5e2d72fe8b82334fc87a4ffd8c))
- **types:** add BInputGroup to TypeScript definitions
  ([#3487](https://github.com/bootstrap-vue/bootstrap-vue/issues/3487))
  ([b4ac081](https://github.com/bootstrap-vue/bootstrap-vue/commit/b4ac0819825c542039347b009d66e02a28a8939e))
- **types:** adjust typing of BvComponent and BvPlugin (closes
  [#3390](https://github.com/bootstrap-vue/bootstrap-vue/issues/3390))
  ([#3391](https://github.com/bootstrap-vue/bootstrap-vue/issues/3391))
  ([6f0f3fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f0f3fd0d49997b3cbd9848ad4233b9272f3c1e0))
- **types:** BCardSubTitle component declared export name
  ([#4229](https://github.com/bootstrap-vue/bootstrap-vue/issues/4229))
  ([9f216df](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f216df0bc7bc97a96e432ea22cabd917bf56ed7))
- **types:** update table field definition types to include sticky column (fixes
  [#5263](https://github.com/bootstrap-vue/bootstrap-vue/issues/5263))
  ([#5265](https://github.com/bootstrap-vue/bootstrap-vue/issues/5265))
  ([20eb3ac](https://github.com/bootstrap-vue/bootstrap-vue/commit/20eb3ac9e22ddbcc41d1f1aa923871007abe0dc0))
- **util/html:** ensure argument is a string (Closes
  [#2770](https://github.com/bootstrap-vue/bootstrap-vue/issues/2770))
  ([#2775](https://github.com/bootstrap-vue/bootstrap-vue/issues/2775))
  ([356247f](https://github.com/bootstrap-vue/bootstrap-vue/commit/356247fd27eef618d788536db9c8348efd291dba))
- **util/loose-equal:** handle comparing sparse arrays
  ([#2813](https://github.com/bootstrap-vue/bootstrap-vue/issues/2813))
  ([6ac8ade](https://github.com/bootstrap-vue/bootstrap-vue/commit/6ac8ade1edea9b95ffc20ff2b7226d7d9fbeeaed))
- **utils:** add back array notation support to `get()` util
  ([#2689](https://github.com/bootstrap-vue/bootstrap-vue/issues/2689))
  ([9e824a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e824a510d0b8a3022a4e926f870e914d7072621))
- **utils:** make `looseEqual()` util compliant with Vue.js spec
  ([#2651](https://github.com/bootstrap-vue/bootstrap-vue/issues/2651))
  ([1b6a994](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b6a994d4effa29a86d908aad0b96f9a6695ec31))
- **utils:** Make `looseEqual()` util handle File comparison correctly
  ([#2640](https://github.com/bootstrap-vue/bootstrap-vue/issues/2640))
  ([401d3e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/401d3e974249c404df2d80282ccecae71baf57a7))
- **utils/dom:** update closest routine to support SVG
  ([#2901](https://github.com/bootstrap-vue/bootstrap-vue/issues/2901))
  ([9d4408d](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d4408d6bebcc2859b8fa1c383c59b692e126099))
- **utils/get:** handle case where passed object is undefined (Fixes
  [#2623](https://github.com/bootstrap-vue/bootstrap-vue/issues/2623))
  ([#2624](https://github.com/bootstrap-vue/bootstrap-vue/issues/2624))
  ([eb07b19](https://github.com/bootstrap-vue/bootstrap-vue/commit/eb07b196f3762d5e441b10d3e24d563544d014f8))
- **utils/get:** handle cases when field value is not array or object (closes
  [#2807](https://github.com/bootstrap-vue/bootstrap-vue/issues/2807))
  ([#2808](https://github.com/bootstrap-vue/bootstrap-vue/issues/2808))
  ([c656fa3](https://github.com/bootstrap-vue/bootstrap-vue/commit/c656fa31f4983e991a2e8d0d3c19e52bcfbc032b))
- **utils/get:** handle edge case with inherited object getters (fixes
  [#3463](https://github.com/bootstrap-vue/bootstrap-vue/issues/3463))
  ([#3465](https://github.com/bootstrap-vue/bootstrap-vue/issues/3465))
  ([e2c8cb1](https://github.com/bootstrap-vue/bootstrap-vue/commit/e2c8cb126619e158a3263b1781598c2255190b34))
- **utisl/observeDom:** make sure to check for browser enviroment
  ([#2838](https://github.com/bootstrap-vue/bootstrap-vue/issues/2838))
  ([8471f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/8471f317785ce6f98b3fd0ce1218d66238fe00f5))
- **v-b-toggle:** don't override `role` if element has a `role` assigned
  ([#3889](https://github.com/bootstrap-vue/bootstrap-vue/issues/3889))
  ([5d155ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/5d155badd671cc60f1f6ab3c294e713ebf7e9915))
- fix Html casing for props ([#2594](https://github.com/bootstrap-vue/bootstrap-vue/issues/2594))
  ([3772bf5](https://github.com/bootstrap-vue/bootstrap-vue/commit/3772bf5b09de8b251c469b52e9f87a6ade0b2bca))
- handle nested form options normalization
  ([#5247](https://github.com/bootstrap-vue/bootstrap-vue/issues/5247))
  ([0c57ffe](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c57ffe31c946475498fa3554b8b4aba4e9d19df))
- nested form options normalization
  ([bea0393](https://github.com/bootstrap-vue/bootstrap-vue/commit/bea039386518c0b0a77bed46b13330c6840b7daa))
- remove underscore form variable and method names
  ([#3352](https://github.com/bootstrap-vue/bootstrap-vue/issues/3352))
  ([bcd0a2f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bcd0a2f6bdf995e56aa0d62c395caf6922424502))
- temporary fix for validation icon positioning (Closes
  [#2599](https://github.com/bootstrap-vue/bootstrap-vue/issues/2599))
  ([#2607](https://github.com/bootstrap-vue/bootstrap-vue/issues/2607))
  ([7168989](https://github.com/bootstrap-vue/bootstrap-vue/commit/71689892576de559c90a5fa9a4a9b80b9371ced3))
- use `installFactory` for main `BootstrapVue` plugin (closes
  [#3338](https://github.com/bootstrap-vue/bootstrap-vue/issues/3338))
  ([#3340](https://github.com/bootstrap-vue/bootstrap-vue/issues/3340))
  ([4c0c445](https://github.com/bootstrap-vue/bootstrap-vue/commit/4c0c4451430cb9e5aec162d1cc30f75e0c6c3dd5))
- **$bvToast,$bvModal:** ensure values passed to slots are arrays for Vue.js 2.5.x compatibility
  (closes [#3174](https://github.com/bootstrap-vue/bootstrap-vue/issues/3174))
  ([#3252](https://github.com/bootstrap-vue/bootstrap-vue/issues/3252))
  ([f46b5d8](https://github.com/bootstrap-vue/bootstrap-vue/commit/f46b5d8eba9936b0c1c9522afb271b111291b432))
- **b-input-group:** fix issue with slots (closes
  [#3284](https://github.com/bootstrap-vue/bootstrap-vue/issues/3284))
  ([#3288](https://github.com/bootstrap-vue/bootstrap-vue/issues/3288))
  ([5639e8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/5639e8f4e6070c0f5001dbc43e3e1e2de9772503))
- **b-input-group:** use same input-group-prepend/append for both props and slots
  ([#3321](https://github.com/bootstrap-vue/bootstrap-vue/issues/3321))
  ([fb7386e](https://github.com/bootstrap-vue/bootstrap-vue/commit/fb7386e020f6d710c665eb8895d490489c5af278))
- **b-link:** ensure href prop is not passed to router-links (fixes
  [#3066](https://github.com/bootstrap-vue/bootstrap-vue/issues/3066))
  ([#3084](https://github.com/bootstrap-vue/bootstrap-vue/issues/3084))
  ([f679c11](https://github.com/bootstrap-vue/bootstrap-vue/commit/f679c118a91615bd2e76047ffbdfff672f0152d7))
- **b-modal:** delay initially open modal via nextTick when using v-model or visible prop
  ([#3320](https://github.com/bootstrap-vue/bootstrap-vue/issues/3320))
  ([6f3010a](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f3010a63f6d79bfe0318187b0f52870c58befc7)),
  closes
  [/github.com/bootstrap-vue/bootstrap-vue/issues/3312#issuecomment-493389988](https://github.com/bootstrap-vue//github.com/bootstrap-vue/bootstrap-vue/issues/3312/issues/issuecomment-493389988)
- **b-nav-item-dropdown:** fix disabled state (fixes
  [#3264](https://github.com/bootstrap-vue/bootstrap-vue/issues/3264))
  ([#3266](https://github.com/bootstrap-vue/bootstrap-vue/issues/3266))
  ([10d4c4d](https://github.com/bootstrap-vue/bootstrap-vue/commit/10d4c4df13bfa27fefe373ff561056b707610889))
- **b-toaster:** CSS fix for IE11 support (fixes
  [#3327](https://github.com/bootstrap-vue/bootstrap-vue/issues/3327))
  ([#3328](https://github.com/bootstrap-vue/bootstrap-vue/issues/3328))
  ([88b1cfd](https://github.com/bootstrap-vue/bootstrap-vue/commit/88b1cfdbe26660d878af0f1936a281b9712525a0))
- **breadcrumb-item:** remove `role="presentation"`
  ([#2991](https://github.com/bootstrap-vue/bootstrap-vue/issues/2991))
  ([e84c4a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/e84c4a76468e6faabeafb08cbe0789362c288e6a))
- **build:** enable babel option to interop default (fixes
  [#3038](https://github.com/bootstrap-vue/bootstrap-vue/issues/3038))
  ([#3046](https://github.com/bootstrap-vue/bootstrap-vue/issues/3046))
  ([4e981c2](https://github.com/bootstrap-vue/bootstrap-vue/commit/4e981c2a4174197983477526a78564114e728ad6))
- **col, form-group:** implement self overwriting lazy props getter (fixes:
  [#3080](https://github.com/bootstrap-vue/bootstrap-vue/issues/3080))
  ([#3125](https://github.com/bootstrap-vue/bootstrap-vue/issues/3125))
  ([92756bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/92756bd0ad59133a9aecaa4231158ce47e81a29d))
- **collapse:** is-nav link click behaviour - check if collapse has `display: block !important`
  before attempting to close collapse
  ([#3199](https://github.com/bootstrap-vue/bootstrap-vue/issues/3199))
  ([b0729cc](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0729ccd0f38edad354fb85e9ad9403f737a0a3b))
- **docs:** add missing close tags for `<b-icon>` components
  ([#4680](https://github.com/bootstrap-vue/bootstrap-vue/issues/4680))
  ([0d86940](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d86940d67520f418c966a7c8879898db0b899e0))
- **docs:** correct Vuelidate validation example and some minor tweaks
  ([#3332](https://github.com/bootstrap-vue/bootstrap-vue/issues/3332))
  ([d5c22a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/d5c22a8cef00bba7f383e8dd03a23caab2d45514))
- **docs:** fix component plugin's included plugins and directives
  ([#2966](https://github.com/bootstrap-vue/bootstrap-vue/issues/2966))
  ([cbf24c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbf24c39a71501802b49a370663b1e55ee863deb))
- **docs:** fix polyfill for IE 11
  ([#3114](https://github.com/bootstrap-vue/bootstrap-vue/issues/3114))
  ([298f733](https://github.com/bootstrap-vue/bootstrap-vue/commit/298f73388c94abec3430a03994cadb70ac0d3159))
- **docs:** improve <b-modal> prevent closing example
  ([#3054](https://github.com/bootstrap-vue/bootstrap-vue/issues/3054))
  ([f609316](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6093165a3b48a567519b5f9385c4e0264552e78))
- **docs:** improve code highlighting + table styles
  ([#3078](https://github.com/bootstrap-vue/bootstrap-vue/issues/3078))
  ([d4b9895](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4b98957133106b636016a60966b093d26afb488))
- **docs:** improve nav social links alignment
  ([#3122](https://github.com/bootstrap-vue/bootstrap-vue/issues/3122))
  ([d37500e](https://github.com/bootstrap-vue/bootstrap-vue/commit/d37500e9a9bf9db9405e9d2b44900387bde9c3c0))
- **docs:** info modal in complete <b-table> example (closes
  [#3144](https://github.com/bootstrap-vue/bootstrap-vue/issues/3144))
  ([#3145](https://github.com/bootstrap-vue/bootstrap-vue/issues/3145))
  ([9dfe0bf](https://github.com/bootstrap-vue/bootstrap-vue/commit/9dfe0bfaed704c7939c002e86ef3d3ac409ed1f8))
- **docs:** minor tweaks ([#3121](https://github.com/bootstrap-vue/bootstrap-vue/issues/3121))
  ([1917f1b](https://github.com/bootstrap-vue/bootstrap-vue/commit/1917f1bda1dcda9e3af2e0a9d5dcfe414bf6d361))
- **docs:** overall improvements
  ([#3129](https://github.com/bootstrap-vue/bootstrap-vue/issues/3129))
  ([be53376](https://github.com/bootstrap-vue/bootstrap-vue/commit/be533769c53f6e1a215abc83b3c10f1f5f985728))
- **docs:** typo in ´<strong>´ tags
  ([#3163](https://github.com/bootstrap-vue/bootstrap-vue/issues/3163))
  ([e465ae9](https://github.com/bootstrap-vue/bootstrap-vue/commit/e465ae96c05c951a45924db06cb2e0dadca09d4d))
- **docs:** unify heading casing
  ([#3101](https://github.com/bootstrap-vue/bootstrap-vue/issues/3101))
  ([649a845](https://github.com/bootstrap-vue/bootstrap-vue/commit/649a845a2a182c7aa0d89ec2603722ca94448da2))
- **docs:** use regex to normalize URL with better browser support
  ([#3147](https://github.com/bootstrap-vue/bootstrap-vue/issues/3147))
  ([c3bd004](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3bd004eea9bb15fca06c2ac5787767b06657bdc))
- **events:** correct `capture` value of `EVENT_OPTIONS_NO_CAPTURE`
  ([#4763](https://github.com/bootstrap-vue/bootstrap-vue/issues/4763))
  ([e9a99e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9a99e6e2cf080ae5d9783229b93fd2eaeedf436))
- **form-input:** properly handle out-of-sync values (closes
  [#2657](https://github.com/bootstrap-vue/bootstrap-vue/issues/2657))
  ([#3172](https://github.com/bootstrap-vue/bootstrap-vue/issues/3172))
  ([976f9c1](https://github.com/bootstrap-vue/bootstrap-vue/commit/976f9c1bfbd4443206e1d81c2664f1cf4a312f56))
- **form-textarea:** improve auto-row height calculation timing (closes
  [#3103](https://github.com/bootstrap-vue/bootstrap-vue/issues/3103))
  ([#3105](https://github.com/bootstrap-vue/bootstrap-vue/issues/3105))
  ([dfc662e](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfc662ed2b4a845186d87e5849c034de43326fdf))
- **form-textarea:** improved computedHeight calculation when in auto resize mode
  ([#3012](https://github.com/bootstrap-vue/bootstrap-vue/issues/3012))
  ([0043b92](https://github.com/bootstrap-vue/bootstrap-vue/commit/0043b9263298999ec09c37a79a2c9af088c97278))
- **modal:** clear internal return_focus after modal closes (fixes
  [#3067](https://github.com/bootstrap-vue/bootstrap-vue/issues/3067))
  ([#3068](https://github.com/bootstrap-vue/bootstrap-vue/issues/3068))
  ([971556f](https://github.com/bootstrap-vue/bootstrap-vue/commit/971556f17342fb11635fd74f0da6fabaadbcc688))
- **modal:** ensure that v-model is updated when show or hide is canceled
  ([#3131](https://github.com/bootstrap-vue/bootstrap-vue/issues/3131))
  ([6726a33](https://github.com/bootstrap-vue/bootstrap-vue/commit/6726a33a765af6aba148ea7a434f5e2b71a662fb))
- **modal:** exclude document.body when determining return focus element
  ([#3228](https://github.com/bootstrap-vue/bootstrap-vue/issues/3228))
  ([092ab2d](https://github.com/bootstrap-vue/bootstrap-vue/commit/092ab2decbd76e98a90b1f71a509bd29c68f03f8))
- **modal:** fix close on click-out for IE11
  ([#3117](https://github.com/bootstrap-vue/bootstrap-vue/issues/3117))
  ([9b09e52](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b09e52567aedbfe17d68cd27470b886b1c5d350))
- **modal:** handle HMR when defining property on Vue prototype
  ([#3123](https://github.com/bootstrap-vue/bootstrap-vue/issues/3123))
  ([a4e7f21](https://github.com/bootstrap-vue/bootstrap-vue/commit/a4e7f2188f0fbcc8189290fbb125f6572cceb024))
- **modal:** prevent close on backdrop when click initiated inside modal content (fixes
  [#3025](https://github.com/bootstrap-vue/bootstrap-vue/issues/3025))
  ([#3029](https://github.com/bootstrap-vue/bootstrap-vue/issues/3029))
  ([ad57e8c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ad57e8cfb7a3e88d92a3f1b43e33c495b0d0eb84))
- **modal:** prevent duplicate key when sending to portal-target
  ([#3235](https://github.com/bootstrap-vue/bootstrap-vue/issues/3235))
  ([5204ad7](https://github.com/bootstrap-vue/bootstrap-vue/commit/5204ad795d5005db14780330a195f8c13e6dc070))
- **modal:** return focus edge case bug in IE11 (fixes
  [#3206](https://github.com/bootstrap-vue/bootstrap-vue/issues/3206))
  ([#3207](https://github.com/bootstrap-vue/bootstrap-vue/issues/3207))
  ([7ef36c2](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ef36c219f7ed493906be5c86f2da53521871c47))
- **modal:** stacked modal z-index calculations (closes
  [#3015](https://github.com/bootstrap-vue/bootstrap-vue/issues/3015))
  ([#3017](https://github.com/bootstrap-vue/bootstrap-vue/issues/3017))
  ([891e8cc](https://github.com/bootstrap-vue/bootstrap-vue/commit/891e8cc21937b9b96204d4f5c012e5e8600adc35))
- **nuxt module:** ensure that css and transpile are arrays (fixes:
  [#3141](https://github.com/bootstrap-vue/bootstrap-vue/issues/3141))
  ([#3142](https://github.com/bootstrap-vue/bootstrap-vue/issues/3142))
  ([239da77](https://github.com/bootstrap-vue/bootstrap-vue/commit/239da7775f2a3de0b0aec393eae9d52e60239fd1))
- **nuxt module:** remove unnecessary export statements
  ([#4624](https://github.com/bootstrap-vue/bootstrap-vue/issues/4624))
  ([27f066c](https://github.com/bootstrap-vue/bootstrap-vue/commit/27f066cfa07ee311fe1e312d9a9ebd0eb76750c7))
- **pagination:** reset to page 1 when total-rows or per-page changes (closes
  [#2987](https://github.com/bootstrap-vue/bootstrap-vue/issues/2987))
  ([#2993](https://github.com/bootstrap-vue/bootstrap-vue/issues/2993))
  ([df2e77a](https://github.com/bootstrap-vue/bootstrap-vue/commit/df2e77ac1613324e79baa73ae90f893eb059c4f1))
- **pagination:** use unicode escape sequence for default bookend button text
  ([#3186](https://github.com/bootstrap-vue/bootstrap-vue/issues/3186))
  ([dfb6af7](https://github.com/bootstrap-vue/bootstrap-vue/commit/dfb6af73c4bdbf7815ea82ed1077c07d8e2962e4))
- **pagination-nav:** better current page detection in IE
  ([#3006](https://github.com/bootstrap-vue/bootstrap-vue/issues/3006))
  ([f742aa9](https://github.com/bootstrap-vue/bootstrap-vue/commit/f742aa948108c72d67d688925410ac98504eb77a))
- **tab:** don't use `aria-expanded` on the panel
  ([#3143](https://github.com/bootstrap-vue/bootstrap-vue/issues/3143))
  ([381eacf](https://github.com/bootstrap-vue/bootstrap-vue/commit/381eacf170f88e4e2169ef855d49ad91413bb0e2))
- **table:** fix bad copy paste
  ([#5067](https://github.com/bootstrap-vue/bootstrap-vue/issues/5067))
  ([874dca2](https://github.com/bootstrap-vue/bootstrap-vue/commit/874dca2c8c385fecf7cec76e6cfa44eda9fcabf4))
- **table:** prevent hover style on busy/empty row (closes
  [#3079](https://github.com/bootstrap-vue/bootstrap-vue/issues/3079))
  ([#3086](https://github.com/bootstrap-vue/bootstrap-vue/issues/3086))
  ([c53ffd4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c53ffd4fab943006b000d706683ea8f5653afe4d))
- **toast:** use appendChild instead of append for IE 11 support
  ([#3160](https://github.com/bootstrap-vue/bootstrap-vue/issues/3160))
  ([be118a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/be118a98727f88e8771ba6c883018e3b154d452b))
- **toaster:** let on-demand toasts know the toaster has been destroyed
  ([#3130](https://github.com/bootstrap-vue/bootstrap-vue/issues/3130))
  ([0b44e4d](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b44e4d043a0dce30d95e2e53b71cd0d94bf5525))
- **tooltip/popover:** prevent double show/shown event emits when .sync modifier used (fixes
  [#1637](https://github.com/bootstrap-vue/bootstrap-vue/issues/1637))
  ([#3001](https://github.com/bootstrap-vue/bootstrap-vue/issues/3001))
  ([0d3599a](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d3599a83c6bef5f2262763550daa1b66095abee))
- **types:** fix msxBoxConfirm typo
  ([#3280](https://github.com/bootstrap-vue/bootstrap-vue/issues/3280))
  ([8027e5a](https://github.com/bootstrap-vue/bootstrap-vue/commit/8027e5ab6c4d65e53b727355caaeed2b18f5563f))
- **typescript:** replaced invalid `mixed` keyword with `any` (fixes
  [#3041](https://github.com/bootstrap-vue/bootstrap-vue/issues/3041))
  ([#3043](https://github.com/bootstrap-vue/bootstrap-vue/issues/3043))
  ([36e8246](https://github.com/bootstrap-vue/bootstrap-vue/commit/36e824626454ecb7869b212d0cb69e92937074ff))
- **utils:** improve `dom`, `env`, `inspect` and test utils
  ([#3085](https://github.com/bootstrap-vue/bootstrap-vue/issues/3085))
  ([bd85049](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd85049b67836c0f451d0fd27de7fdd257e6d535))
- **utils/get:** handle case when nested value is falsy
  ([#2982](https://github.com/bootstrap-vue/bootstrap-vue/issues/2982))
  ([40f6cb7](https://github.com/bootstrap-vue/bootstrap-vue/commit/40f6cb7c11d561ce035d23bde88f591891dcd057))
- **v-b-toggle/b-collapse:** ensure toggle remains in sync with collapse (Closes
  [#3020](https://github.com/bootstrap-vue/bootstrap-vue/issues/3020))
  ([#3021](https://github.com/bootstrap-vue/bootstrap-vue/issues/3021))
  ([6b36d0d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b36d0d088789cf8439498a890881d45d572d20c))
- use stable nuxt opencollective
  ([#1885](https://github.com/bootstrap-vue/bootstrap-vue/issues/1885))
  ([876f4a1](https://github.com/bootstrap-vue/bootstrap-vue/commit/876f4a1a4f46cc58f9d20788758c7ec03c576a3c))
- **table:** generate TR key using serialized item or primary key if provided (fixes:
  [#2410](https://github.com/bootstrap-vue/bootstrap-vue/issues/2410))
  ([#2416](https://github.com/bootstrap-vue/bootstrap-vue/issues/2416))
  ([6e22d99](https://github.com/bootstrap-vue/bootstrap-vue/commit/6e22d99bb3ae50674abaace337270f65a5cbf6b9))
- **table:** selectable range mode update and minor fixes
  ([#2326](https://github.com/bootstrap-vue/bootstrap-vue/issues/2326))
  ([ef281d1](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef281d12dbb3a6d3ff56b621f5712f0d914495f9))
- **tabs:** `tabIndex` prop type
  ([#2459](https://github.com/bootstrap-vue/bootstrap-vue/issues/2459))
  ([05ef65a](https://github.com/bootstrap-vue/bootstrap-vue/commit/05ef65ad1706c44b4aa3a093719da7040eaad5fa))
- **tabs:** Fix tab titleLinkClass and titleItemClass handling
  ([#2448](https://github.com/bootstrap-vue/bootstrap-vue/issues/2448))
  ([36400f5](https://github.com/bootstrap-vue/bootstrap-vue/commit/36400f5f50ea762b7ae0f8c62044cf5d6ec5f238))
- **tabs:** various fixes and improvements (Fixes:
  [#2327](https://github.com/bootstrap-vue/bootstrap-vue/issues/2327),
  [#2148](https://github.com/bootstrap-vue/bootstrap-vue/issues/2148). Closes:
  [#2403](https://github.com/bootstrap-vue/bootstrap-vue/issues/2403),
  [#2180](https://github.com/bootstrap-vue/bootstrap-vue/issues/2180))
  ([#2442](https://github.com/bootstrap-vue/bootstrap-vue/issues/2442))
  ([de11a8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/de11a8f5e9999cbd98909b9ae3a9d58b556ee587))
- **types:** add missing declaration for `b-form-timepicker` (closes
  [#5035](https://github.com/bootstrap-vue/bootstrap-vue/issues/5035))
  ([#5036](https://github.com/bootstrap-vue/bootstrap-vue/issues/5036))
  ([ae84118](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae841184dc3037b5d6f365311cc668bccb0e85da))
- **types:** add missing declarations for `b-form-select-option` & `b-form-select-option-group`
  ([#4595](https://github.com/bootstrap-vue/bootstrap-vue/issues/4595))
  ([8d60832](https://github.com/bootstrap-vue/bootstrap-vue/commit/8d60832d38e74231a4bda15aa045b84aae97d2ed))
- **typescript:** include named export BootstrapVue in declaration file
  ([#4590](https://github.com/bootstrap-vue/bootstrap-vue/issues/4590))
  ([603307a](https://github.com/bootstrap-vue/bootstrap-vue/commit/603307aeccf6141b94eff2186baee4ec43439033))
- **utils:** correct `identity` spelling error
  ([#4579](https://github.com/bootstrap-vue/bootstrap-vue/issues/4579))
  ([7fed191](https://github.com/bootstrap-vue/bootstrap-vue/commit/7fed1911d6d9f7eae81526010483c71e1679e770))
- **utils:** pass all Array/Object util shortcuts as functions, for handling late loaded polyfills
  ([#4647](https://github.com/bootstrap-vue/bootstrap-vue/issues/4647))
  ([f584425](https://github.com/bootstrap-vue/bootstrap-vue/commit/f5844256a03d2f4b8006900419acfa2c5e3803c3)),
  closes
  [/github.com/bootstrap-vue/bootstrap-vue/pull/3641#issuecomment-575884289](https://github.com/bootstrap-vue//github.com/bootstrap-vue/bootstrap-vue/pull/3641/issues/issuecomment-575884289)
- **v-b-modal:** bind to inner link or button for dropdown items or nav items (fixes
  [#4149](https://github.com/bootstrap-vue/bootstrap-vue/issues/4149))
  ([#4187](https://github.com/bootstrap-vue/bootstrap-vue/issues/4187))
  ([5c28bd2](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c28bd2fe22a14e5b30b3e955a0eaed5acf62ee5))
- **v-b-modal:** ensure trigger element is keyboard accessible if not a link or button, for A11Y
  ([#4365](https://github.com/bootstrap-vue/bootstrap-vue/issues/4365))
  ([f54ca29](https://github.com/bootstrap-vue/bootstrap-vue/commit/f54ca2969a38f75a69d58a8eedeac4f0bd905eca))
- **v-b-modal:** only unbind/rebind if trigger element or modal ID changes (closes
  [#4669](https://github.com/bootstrap-vue/bootstrap-vue/issues/4669))
  ([#4672](https://github.com/bootstrap-vue/bootstrap-vue/issues/4672))
  ([e53a05d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e53a05d960a9de0ca9636ee31e0197e7e554ddbc))
- **v-b-modal:** open modal using `ENTER` key on non-button elements for A11Y
  ([#4364](https://github.com/bootstrap-vue/bootstrap-vue/issues/4364))
  ([0d27d7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d27d7be2677f1fdada7c91c5b9f58a216a3de4e))
- **v-b-tooltip, v-b-popover:** add missing `disabled` config option
  ([#4057](https://github.com/bootstrap-vue/bootstrap-vue/issues/4057))
  ([f488dc1](https://github.com/bootstrap-vue/bootstrap-vue/commit/f488dc1e6c8aab7ba43fce9805f6f5bccd6419c3))
- **v-b-tooltip, v-b-popover:** don't show if no title/content provided (closes
  [#4064](https://github.com/bootstrap-vue/bootstrap-vue/issues/4064))
  ([#4076](https://github.com/bootstrap-vue/bootstrap-vue/issues/4076))
  ([0b7de29](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b7de2992b42c094541b574b4bf24bcf10abe22e))
- **v-b-tooltip, v-b-popover:** ensure reference to trigger element is passed to title/content
  function (fixes [#4331](https://github.com/bootstrap-vue/bootstrap-vue/issues/4331))
  ([#4332](https://github.com/bootstrap-vue/bootstrap-vue/issues/4332))
  ([ea0cbda](https://github.com/bootstrap-vue/bootstrap-vue/commit/ea0cbda18b58a619c1ddd100d3b48905f88bf926))
- **v-b-visible:** fix type error in `componentUpdated` hook + minor docs update/fixes
  ([#4327](https://github.com/bootstrap-vue/bootstrap-vue/issues/4327))
  ([5f3ba9e](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f3ba9e7a22c236f7f8023a99dc0116e1b382dc8))
- **web-types:** update web-types code generation to match schema
  ([#4271](https://github.com/bootstrap-vue/bootstrap-vue/issues/4271))
  ([009431e](https://github.com/bootstrap-vue/bootstrap-vue/commit/009431ee2f0769dc22a47f7f15ee834621e5b73c))
- relax prop type checks to prevent vue warns
  ([835eccf](https://github.com/bootstrap-vue/bootstrap-vue/commit/835eccfe92de90a56a06531006245b53a43ec5b8))
- **alert:** import button-close in alert with a name matching tag.
  ([#1523](https://github.com/bootstrap-vue/bootstrap-vue/issues/1523)) fixes
  [#1522](https://github.com/bootstrap-vue/bootstrap-vue/issues/1522).
  ([51b527f](https://github.com/bootstrap-vue/bootstrap-vue/commit/51b527f83c0577f62fe2e0035e15aaa2d5fb8bac))
- **alert:** target custom transition CSS to the alert component
  ([#2205](https://github.com/bootstrap-vue/bootstrap-vue/issues/2205))
  ([0a48268](https://github.com/bootstrap-vue/bootstrap-vue/commit/0a4826852a35e3d257f39883cc5dfb44d0363ad0))
- **build:** don't exclude lodash.get
  ([543c3c2](https://github.com/bootstrap-vue/bootstrap-vue/commit/543c3c2f9aeccffb03c571aeea93333774243ab3))
- **card:** duplicate header and footer slots with no-body
  ([#1713](https://github.com/bootstrap-vue/bootstrap-vue/issues/1713),
  [#1680](https://github.com/bootstrap-vue/bootstrap-vue/issues/1680))
  ([2bd0e71](https://github.com/bootstrap-vue/bootstrap-vue/commit/2bd0e713b877e1ced7fa5caba418e9b88c12aa1f))
- **card:** fix card and sub component render issues. Fixes
  [#2062](https://github.com/bootstrap-vue/bootstrap-vue/issues/2062)
  ([#2125](https://github.com/bootstrap-vue/bootstrap-vue/issues/2125))
  ([430371f](https://github.com/bootstrap-vue/bootstrap-vue/commit/430371ff1ce5933b041673e31bd6ba75605eb673))
- **card:** pass children instead of default prop to sub-components
  ([63b35e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/63b35e3429b353d8ac1af01fd3e65383cc7baf13))
- **checkbox,radio:** update HTML markup for BS4
  ([#1539](https://github.com/bootstrap-vue/bootstrap-vue/issues/1539))
  ([ccfb5b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/ccfb5b1f45cc5ac4c056070f4e78ef098411729c))
- **collapse:** when is-nav, do better checking of click events (Fixes
  [#2222](https://github.com/bootstrap-vue/bootstrap-vue/issues/2222))
  ([#2225](https://github.com/bootstrap-vue/bootstrap-vue/issues/2225))
  ([8b96e1e](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b96e1efdd9d3ea03ca707eec17de16423afc19c))
- **collapse/toggle:** "collapsed" class cleared when component updated
  ([#2102](https://github.com/bootstrap-vue/bootstrap-vue/issues/2102))
  ([6d33cae](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d33caee025a6ba08b1ce49cbc357c2111b52e56)),
  closes [#1798](https://github.com/bootstrap-vue/bootstrap-vue/issues/1798)
- **contributing:** Improve the commit guidelines
  ([c506280](https://github.com/bootstrap-vue/bootstrap-vue/commit/c506280af9acffb1d8978890e7efecca36042212))
- **dependencies:** replace opencollective with opencollective-postintall
  ([#2067](https://github.com/bootstrap-vue/bootstrap-vue/issues/2067))
  ([fa26882](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa26882686166a74621330bf658c0b9447a93590))
- **docs:** Button - typo ([#1962](https://github.com/bootstrap-vue/bootstrap-vue/issues/1962))
  ([dcbfcf9](https://github.com/bootstrap-vue/bootstrap-vue/commit/dcbfcf9a2de47f2c70486461e0716f9f79f03501))
- **docs:** change b-input-group attribute 'left' to 'prepend'
  ([#2017](https://github.com/bootstrap-vue/bootstrap-vue/issues/2017))
  ([d471502](https://github.com/bootstrap-vue/bootstrap-vue/commit/d471502e8e96b1bdc6581360c1960382b676adf3))
- **docs:** Collapse - typo fix
  ([#1964](https://github.com/bootstrap-vue/bootstrap-vue/issues/1964))
  ([becaa98](https://github.com/bootstrap-vue/bootstrap-vue/commit/becaa98558c56136a4cc3742708e5983f0376747))
- **docs:** Embed - Typos ([#1965](https://github.com/bootstrap-vue/bootstrap-vue/issues/1965))
  ([ae7101e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae7101edfcaf566ed648d7d534b85ff42c3a3a0a))
- **docs:** Fix broken examples
  ([1d599a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d599a56acd9003e7a1f2f9d4483e5dc1325cb91))
- **docs:** Fix console errors and improve `play` directive
  ([#2176](https://github.com/bootstrap-vue/bootstrap-vue/issues/2176))
  ([cc02130](https://github.com/bootstrap-vue/bootstrap-vue/commit/cc02130f6d45bdb391d6c34a79c435b1bb0f08ba))
- **docs:** Fix duplicate keys in events table
  ([#1786](https://github.com/bootstrap-vue/bootstrap-vue/issues/1786))
  ([fa60d56](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa60d56e812aedfa3506199dbaf7826cc521be60))
- **docs:** fix issue with playground export button and improved error catching
  ([#2197](https://github.com/bootstrap-vue/bootstrap-vue/issues/2197))
  ([c69ffbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/c69ffbc2f2f66f1a8a3df38fc0fe0c098450dc1d))
- **docs:** fix playground hang issues. fixes
  [#1843](https://github.com/bootstrap-vue/bootstrap-vue/issues/1843)
  ([#2177](https://github.com/bootstrap-vue/bootstrap-vue/issues/2177))
  ([5bdc2e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bdc2e63c615f653415a24b513b8ef1ec27a61df))
- **docs:** fix table refresh event name
  ([#1692](https://github.com/bootstrap-vue/bootstrap-vue/issues/1692))
  ([01e223c](https://github.com/bootstrap-vue/bootstrap-vue/commit/01e223caaae965234f14205c67505506768e9a3e))
- **docs:** fix typo in collapse events doc
  ([d8f5d69](https://github.com/bootstrap-vue/bootstrap-vue/commit/d8f5d694b64761120f3b4b230b1d3541bf4b0753))
- **docs:** fixes broken styling of docs navigation
  ([#1911](https://github.com/bootstrap-vue/bootstrap-vue/issues/1911))
  ([95a5012](https://github.com/bootstrap-vue/bootstrap-vue/commit/95a5012575b25b9594f3757512218b98156bc5a9))
- **docs:** improve CSS load ordering
  ([#2255](https://github.com/bootstrap-vue/bootstrap-vue/issues/2255))
  ([e193362](https://github.com/bootstrap-vue/bootstrap-vue/commit/e19336272a8a6a5fb04d28580a487f72e11d4fc8))
- **docs:** incorrect closing <b-form-file> tag
  ([#1838](https://github.com/bootstrap-vue/bootstrap-vue/issues/1838))
  ([69e410d](https://github.com/bootstrap-vue/bootstrap-vue/commit/69e410d204a31664f6f85e06f8a92f19e05ecb56))
- **docs:** input group prepend slot typo
  ([#2059](https://github.com/bootstrap-vue/bootstrap-vue/issues/2059))
  ([3c3cd8d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c3cd8d2683e6ecb8e50811ca0bf6cc3acd7e23a))
- **docs:** Layout - Typo ([#1966](https://github.com/bootstrap-vue/bootstrap-vue/issues/1966))
  ([c5a37d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/c5a37d3873fcbd73f11680dc12c2c85bbad54548))
- **docs:** missing dash and typo
  ([#1850](https://github.com/bootstrap-vue/bootstrap-vue/issues/1850))
  ([7b5fde8](https://github.com/bootstrap-vue/bootstrap-vue/commit/7b5fde8ea1a00373465f0d587ec834fbeaf61724))
- **docs:** Remove incorrect code added during debugging
  ([#1787](https://github.com/bootstrap-vue/bootstrap-vue/issues/1787))
  ([9911507](https://github.com/bootstrap-vue/bootstrap-vue/commit/99115074a1e57b7ccb7e8c4d31555749b5934c0a))
- **docs:** spelling correction in comment
  ([#1568](https://github.com/bootstrap-vue/bootstrap-vue/issues/1568))
  ([e0e4006](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0e40069b2e75514f07edcc6927bd358d34f9f0c))
- **docs:** typo ([#2009](https://github.com/bootstrap-vue/bootstrap-vue/issues/2009))
  ([9e0eb67](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e0eb677c3ebad0ea82f3837bccefe442f16c0de))
- **docs:** typo in docs plugin
  ([#1777](https://github.com/bootstrap-vue/bootstrap-vue/issues/1777))
  ([fb50c6f](https://github.com/bootstrap-vue/bootstrap-vue/commit/fb50c6f750be7a9363d147bf8e1ab9135892dbcb))
- **docs:** vue-loader v15 changes
  ([#2005](https://github.com/bootstrap-vue/bootstrap-vue/issues/2005))
  ([449a712](https://github.com/bootstrap-vue/bootstrap-vue/commit/449a7121928f394f912dad488e388f1dc78fc09f))
- **dropdown:** add missing TAB keyCode. closes
  [#1577](https://github.com/bootstrap-vue/bootstrap-vue/issues/1577)
  ([#2140](https://github.com/bootstrap-vue/bootstrap-vue/issues/2140))
  ([5e5c5c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e5c5c9a447bebde19460c38c21ebf36448c5bf2))
- **dropdown:** aria-labbeledby for dropdowns
  ([8efa7ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/8efa7ee3978bb2ee29b45d1c92465292174af4e4))
- **dropdown:** Item click event timing
  ([#2251](https://github.com/bootstrap-vue/bootstrap-vue/issues/2251))
  ([e620e07](https://github.com/bootstrap-vue/bootstrap-vue/commit/e620e07d1e15aba43cac0164f502f13672a7ebb7))
- **dropdown:** typo in README ([#1939](https://github.com/bootstrap-vue/bootstrap-vue/issues/1939))
  ([#1942](https://github.com/bootstrap-vue/bootstrap-vue/issues/1942))
  ([8a2ca5e](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a2ca5e607b4e3942a835dddd1a1db3d93a528d7))
- **dropdown:** Use custom CSS for `no-caret` option
  [#1473](https://github.com/bootstrap-vue/bootstrap-vue/issues/1473)
  ([#2136](https://github.com/bootstrap-vue/bootstrap-vue/issues/2136))
  ([2eb706f](https://github.com/bootstrap-vue/bootstrap-vue/commit/2eb706f65c1dbbe46223e9003fd06098c00b42e6))
- **dropdown-item-button:** Add support for `active` state
  ([#2212](https://github.com/bootstrap-vue/bootstrap-vue/issues/2212))
  ([4b9e6c0](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b9e6c01b1fb1466050b7708e414820a4dc4ac38))
- **dropdown, button, link:** various bug fixes and aria fixes (Fixes
  [#1814](https://github.com/bootstrap-vue/bootstrap-vue/issues/1814),[#1817](https://github.com/bootstrap-vue/bootstrap-vue/issues/1817))
  ([#2159](https://github.com/bootstrap-vue/bootstrap-vue/issues/2159))
  ([e79270d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e79270d623a606ed9fabea11af154002831da190))
- **fom-input:** revert changes from PR
  [#1841](https://github.com/bootstrap-vue/bootstrap-vue/issues/1841)
  ([#2174](https://github.com/bootstrap-vue/bootstrap-vue/issues/2174))
  ([aacc7c0](https://github.com/bootstrap-vue/bootstrap-vue/commit/aacc7c083e8b7d62f0cdb1142da349338fd46e29))
- **form-file:** Add prop to allow customization of browse button text. fixes
  [#2143](https://github.com/bootstrap-vue/bootstrap-vue/issues/2143)
  ([#2168](https://github.com/bootstrap-vue/bootstrap-vue/issues/2168))
  ([56c26da](https://github.com/bootstrap-vue/bootstrap-vue/commit/56c26dacd1a7fd9b6990db5225593f8de22efe19))
- **form-file:** fix drag and drop feature
  ([#2169](https://github.com/bootstrap-vue/bootstrap-vue/issues/2169))
  ([07bfc29](https://github.com/bootstrap-vue/bootstrap-vue/commit/07bfc29e641369c6ea385acc7f38e1a509173f2a))
- **form-file:** issue with "accept" values
  [fixes [#1526](https://github.com/bootstrap-vue/bootstrap-vue/issues/1526), reverts [#2028](https://github.com/bootstrap-vue/bootstrap-vue/issues/2028)](<[#2008](https://github.com/bootstrap-vue/bootstrap-vue/issues/2008)>)
  ([963d478](https://github.com/bootstrap-vue/bootstrap-vue/commit/963d4785e341ffc83ea79f0bba9e04afc302ed0f))
- **form-group:** add missing disabled prop
  ([#2106](https://github.com/bootstrap-vue/bootstrap-vue/issues/2106))
  ([4971c06](https://github.com/bootstrap-vue/bootstrap-vue/commit/4971c067817b8c4c3336111614ae9957dc603ee0)),
  closes [#1920](https://github.com/bootstrap-vue/bootstrap-vue/issues/1920)
- **form-group:** replace .col-form-legend with .col-form-label
  ([ac2d4dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ac2d4dd54ce9940b63457975cea949c541d76833))
- **id:** fixed check for \_uid in client side id generator
  ([#1499](https://github.com/bootstrap-vue/bootstrap-vue/issues/1499))
  ([f3fe0f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/f3fe0f468b6cf242bb2af41b9fee3d5a67db2197))
- **input-group:** fix dropdown rounded corners. closes
  [#1560](https://github.com/bootstrap-vue/bootstrap-vue/issues/1560).
  ([7df01ff](https://github.com/bootstrap-vue/bootstrap-vue/commit/7df01ff4dde2a934f287b7fa193ea97196cdcd99))
- **modal:** Correct the internal btn variable names
  ([301f2e4](https://github.com/bootstrap-vue/bootstrap-vue/commit/301f2e422864eb0b799a2dfdc8ef920393a6594f)),
  closes [#1650](https://github.com/bootstrap-vue/bootstrap-vue/issues/1650)
- **modal:** hide dropdown on click.
  ([#1528](https://github.com/bootstrap-vue/bootstrap-vue/issues/1528))
  ([3ad8a9a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ad8a9a8a23ae075f9115b61ec989f24d4cde577))
- **select:** Fix issues with form-select
  ([#1673](https://github.com/bootstrap-vue/bootstrap-vue/issues/1673))
  ([e3336c5](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3336c5636ad66dd0efbc1a8b1aa52e70fbd92d1)),
  closes [#1658](https://github.com/bootstrap-vue/bootstrap-vue/issues/1658)
- **tab:** fix the delay in tab transition
  ([#1812](https://github.com/bootstrap-vue/bootstrap-vue/issues/1812))
  ([#1806](https://github.com/bootstrap-vue/bootstrap-vue/issues/1806))
  ([5a7a290](https://github.com/bootstrap-vue/bootstrap-vue/commit/5a7a29002f3140162e597c76d98c0101a9ca3949))
- **tab:** typo aria-lablelledby
  ([#1959](https://github.com/bootstrap-vue/bootstrap-vue/issues/1959))
  ([5933955](https://github.com/bootstrap-vue/bootstrap-vue/commit/59339555070586a838cf8fb87a32638a3b25cb25)),
  closes [#954](https://github.com/bootstrap-vue/bootstrap-vue/issues/954)
- **table:** only call provider once DOM is fully updated
  ([#1904](https://github.com/bootstrap-vue/bootstrap-vue/issues/1904))
  ([#1955](https://github.com/bootstrap-vue/bootstrap-vue/issues/1955))
  ([ae7147e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae7147e34b7727fb28d7f6aa4a47ff0422484c59))
- typo corrected in tooltips ([#1930](https://github.com/bootstrap-vue/bootstrap-vue/issues/1930))
  ([5e4fbe4](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e4fbe40a7f85c612e46a7ccfc9f554cc1c2af75))
- typo in form-radio watcher ([#1943](https://github.com/bootstrap-vue/bootstrap-vue/issues/1943))
  ([9ab23ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ab23ef3642d545c91514809a98063a48a04d29c))
- **form-input:** allow readonly to be forced to false when plaintext is enabled
  ([#1841](https://github.com/bootstrap-vue/bootstrap-vue/issues/1841))
  ([b02a6ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/b02a6ee376681a16f898170d387c99d0af1291b3))
- **form-input:** always return formatted value
  ([#1839](https://github.com/bootstrap-vue/bootstrap-vue/issues/1839))
  ([77cc97b](https://github.com/bootstrap-vue/bootstrap-vue/commit/77cc97bf89d083603902288435e82183cf0bd534))
- **form-input:** bug fixes and add new features
  ([#2100](https://github.com/bootstrap-vue/bootstrap-vue/issues/2100))
  ([0299159](https://github.com/bootstrap-vue/bootstrap-vue/commit/02991599a087ce145e8409f3e1fb81875e579660))
- **form-input:** custom-range style adjustments
  ([#2122](https://github.com/bootstrap-vue/bootstrap-vue/issues/2122))
  ([1917c15](https://github.com/bootstrap-vue/bootstrap-vue/commit/1917c15b6fe2204e930df4555f685f4d5f7eb9f5))
- **form-input:** force update formatted value
  ([#1845](https://github.com/bootstrap-vue/bootstrap-vue/issues/1845))
  ([497cc6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/497cc6e39ab6872549c0b5884041719d4e25afec))
- **form-input:** revert step, min and max props
  ([#1767](https://github.com/bootstrap-vue/bootstrap-vue/issues/1767))
  ([1ce1a20](https://github.com/bootstrap-vue/bootstrap-vue/commit/1ce1a20b35cbcd385dd4327ced73e8cf0bbfcdb0))
- **form-state:** explicitly handle when state is set to empty string. fixes
  [#2166](https://github.com/bootstrap-vue/bootstrap-vue/issues/2166)
  ([#2167](https://github.com/bootstrap-vue/bootstrap-vue/issues/2167))
  ([805a7fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/805a7fe8d38f17cf03131a3a46d00fc0f1239d06))
- **img-lazy:** typo ([#1778](https://github.com/bootstrap-vue/bootstrap-vue/issues/1778))
  ([11d113c](https://github.com/bootstrap-vue/bootstrap-vue/commit/11d113cc93506bfb4803692f523b6e5cf1c784ff))
- **input-group:** Fix size styling issues for input types range and color
  ([3ba1230](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ba12309b242b5025afab4e4fb312576b1311405))
- **input-group:** Minor fixes and documentation update
  ([#2128](https://github.com/bootstrap-vue/bootstrap-vue/issues/2128))
  ([afe1cd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/afe1cd06091eb531fd24e31fc58f22e4925b0fc3))
- **input-group:** Styling fix for dropdowns, radio and checkbox groups. Fixes
  [#2114](https://github.com/bootstrap-vue/bootstrap-vue/issues/2114),[#1560](https://github.com/bootstrap-vue/bootstrap-vue/issues/1560)
  ([#2118](https://github.com/bootstrap-vue/bootstrap-vue/issues/2118))
  ([ed31bcd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed31bcde977e735e1b887c529afaf05ebe400333))
- **list-group-item:** set button type to 'button' when button in mode or tag=button (Fixes
  [#2192](https://github.com/bootstrap-vue/bootstrap-vue/issues/2192))
  ([#2194](https://github.com/bootstrap-vue/bootstrap-vue/issues/2194))
  ([4322ccb](https://github.com/bootstrap-vue/bootstrap-vue/commit/4322ccb800ac3886cf7b2b252ae7e8b22b73e7ee))
- **modal:** better enforce focus handler.
  ([#2215](https://github.com/bootstrap-vue/bootstrap-vue/issues/2215))
  ([9628de2](https://github.com/bootstrap-vue/bootstrap-vue/commit/9628de25577bc33cdcac6440a49b80415623084b))
- **modal:** clear modal paddingLeft and paddingRight if no Scrollbar(s) in adjustDialog().
  ([#2050](https://github.com/bootstrap-vue/bootstrap-vue/issues/2050))
  ([80f1d6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/80f1d6e927ebf6c86c84824df54f0f8b1e13d5ac))
- **modal:** Handle enforce focus when modals are stacked (Fixes
  [#2175](https://github.com/bootstrap-vue/bootstrap-vue/issues/2175))
  ([#2211](https://github.com/bootstrap-vue/bootstrap-vue/issues/2211))
  ([7d768d1](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d768d1ce12648050659a565e20cc69e2f8f4c7d))
- **modal:** prevent scrolling on .modal-content focus, fixes
  [#1748](https://github.com/bootstrap-vue/bootstrap-vue/issues/1748)
  ([#2060](https://github.com/bootstrap-vue/bootstrap-vue/issues/2060))
  ([df9efad](https://github.com/bootstrap-vue/bootstrap-vue/commit/df9efadbb51797918016fdc7fda8e5304c4e3682))
- **nav-item-dropdown:** close menu when clicked outside
  ([#2202](https://github.com/bootstrap-vue/bootstrap-vue/issues/2202))
  ([9e3e33e](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e3e33ea8484ae0cc6e972b53ac39f868674060b)),
  closes [#2198](https://github.com/bootstrap-vue/bootstrap-vue/issues/2198)
- **navbar:** Support always expanded navbar (fixes
  [#2209](https://github.com/bootstrap-vue/bootstrap-vue/issues/2209))
  ([#2210](https://github.com/bootstrap-vue/bootstrap-vue/issues/2210))
  ([7c3737c](https://github.com/bootstrap-vue/bootstrap-vue/commit/7c3737c2446683b2dd616e618b82358149bfde99))
- **observe-dom:** fix comment typo
  ([#2084](https://github.com/bootstrap-vue/bootstrap-vue/issues/2084))
  ([8b41913](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b419139f7f5111a7f5ac745450d5b5d0bdcae27))
- **popover:** Add directive to component plugin
  ([#2115](https://github.com/bootstrap-vue/bootstrap-vue/issues/2115))
  ([e39a855](https://github.com/bootstrap-vue/bootstrap-vue/commit/e39a8550f8a492dcc6ecc0e521f87e6a1b65589b))
- **popover:** fixes close emit argument
  ([#1937](https://github.com/bootstrap-vue/bootstrap-vue/issues/1937))
  ([8b9db28](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b9db28e5be1e96acd28bc4905e6a53aabc5c7c1))
- **safeId:** trigger id creation/update after mount (fixes
  [#1978](https://github.com/bootstrap-vue/bootstrap-vue/issues/1978))
  ([#2161](https://github.com/bootstrap-vue/bootstrap-vue/issues/2161))
  ([48218fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/48218fe7fd0dc78a7936608b11fd7f98a1dfc243))
- **scss:** import \_input-group.scss once at most
  ([#2239](https://github.com/bootstrap-vue/bootstrap-vue/issues/2239))
  ([2e7dcfa](https://github.com/bootstrap-vue/bootstrap-vue/commit/2e7dcfab5813e6712486798fe85f7fa2e3596659))
- **select:** Wait for the v-model value to update before emitting change event on form select
  ([#2207](https://github.com/bootstrap-vue/bootstrap-vue/issues/2207))
  ([7a860ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a860eeae5664dbc7560e58a8cce4adcd32f0241))
- **table:** Emit v-model input event only when computedItems changes (closes
  [#2231](https://github.com/bootstrap-vue/bootstrap-vue/issues/2231))
  ([#2254](https://github.com/bootstrap-vue/bootstrap-vue/issues/2254))
  ([f0fb9af](https://github.com/bootstrap-vue/bootstrap-vue/commit/f0fb9af0b4f2398addac1441574967a90aa6a747))
- **table:** fix aria-rowcount ([#1836](https://github.com/bootstrap-vue/bootstrap-vue/issues/1836))
  ([e3e5439](https://github.com/bootstrap-vue/bootstrap-vue/commit/e3e54395838261e296f92ab5baac635ba9f78803))
- **table:** fix filtered event, fix emptyFilter message w/filter function, fix reactivity of filter
  sub routines, fix empty header label accessibility issue (Fixes
  [#1989](https://github.com/bootstrap-vue/bootstrap-vue/issues/1989),[#1517](https://github.com/bootstrap-vue/bootstrap-vue/issues/1517))
  ([#2149](https://github.com/bootstrap-vue/bootstrap-vue/issues/2149))
  ([e0e1eee](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0e1eeef2a55348a52511f388baf70bc1a2df07b))
- **table:** import lodash.get from "dependencies"
  ([#1697](https://github.com/bootstrap-vue/bootstrap-vue/issues/1697))
  ([4d620a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/4d620a5e68acafd03abc157cad0ecf7353a52bd6))
- **table:** Preserve aria-rowcount and aria-describedby if provided. Fixes
  [#1801](https://github.com/bootstrap-vue/bootstrap-vue/issues/1801)
  ([#2195](https://github.com/bootstrap-vue/bootstrap-vue/issues/2195))
  ([e0cdca0](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0cdca08cbdaae34b5bab8e669194a7775eeacf5))
- **table:** return empty string if cell value is null or undefined. Fixes
  [#1502](https://github.com/bootstrap-vue/bootstrap-vue/issues/1502)
  ([#2139](https://github.com/bootstrap-vue/bootstrap-vue/issues/2139))
  ([b62f8f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/b62f8f4d311fbb234cbb8f131a8a0df2b600a739))
- **table:** typo in README.md ([#1729](https://github.com/bootstrap-vue/bootstrap-vue/issues/1729))
  ([8d0e186](https://github.com/bootstrap-vue/bootstrap-vue/commit/8d0e1863124d779e8de38364ad283b7221129a94))
- **tabs:** change default key nav to avoid breaking changes
  ([#1733](https://github.com/bootstrap-vue/bootstrap-vue/issues/1733))
  ([a6dea02](https://github.com/bootstrap-vue/bootstrap-vue/commit/a6dea0236e1912b02792a6720d0a61bae1693e0a))
- **tabs:** typo in tabs ([#1735](https://github.com/bootstrap-vue/bootstrap-vue/issues/1735))
  ([89eff3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/89eff3c90f861215b9b92dd30d89cea15efe58bd))
- **tooltip:** typo in comment ([#1779](https://github.com/bootstrap-vue/bootstrap-vue/issues/1779))
  ([ef253f7](https://github.com/bootstrap-vue/bootstrap-vue/commit/ef253f7affcad451766dd57b55d6b16901c1e353))
- default export in TypeScript definitions
  ([cd7e310](https://github.com/bootstrap-vue/bootstrap-vue/commit/cd7e310f9ba9117b5c97ed51567cc7ebff732c52))
- **tabs:** rename prop to no-key-nav, update docs
  ([491d698](https://github.com/bootstrap-vue/bootstrap-vue/commit/491d698e0d2347f0b650fccb3122f008a16e1d1f))
- **text-area:** input event ([#1714](https://github.com/bootstrap-vue/bootstrap-vue/issues/1714))
  ([5e2973d](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e2973de2b70b4943e332fae80f10ee748966332))
- **toolpop mixin:** allow boundary type to be HTMLElement (Fixes
  [#2229](https://github.com/bootstrap-vue/bootstrap-vue/issues/2229))
  ([#2233](https://github.com/bootstrap-vue/bootstrap-vue/issues/2233))
  ([8b8272b](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b8272bad45585389989064aa11e1fd622237493))
- **tooltip:** Add directive to component plugin
  ([#2116](https://github.com/bootstrap-vue/bootstrap-vue/issues/2116))
  ([e5bb09e](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5bb09e5dc62e09538a344f535d321921d5d3532))
- **utils/loose-equal:** check dates in looseEqual util
  ([#2123](https://github.com/bootstrap-vue/bootstrap-vue/issues/2123))
  ([8a8d0f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a8d0f07b9f941d55254b30f68c95d84d0ebc2e6))
- call `removeEventListener` on the right element
  ([#1557](https://github.com/bootstrap-vue/bootstrap-vue/issues/1557))
  ([cf2bfca](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf2bfca67411833805e6094c614854d56ff30787)),
  closes [#1391](https://github.com/bootstrap-vue/bootstrap-vue/issues/1391)
- polyfill HTMLElement for SSR
  ([d4dd9b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4dd9b386907b0b35639a6e2ce20ab77d9e5e416))
- **button:** allow custom size classes to be passed to the size prop
  ([#1389](https://github.com/bootstrap-vue/bootstrap-vue/issues/1389))
  ([41a46b2](https://github.com/bootstrap-vue/bootstrap-vue/commit/41a46b28ef4ff184ca5d198c06b43e8e820f488c))
- **button:** allow custom size classes to be passed to the size prop
  ([#1389](https://github.com/bootstrap-vue/bootstrap-vue/issues/1389))
  ([96fb934](https://github.com/bootstrap-vue/bootstrap-vue/commit/96fb934d378e10a94533b78792ec42f8ebdc82fc))
- **button-close:** switch to slots() from children
  ([#1345](https://github.com/bootstrap-vue/bootstrap-vue/issues/1345))
  ([9c997b7](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c997b765430ab94bcbca4ccf10ecc0bcc4245e2))
- **carousel:** clear timers on beforeDestroy
  ([fa1c083](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa1c083cad4495d6020b9363aaceaab1f084bd25))
- **carousel:** clear timers on beforeDestroy
  ([53ea1b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/53ea1b4ae61618af5de4cf4c3098e41a88b80b0e))
- **carousel:** remove un-needed `aria-` atribute on slides
  ([#1448](https://github.com/bootstrap-vue/bootstrap-vue/issues/1448))
  ([260919f](https://github.com/bootstrap-vue/bootstrap-vue/commit/260919f30c46efdc2b162931d155c042c2d31d59))
- **carousel:** uncaught typeerror on empty slides.
  ([#1401](https://github.com/bootstrap-vue/bootstrap-vue/issues/1401))
  ([cadae79](https://github.com/bootstrap-vue/bootstrap-vue/commit/cadae7928c40e444d785b7bc317024473d700748))
- **carousel:** uncaught typeerror on empty slides.
  ([#1401](https://github.com/bootstrap-vue/bootstrap-vue/issues/1401))
  ([a2ee9b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2ee9b6498d655e4bf92b261453ce4dcade0e499))
- **ci:** auto deploy docs from master branch
  ([22e432d](https://github.com/bootstrap-vue/bootstrap-vue/commit/22e432d972a67638ec9111675333c934e6b0ff1b))
- **docs play:** prevent duplicate key errors in console output
  ([#1476](https://github.com/bootstrap-vue/bootstrap-vue/issues/1476))
  ([68deee1](https://github.com/bootstrap-vue/bootstrap-vue/commit/68deee1a90a2360396f9b58efc51a7d1cabb5ef1))
- **dropdown:** fix condition for when position-static is applied
  ([#1477](https://github.com/bootstrap-vue/bootstrap-vue/issues/1477))
  ([1717edb](https://github.com/bootstrap-vue/bootstrap-vue/commit/1717edbda6f4c581111342f4fb66e06ce058021a))
- **dropdown:** fixed aria-labbeledby for non-split dropdowns
  ([d597dbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/d597dbce683928246eaf3cf6e386f63b6c9f157b))
- **dropdown:** prevent toggle click from closing in collapsed navbar
  ([#1475](https://github.com/bootstrap-vue/bootstrap-vue/issues/1475))
  ([24ef1e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/24ef1e6b2a94981d302da3a05ed790a9b46afa32)),
  closes [#1474](https://github.com/bootstrap-vue/bootstrap-vue/issues/1474)
- **dropdown:** use class `position-static` instead of inline style
  ([#1451](https://github.com/bootstrap-vue/bootstrap-vue/issues/1451))
  ([fc49325](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc493259aee8fd0f4a806c69a3844e63b80ede3a))
- **dropdowns:** prevent memory leak on destroy
  ([#1392](https://github.com/bootstrap-vue/bootstrap-vue/issues/1392))
  ([839418e](https://github.com/bootstrap-vue/bootstrap-vue/commit/839418ee666c44b3b56d20e28fb1e98f170ea0a1)),
  closes [#1391](https://github.com/bootstrap-vue/bootstrap-vue/issues/1391)
- **dropdowns:** prevent memory leak on destroy
  ([#1392](https://github.com/bootstrap-vue/bootstrap-vue/issues/1392))
  ([05a5c50](https://github.com/bootstrap-vue/bootstrap-vue/commit/05a5c504a61eba9b5b87bdc254283523f10acbaf)),
  closes [#1391](https://github.com/bootstrap-vue/bootstrap-vue/issues/1391)
- **form-file:** invalid/valid feedback display for plain file input missing in Bootstrap V4
  ([#1373](https://github.com/bootstrap-vue/bootstrap-vue/issues/1373))
  ([85ab0d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/85ab0d0b418559d36cd693d235167e933a3d906e))
- **form-group:** import b-form-row directly from layout
  ([8dcce39](https://github.com/bootstrap-vue/bootstrap-vue/commit/8dcce39e670cbdd0401cb0ff5ebe7b098bf3c8df))
- **form-group:** import b-form-row directly from layout
  ([b43d7c8](https://github.com/bootstrap-vue/bootstrap-vue/commit/b43d7c836d23c5d126428b37325adf355f968afa))
- **form-radio-group:** prepare for bootstrap V4.beta.3
  ([39eb237](https://github.com/bootstrap-vue/bootstrap-vue/commit/39eb2377b78886f22e547e509d999524e7ed4f27))
- **form-radio-group:** prepare for bootstrap V4.beta.3
  ([5b659d1](https://github.com/bootstrap-vue/bootstrap-vue/commit/5b659d17ecb4aeaed5d9a0a4e3940de61c8a8a29))
- **form-textarea:** initial value population
  ([#1370](https://github.com/bootstrap-vue/bootstrap-vue/issues/1370))
  ([a08a46e](https://github.com/bootstrap-vue/bootstrap-vue/commit/a08a46e661b5bcae5a3266299c91d66bd65ca014)),
  closes [#1368](https://github.com/bootstrap-vue/bootstrap-vue/issues/1368)
- **form-textarea:** monitor localValue instead of value when calculating lines
  ([9f3439f](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f3439f870f8281536d27eb86a9933813a31e25b))
- **id mixin:** set prop type to String
  ([9a6eaa5](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a6eaa5f40047e72a7d66f8f04169885fa003b33))
- **id mixin:** set prop type to String
  ([37ab5cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/37ab5cbf78f848a7d09e5b541568334ab377013e))
- **link:** restore original tabindex when not disabled
  ([cfdf0b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/cfdf0b98b3d5961cfa056455056c2f983a62979e))
- **link:** take link out of tab sequence if disabled
  ([#1347](https://github.com/bootstrap-vue/bootstrap-vue/issues/1347))
  ([360588a](https://github.com/bootstrap-vue/bootstrap-vue/commit/360588aa4aa4011a0cc90141801ad4c778aa45fe))
- **list-group:** disabled button items
  ([#1444](https://github.com/bootstrap-vue/bootstrap-vue/issues/1444))
  ([c037b38](https://github.com/bootstrap-vue/bootstrap-vue/commit/c037b381ae44e6d89b073a6fc9417aba99394219))
- **modal:** modal-open body class lost when switching between modals
  ([#1327](https://github.com/bootstrap-vue/bootstrap-vue/issues/1327))
  ([99e146f](https://github.com/bootstrap-vue/bootstrap-vue/commit/99e146f34c6a99ecb9ee2dacff40b88b8cf7cb43)),
  closes [#1325](https://github.com/bootstrap-vue/bootstrap-vue/issues/1325)
- **modal:** rounded-top class no longer needed when header variant applied
  ([#1433](https://github.com/bootstrap-vue/bootstrap-vue/issues/1433))
  ([ecf1bf5](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecf1bf508f945a996cabb91f3efb9aeffa2e6c90))
- **modal:** update centered modal margins to align with BSV4.beta.3 update
  ([f7e80a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/f7e80a8fcd11c5c970e11d74cb94d5042867a0f8))
- **table:** better custom css specificity for when nesting tables
  ([7acccb9](https://github.com/bootstrap-vue/bootstrap-vue/commit/7acccb990d8c1115b0c22274c30d9df4d641a6cd))
- **table:** better custom css specificity for when nesting tables
  ([4a2d121](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a2d12103496397667d596ca1fa873b1d8f810d3))
- **table:** correct fixd-top row scoped slot properties
  ([debf8e2](https://github.com/bootstrap-vue/bootstrap-vue/commit/debf8e2ee3111a0f0c223820887cb11fb46783d1))
- **table:** correct fixd-top row scoped slot properties
  ([7e042f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/7e042f140fa08d5cf3792ac7537698fcf57c1b5c))
- **table:** fix outlined table
  ([e81b107](https://github.com/bootstrap-vue/bootstrap-vue/commit/e81b107e5a12a3a42e0d4c4cf91fc2105baa1c02))
- **table:** initial busy of true always makes table busy
  ([#1400](https://github.com/bootstrap-vue/bootstrap-vue/issues/1400))
  ([029e4d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/029e4d0876fcc8cb8fd4dc613f148edc37bbe325)),
  closes [#1398](https://github.com/bootstrap-vue/bootstrap-vue/issues/1398)
- **table:** initial busy of true always makes table busy
  ([#1400](https://github.com/bootstrap-vue/bootstrap-vue/issues/1400))
  ([5daa0df](https://github.com/bootstrap-vue/bootstrap-vue/commit/5daa0df1426487a024339634619fee99798b5265)),
  closes [#1398](https://github.com/bootstrap-vue/bootstrap-vue/issues/1398)
- **table:** use stable sort algorithm to prevent SSR issues
  ([#1399](https://github.com/bootstrap-vue/bootstrap-vue/issues/1399))
  ([21b33f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/21b33f2e5e6d127380027ff3cd118512636dcd09))
- **table:** use stable sort algorithm to prevent SSR issues
  ([#1399](https://github.com/bootstrap-vue/bootstrap-vue/issues/1399))
  ([552c438](https://github.com/bootstrap-vue/bootstrap-vue/commit/552c438ed8a7cc10726a1d82f77e1e9bbfaa37a4))
- **tooltip+popover:** auto-append to `.modal-content` instead of `.modal`
  ([#1465](https://github.com/bootstrap-vue/bootstrap-vue/issues/1465))
  ([b53715c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b53715c78eab38faab839ff25d607a7f9e1e733d)),
  closes [#1464](https://github.com/bootstrap-vue/bootstrap-vue/issues/1464)
- detach clickout listener in beforeDestroy
  ([b290cad](https://github.com/bootstrap-vue/bootstrap-vue/commit/b290cad0c0f4fbff9c1dab6bdcee6dfa933c1359))
- detach clickout listener in beforeDestroy
  ([89618de](https://github.com/bootstrap-vue/bootstrap-vue/commit/89618de14f68fc9b3f930463ecdade01a73356e0))
- remove listenOnRoot handlers in beforeDestroy
  ([e594490](https://github.com/bootstrap-vue/bootstrap-vue/commit/e594490a58c332cfda3ffc56b666c545e99f307d))
- remove listenOnRoot handlers in beforeDestroy
  ([7f7eba1](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f7eba1f814202ad3200653d7f252a3ab100a0f8))
- SFC transpilation in es buld ([#1410](https://github.com/bootstrap-vue/bootstrap-vue/issues/1410))
  ([3ef9572](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ef95723d7c1d2bda5635013216630fc35fe13ce))
- SFC transpilation in es buld ([#1410](https://github.com/bootstrap-vue/bootstrap-vue/issues/1410))
  ([ce80809](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce8080936e803031585b2b9437509587624d46cc))
- **build:** use esm bundle. resolves
  [#1296](https://github.com/bootstrap-vue/bootstrap-vue/issues/1296).
  ([06d40a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/06d40a54b61f6bdd118ab2fd4c87be072e860034))
- **button:** Don't ovrwrite user supplied tabindex if not disabled
  ([#1120](https://github.com/bootstrap-vue/bootstrap-vue/issues/1120))
  ([18f5129](https://github.com/bootstrap-vue/bootstrap-vue/commit/18f512916c41965c1e388a84c541ed1362de57fb)),
  closes [#1119](https://github.com/bootstrap-vue/bootstrap-vue/issues/1119)
- **button-close:** Hardcode &times; character to prevent SSR bailing
  ([b0dd1ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0dd1ba175dad8456f931a84973c214375f9a7e7))
- **button-group:** Bootstrap V4.beta.2 CSS changes
  ([1b4618f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b4618f29dc70022b607c23002f5cff7b49d5ced))
- **carousel:** Minor adjustments to fousout/mouseout event handler
  ([#1239](https://github.com/bootstrap-vue/bootstrap-vue/issues/1239))
  ([330b70b](https://github.com/bootstrap-vue/bootstrap-vue/commit/330b70ba2361b49bbeebb238eed842d4a2a30f1e))
- **docs:** Homepage link to changelog
  ([2dd229d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dd229d679d24e8ca8e6ac736563fceac6898f52))
- **docs:** Move TOC generation inside export
  ([1267207](https://github.com/bootstrap-vue/bootstrap-vue/commit/12672079c023ecfb32fb2f9056cf87ac489173ef))
- **docs:** popover directive's broken link
  ([#1116](https://github.com/bootstrap-vue/bootstrap-vue/issues/1116))
  ([201e926](https://github.com/bootstrap-vue/bootstrap-vue/commit/201e926258acf18c85821e535796f71e9177cc73))
- **docs:** typo in Modal docs ([#1092](https://github.com/bootstrap-vue/bootstrap-vue/issues/1092))
  ([051034b](https://github.com/bootstrap-vue/bootstrap-vue/commit/051034ba3a06239d7a34ed908353afb39f6abc44))
- **dom utils:** use getBoundingClientRect() to determine element visibility
  ([#1203](https://github.com/bootstrap-vue/bootstrap-vue/issues/1203))
  ([6e2fff4](https://github.com/bootstrap-vue/bootstrap-vue/commit/6e2fff489b716fcddd4aeb0ce3a01b3f1f1e251c))
- **dropdown:** Bootstrap V4.beta.2 now has better hover/focus styling
  ([#1224](https://github.com/bootstrap-vue/bootstrap-vue/issues/1224))
  ([0b8bc67](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b8bc67f8f4726fe1bd289f001da5639dc1269ba))
- **form-check+radio mixin:** pull state from parent group
  ([6845014](https://github.com/bootstrap-vue/bootstrap-vue/commit/68450143623c7e4bdd82959f6ea769c53d25b3d7))
- **form-checkbox:** apply form state class to hidden inputs
  ([710369c](https://github.com/bootstrap-vue/bootstrap-vue/commit/710369c9f061ca9d5a7d9e7d95c36f7c9a7be7b9))
- **form-checkbox-group:** Changes to button styles
  ([431eb02](https://github.com/bootstrap-vue/bootstrap-vue/commit/431eb0229a73017e99de5d1fda5a145008455eac))
- **form-checkbox-group:** Import b-form-checkbox
  ([09187ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/09187ead52ae3c4c781584593167a6a6c3d487f5))
- **form-file:** control size not supported in BS V4
  ([#1305](https://github.com/bootstrap-vue/bootstrap-vue/issues/1305))
  ([e9a26cf](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9a26cff7fe3e16ffe75accff78e763564e8223d)),
  closes [#1304](https://github.com/bootstrap-vue/bootstrap-vue/issues/1304)
- **form-file:** Focus styling tweaks
  ([c3bc583](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3bc5839aab91f39238fd4eb0f89abb059ed7867))
- **form-input:** BS V4.beta.2 is missing width:100% on readonly plaintext
  ([#1225](https://github.com/bootstrap-vue/bootstrap-vue/issues/1225))
  ([c37cef4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c37cef4989e2e10c7ce8ee956d5d1ba0b7fce293))
- **form-options:** Handle object special cases
  ([#1099](https://github.com/bootstrap-vue/bootstrap-vue/issues/1099))
  ([1b17df3](https://github.com/bootstrap-vue/bootstrap-vue/commit/1b17df39fe441ed55d54b77d4eb4ebe96392d223))
- **form-radio:** apply form state to hidden input element
  ([3074ecc](https://github.com/bootstrap-vue/bootstrap-vue/commit/3074ecc2dd9bb4e7c7dddf05536e947197fe2fab))
- **form-radio-group:** Add support for Boolean value
  ([4cafb27](https://github.com/bootstrap-vue/bootstrap-vue/commit/4cafb27c63a6969b397eda0b6f9cead9e26dd59f))
- **form-radio-group:** Allow number type for checked
  ([#1089](https://github.com/bootstrap-vue/bootstrap-vue/issues/1089))
  ([8eccdbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/8eccdbc0ec540f1088a496bda564f0025d28ddb0))
- **form-radio-group:** Changes to button styles
  ([063e9d8](https://github.com/bootstrap-vue/bootstrap-vue/commit/063e9d84ae68666aba02f70a8f71a6dcf29c944a))
- **form-radio-group:** Import b-form-radio
  ([82bb078](https://github.com/bootstrap-vue/bootstrap-vue/commit/82bb078883ab94b873fa1815b5d3cd2c5da82267))
- **form-select:** Custom select now supports multiple attribute in V4.beta.2 CSS
  ([#1223](https://github.com/bootstrap-vue/bootstrap-vue/issues/1223))
  ([3a4262d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a4262d8dfd52663c53680fb383145ad3f6074f2))
- **img-lazy:** alt tag was being removed when image loaded
  ([f2fb99c](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2fb99c5e418543869d6611f201fc240d284b722))
- **input-group:** BS V4.beta CSS no longer has the `has-${state}` classes
  ([#1155](https://github.com/bootstrap-vue/bootstrap-vue/issues/1155))
  ([9f4df16](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f4df169078dd543248deab741746cbdd24ee5ef))
- **input-group:** correct input-group right addon via prop
  ([#1317](https://github.com/bootstrap-vue/bootstrap-vue/issues/1317))
  ([061abc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/061abc5ed90d523b8d164780e9bfe965caefd133))
- **link:** Only set attribute aria-disabled when disabled
  ([fe2c340](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe2c34046ea7e320f652afe6646debf5947f4512))
- **link:** working href with router-link on ssr
  ([8a6f243](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a6f243f4174587888c65c360678a1fd9e74a2e9))
- **modal:** Add outer wrapper div to that lazy modal's will still have a $ref when hidden
  ([#1186](https://github.com/bootstrap-vue/bootstrap-vue/issues/1186))
  ([7f7e6a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/7f7e6a72fb1c1d69830d9fc52579d4b6dcf6dd95))
- **modal:** Ensure body scrollbar is removed if modal destroyed before being closed
  ([#1168](https://github.com/bootstrap-vue/bootstrap-vue/issues/1168))
  ([e0a4444](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0a4444ab04008f78e162b86ee22801b676f71b7))
- **modal:** Modal jumps when dialog height changes
  ([#1182](https://github.com/bootstrap-vue/bootstrap-vue/issues/1182))
  ([126fe95](https://github.com/bootstrap-vue/bootstrap-vue/commit/126fe950e1fdb72024e332b65f3ecf5d07c3864c)),
  closes [#1058](https://github.com/bootstrap-vue/bootstrap-vue/issues/1058)
- **nav-item-dropdown:** fix disabled in toggleClasses
  ([#1123](https://github.com/bootstrap-vue/bootstrap-vue/issues/1123))
  ([aabc54d](https://github.com/bootstrap-vue/bootstrap-vue/commit/aabc54d213fff57814f3f78a874c28d63d05de83))
- **nuxt module:** wrong relative path to package.json
  ([#1298](https://github.com/bootstrap-vue/bootstrap-vue/issues/1298))
  ([e766e75](https://github.com/bootstrap-vue/bootstrap-vue/commit/e766e75163252b69de7a802b4e30ddc2205bdebb))
- **package.json:** Move Bootstrap back to devDep and update popper.js version
  ([#1228](https://github.com/bootstrap-vue/bootstrap-vue/issues/1228))
  ([87cfab4](https://github.com/bootstrap-vue/bootstrap-vue/commit/87cfab479ab8a9681462070c1a83a3f3bf8e2de1))
- **pagination-nav:** ARIA tabing control
  ([92d0810](https://github.com/bootstrap-vue/bootstrap-vue/commit/92d08102a32345c124bc72bfc4a08fe730d49e3e))
- **popover+tooltip:** content not restored after hiding all popovers with 'bv::hide::popover'
  ([#1323](https://github.com/bootstrap-vue/bootstrap-vue/issues/1323))
  ([94488c6](https://github.com/bootstrap-vue/bootstrap-vue/commit/94488c690a746bc958d5884e552bfa43d75a2e17)),
  closes [#1322](https://github.com/bootstrap-vue/bootstrap-vue/issues/1322)
- **progress:** Apply height style correctly
  ([675c1c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/675c1c999bb205c7538793b7c3167946fcacdbbb))
- **progress:** Bootstrap V4.beta.2 missing progress bar transition
  ([1f1064f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1f1064f26fd2b052500ffbed2f68d2cf3c2193f1))
- **Progress:** Bootstrap V4.beta.2 CSS height prop change
  ([#1217](https://github.com/bootstrap-vue/bootstrap-vue/issues/1217))
  ([a963ea3](https://github.com/bootstrap-vue/bootstrap-vue/commit/a963ea33dab46e4009c740f072f09eee6c5f9ade)),
  closes [#1216](https://github.com/bootstrap-vue/bootstrap-vue/issues/1216)
- **scrollspy:** Minor CSS selector update
  ([0b58a69](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b58a691f5190e29a8526594333875a58b6bb88f))
- **scrollspy:** typo
  ([ec36379](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec3637939381f54b682d483a4cbf63b8ba5e43b3))
- **search+toc:** Make search and TOC generation work with SSR
  ([#1091](https://github.com/bootstrap-vue/bootstrap-vue/issues/1091))
  ([51db684](https://github.com/bootstrap-vue/bootstrap-vue/commit/51db68482236b0b6dd39fe1cc432469b60e101b0))
- **table:** Don't startcase field label when label explicitly given
  ([76a511f](https://github.com/bootstrap-vue/bootstrap-vue/commit/76a511f91083396b741c562ff26daa2da0e57ab4))
- **tabs:** Apply `small` class to parent `ul.nav`
  ([#1255](https://github.com/bootstrap-vue/bootstrap-vue/issues/1255))
  ([42f8a78](https://github.com/bootstrap-vue/bootstrap-vue/commit/42f8a7813a9185cc32c2bdc1bbcb313607ab435a)),
  closes [#1248](https://github.com/bootstrap-vue/bootstrap-vue/issues/1248)
- **tabs:** lazy prop regression
  ([#1372](https://github.com/bootstrap-vue/bootstrap-vue/issues/1372))
  ([844cd81](https://github.com/bootstrap-vue/bootstrap-vue/commit/844cd81c42edceba48a403d43f50dad875750d3c)),
  closes [#1371](https://github.com/bootstrap-vue/bootstrap-vue/issues/1371)
- Remove spacing between stacked buttons style
  ([554e54a](https://github.com/bootstrap-vue/bootstrap-vue/commit/554e54a5eb12153665ba8e8054135357e2e9b40d))
- **alert:** Emit dismiss-count-down at 0 seconds
  ([#839](https://github.com/bootstrap-vue/bootstrap-vue/issues/839))
  ([8dc90bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/8dc90bb628d91a284858cea65c8e40d694b2463b))
- **alert:** Fix auto-dimissing alert "bug"
  ([#897](https://github.com/bootstrap-vue/bootstrap-vue/issues/897))
  ([eccd63e](https://github.com/bootstrap-vue/bootstrap-vue/commit/eccd63e81f77387f8e570f4a6fd723c7aff9ce44))
- **alert:** show dismiss button when dismissible is true
  ([590cead](https://github.com/bootstrap-vue/bootstrap-vue/commit/590ceadbc4695b7ddaacf2b4848ad92835e8b8d3))
- **b-col:** handle bool style prop for sm,md,lg,xl
  ([#1042](https://github.com/bootstrap-vue/bootstrap-vue/issues/1042))
  ([3e7e17d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3e7e17df76b4712090772c568cf5ebebca0d7274)),
  closes [#1041](https://github.com/bootstrap-vue/bootstrap-vue/issues/1041)
- **badge:** Default variant changed
  ([8d3be9e](https://github.com/bootstrap-vue/bootstrap-vue/commit/8d3be9ec4e1e6541e96792a9a081b75e46e69249))
- **badge:** Default variant no longer exists in V4.beta
  ([#875](https://github.com/bootstrap-vue/bootstrap-vue/issues/875))
  ([5fc14d2](https://github.com/bootstrap-vue/bootstrap-vue/commit/5fc14d231eeaa02206e9504fa83d59da4f19195f))
- **carousel:** Handle older opera oTransitionEnd event
  ([#899](https://github.com/bootstrap-vue/bootstrap-vue/issues/899))
  ([5afb591](https://github.com/bootstrap-vue/bootstrap-vue/commit/5afb591f87e59db38a54087516a444d09e891939))
- **carousel:** Prevent reflow trigger from being optimised out
  ([#995](https://github.com/bootstrap-vue/bootstrap-vue/issues/995))
  ([d765976](https://github.com/bootstrap-vue/bootstrap-vue/commit/d765976d7286c0379f31d1f2209b787cb1704617))
- **carousel:** Typo in transition
  ([9693872](https://github.com/bootstrap-vue/bootstrap-vue/commit/96938725f9c0cdcfd978b5f770e55a0530564fd2))
- **coursel:** Ensure minimum interval of 1 second
  ([467ec27](https://github.com/bootstrap-vue/bootstrap-vue/commit/467ec2723503b2c91b48fb613c9b67cc30ecc97c))
- **docs:** Adjust source link if component is a functional component
  ([9cc07a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/9cc07a71b3f6335a5a901756c24657cffea9977d))
- **docs:** b-img fluid-grow example
  ([fe32515](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe325159478a5c20e449a8e422b8adcb08303b9d))
- **docs:** feedback doc in form group
  ([#934](https://github.com/bootstrap-vue/bootstrap-vue/issues/934))
  ([45881bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/45881bbaa61bc2819dbc20cf1cf699fda214371d))
- **docs:** Fix examples in b-img
  ([7607a00](https://github.com/bootstrap-vue/bootstrap-vue/commit/7607a003965f3559938c6573d612bf2848570fa3))
- **docs:** Fix modal-cancel slot name in meta.json
  ([a8772ac](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8772ac385568d299599a55940436e67f1c1354b))
- **docs:** Fix multipe collapse example
  ([65ba276](https://github.com/bootstrap-vue/bootstrap-vue/commit/65ba276899b5b0cd1ed4909c57d1d55e20656215))
- **docs:** Fix reference to modal-cancel slot in modal docs
  ([5747c6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/5747c6dcdac14f32725a864b11f2a97906ee3655))
- **docs:** Side bar navigation not accessible on small screens
  ([#946](https://github.com/bootstrap-vue/bootstrap-vue/issues/946))
  ([4666b37](https://github.com/bootstrap-vue/bootstrap-vue/commit/4666b372019d2c739c797bb8e0dbfb701aba4feb)),
  closes [#948](https://github.com/bootstrap-vue/bootstrap-vue/issues/948)
- **dropdown:** hover/focus shading for active items
  ([b2b6ad9](https://github.com/bootstrap-vue/bootstrap-vue/commit/b2b6ad9853adc030dc1d8b57d0a7094c9fb27894))
- **dropdown:** remove custom hover styling
  ([9c9c3bb](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c9c3bb414006a05c920871653279a75272291c4))
- **dropdown.js:** import clickout as a mixin
  ([#896](https://github.com/bootstrap-vue/bootstrap-vue/issues/896))
  ([1ba47e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/1ba47e53846c41765229db2a24869fe70b16890c))
- **dropdowns:** Allow gracefull fallback if Popper.js not defined
  ([#920](https://github.com/bootstrap-vue/bootstrap-vue/issues/920))
  ([41b5947](https://github.com/bootstrap-vue/bootstrap-vue/commit/41b59478b06ac2e88ef5e6da9b6634e945329f02))
- **dropdowns:** Migration to popper.js positioning
  ([#913](https://github.com/bootstrap-vue/bootstrap-vue/issues/913))
  ([116cb3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/116cb3e19d52c636f0c3a9d38d887a72788a4a48))
- **dropdowns:** Minor code update & comments
  ([54a2546](https://github.com/bootstrap-vue/bootstrap-vue/commit/54a2546792059a1ef68d3fd7a2682c52a8c0ada1))
- **embed:** Validate type prop
  ([993116b](https://github.com/bootstrap-vue/bootstrap-vue/commit/993116b9609f109f9d3fa0c04782ee188477cb47))
- **form-file:** Selected file name(s) not always showing
  ([565b0ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/565b0aba0e015ae4b7fd943cf931d32c545fe90c))
- **form-group:** Not applying label-for prop value
  ([#1000](https://github.com/bootstrap-vue/bootstrap-vue/issues/1000))
  ([56a4e5e](https://github.com/bootstrap-vue/bootstrap-vue/commit/56a4e5ed4430da89af27456512eb7ddd2d42d3e9))
- **form-group:** use new prop labelCols over old computedLabelCols
  ([#878](https://github.com/bootstrap-vue/bootstrap-vue/issues/878))
  ([b6aa317](https://github.com/bootstrap-vue/bootstrap-vue/commit/b6aa3173248947293c3d548b1987ebe34317b8b8))
- **form-input:** use :value instead of v-model
  ([fcff25d](https://github.com/bootstrap-vue/bootstrap-vue/commit/fcff25d73bfb9e7ed284f271575e04fd84597437))
- **form-textarea:** correct CSS value for no resize
  ([b9bff5e](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9bff5e890ddba11d2e7a8ed1632c5fd4910d9c7))
- **form-textarea:** Fix value reactivity
  ([aeb11be](https://github.com/bootstrap-vue/bootstrap-vue/commit/aeb11be9e26903263f95d5c28948561f5e7753a8))
- **form-textarea:** Max rows not respected if rows specified
  ([4762471](https://github.com/bootstrap-vue/bootstrap-vue/commit/4762471526d4b7dea9e1e242918c211d4034e8f5))
- **form-textarea:** not respecting rows when max-rows provided
  ([e8bf4b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8bf4b38aecabd0fd715cca4829a0caeb642dc25))
- **form-textarea:** Set width to 100% if in plaintext mode
  ([01735e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/01735e68d791987a57f0e662e8fba7a944e8bd33))
- **forms:** Adjustments to form-textarea and form-input
  ([#880](https://github.com/bootstrap-vue/bootstrap-vue/issues/880))
  ([79a7aa8](https://github.com/bootstrap-vue/bootstrap-vue/commit/79a7aa8fdc5d5bb13b4bc5adaa7c4322e628a386))
- **forms:** BS4.beta form/input validation styles & components
  ([#847](https://github.com/bootstrap-vue/bootstrap-vue/issues/847))
  ([00e2b6f](https://github.com/bootstrap-vue/bootstrap-vue/commit/00e2b6ff0afd18d291b6db17e836facfadef9f72))
- **jumbotron:** Accept string or number for header-level
  ([ff223a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff223a816bcf64c85fb246301f977e39f8b7e9e1))
- **lform-group:** Missing return in target ID selection
  ([3323531](https://github.com/bootstrap-vue/bootstrap-vue/commit/332353183f6e111a4d2c447c26f0856d195d06d4))
- **link:** clear router-link/href collision and remove old link mixin
  ([#1016](https://github.com/bootstrap-vue/bootstrap-vue/issues/1016))
  ([ed381f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed381f4b49f06d3d08ad08758dc3d6db77b34fcb)),
  closes [#1018](https://github.com/bootstrap-vue/bootstrap-vue/issues/1018)
  [#1013](https://github.com/bootstrap-vue/bootstrap-vue/issues/1013)
  [#1017](https://github.com/bootstrap-vue/bootstrap-vue/issues/1017)
  [#940](https://github.com/bootstrap-vue/bootstrap-vue/issues/940)
- **link:** default href to null
  ([716ce45](https://github.com/bootstrap-vue/bootstrap-vue/commit/716ce45d55fcbf42055672779ee007e09a30e100))
- **link:** ensure target is vue component before #emit
  ([200f31b](https://github.com/bootstrap-vue/bootstrap-vue/commit/200f31b0072ac2f2005639fb4dc966dc2057d4e7))
- **link:** if nothing is provided default href to #
  ([86533fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/86533fae037a99d20342e402f68b47ce42115397))
- **modal:** Fix aria hidden attr and observeDom target element
  ([f099ac7](https://github.com/bootstrap-vue/bootstrap-vue/commit/f099ac702468d7546028ce77e7271c70be4f2441))
- **modal:** fix issue with lazy loading
  ([7557f52](https://github.com/bootstrap-vue/bootstrap-vue/commit/7557f52c188bed0ea8889788a5e758f438a54c40))
- **modal:** Minor bug fixes
  ([6cfc682](https://github.com/bootstrap-vue/bootstrap-vue/commit/6cfc68271aab567a67e5d0c4f238e0bb9f76d02e))
- **nav-dropdown:** Fix right alignment in <b-nav>
  ([#962](https://github.com/bootstrap-vue/bootstrap-vue/issues/962))
  ([9598763](https://github.com/bootstrap-vue/bootstrap-vue/commit/95987631e3edca90879021aebc8d01d706a3944f))
- **nav-item-dropdown:** Fix focus/hover custom CSS
  ([e38576c](https://github.com/bootstrap-vue/bootstrap-vue/commit/e38576c057ecadc22734b6d6099570dd179bfe70))
- **nav-item-dropdown:** hover/focus shading for active items
  ([5bd2b23](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bd2b23b8fb3d6a5fa3deee08f08e78ad1393c1c))
- **nav-item-dropdown:** remove custom hover styling
  ([c794fef](https://github.com/bootstrap-vue/bootstrap-vue/commit/c794fef209605900ca6326298d1d24019f3977e6))
- **nav-toggle:** Use new namespaced collape events
  ([6f87c23](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f87c23006fa608d7f26f86c7902c1b8a421fff8))
- **navbar:** breakpoint control
  ([72cd58d](https://github.com/bootstrap-vue/bootstrap-vue/commit/72cd58d0d843799e74f26cf0a95d25046384beba))
- **navbar:** breakpoint not working
  ([42ca902](https://github.com/bootstrap-vue/bootstrap-vue/commit/42ca902c153eff1c43acd7aa8c855410b7f42883))
- **navbar-brand:** fix pluckProps call for link
  ([9dadfbc](https://github.com/bootstrap-vue/bootstrap-vue/commit/9dadfbc45028b46c9fc1ac2b5410e2762298d0a5))
- **object mixin:** Add polyfill Object.is for IE
  ([beed2c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/beed2c3d1f4f50eb2128d1e7f8d157515b92dd91))
- **observedom:** Adjustments to mutation type detection
  ([75e92d3](https://github.com/bootstrap-vue/bootstrap-vue/commit/75e92d3355c72ea10b7a4b6e4a1ad4a2e5a07d84))
- **observedom:** Callback not being called for changes other than childList changes
  ([#1025](https://github.com/bootstrap-vue/bootstrap-vue/issues/1025))
  ([88cfaef](https://github.com/bootstrap-vue/bootstrap-vue/commit/88cfaefb096f0539ad6ea0632eeb56b9b8d6f0de))
- **observedom:** Callback not being called for changes other than node inert/remove
  ([92ef7eb](https://github.com/bootstrap-vue/bootstrap-vue/commit/92ef7eb997763bcf5643e70fb75bf293a6e9f365))
- **pagination:** Change classes from .hidden-_ to .d-_
  ([#840](https://github.com/bootstrap-vue/bootstrap-vue/issues/840))
  ([0f543a1](https://github.com/bootstrap-vue/bootstrap-vue/commit/0f543a1fcea6de64a52f70ab38a4b576dfe54511))
- **pagination-nav:** Fix link-gen and page-gen
  ([6746cb1](https://github.com/bootstrap-vue/bootstrap-vue/commit/6746cb1fc4c5569ee21c434aadc929984bc15f8a))
- **pagination-nav:** Update v-model on click
  ([188adea](https://github.com/bootstrap-vue/bootstrap-vue/commit/188adea57cbc9ec8bfecf1f700790b5c694320d1))
- **popove:** tooltip import
  ([8a75d10](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a75d10b4727eb942ab0d1691e4574dda3424890))
- **popover:** getting title from title attribute
  ([685de6a](https://github.com/bootstrap-vue/bootstrap-vue/commit/685de6aea634a38f00f52515da177168d55e5245))
- **popover:** remove deprecated target-id prop
  ([472fa79](https://github.com/bootstrap-vue/bootstrap-vue/commit/472fa79e86339d20e1dd4fb89fbfa2048f4eca35))
- **popover:** Remove old tether popover mixin
  ([#947](https://github.com/bootstrap-vue/bootstrap-vue/issues/947))
  ([e500836](https://github.com/bootstrap-vue/bootstrap-vue/commit/e5008361869411e64d99396732ba000d6960f9d4))
- **popover+tooltip:** Allow indiviual component imports
  ([#999](https://github.com/bootstrap-vue/bootstrap-vue/issues/999))
  ([dcc7504](https://github.com/bootstrap-vue/bootstrap-vue/commit/dcc7504c8015db70eb1fd5352438aa3bb97ea7ef))
- **progress:** make progress-bar respect parent show-\* props
  ([9fc726d](https://github.com/bootstrap-vue/bootstrap-vue/commit/9fc726d51f176648451da360f97e4f06af849341))
- **progress-bar:** aria-valuenow fix
  ([f0b486e](https://github.com/bootstrap-vue/bootstrap-vue/commit/f0b486e1954321ede8850c20de7d16b66bba00ff))
- **progress-bar:** Minor adjutment to style calculation
  ([14819ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/14819efe6a5e5650f1d473ee4648c158a76988ea))
- **progress-bar:** remove unessesary this in template
  ([c04df8c](https://github.com/bootstrap-vue/bootstrap-vue/commit/c04df8c068f6ec0ebf3f9e6b51a44becc0e685dd))
- **radios checkboxes:** Parent group should emit change event
  ([#1071](https://github.com/bootstrap-vue/bootstrap-vue/issues/1071))
  ([ac7c506](https://github.com/bootstrap-vue/bootstrap-vue/commit/ac7c506ff74e1b94120c0ec2cfbfb953feeec315))
- **scrollspy:** fixes ffor various bugs
  ([#1063](https://github.com/bootstrap-vue/bootstrap-vue/issues/1063))
  ([97fccdd](https://github.com/bootstrap-vue/bootstrap-vue/commit/97fccdd116cf332d82cfbceebdfd3adf7c54803a))
- **scrollspy:** Handle .nav-link inside .nav-item active state
  ([6db094d](https://github.com/bootstrap-vue/bootstrap-vue/commit/6db094d30ead62238b233aac127c2c772ce39f71))
- **scrollspy:** Handle nested nav-links when inside nav-item
  ([#1068](https://github.com/bootstrap-vue/bootstrap-vue/issues/1068))
  ([f4e017c](https://github.com/bootstrap-vue/bootstrap-vue/commit/f4e017ca9dc47c3f09805e39882d8971c2d45b2d))
- **scrollspy:** Make work with new nav-link functional component
  ([#909](https://github.com/bootstrap-vue/bootstrap-vue/issues/909))
  ([2ebba5d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2ebba5d90cf09bfe1454f742bff2de16fbb65df8))
- **scrollspy:** Minor updates
  ([95f0840](https://github.com/bootstrap-vue/bootstrap-vue/commit/95f08400621682218100c851c4d4a7a071331e8a))
- **scrollspy:** Minor updates
  ([ce15b69](https://github.com/bootstrap-vue/bootstrap-vue/commit/ce15b69873d48aeedbd325573492fce3444226d8))
- **scrollspy:** Trigger refresh on transitionend event
  ([947b5e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/947b5e0facff2239a538a31c72546b1c388adf60))
- **scrollspy:** Undefined value during bind()
  ([#967](https://github.com/bootstrap-vue/bootstrap-vue/issues/967))
  ([5c35e07](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c35e079ec36e85549d5402762e84a78f33fb48a))
- **scrollspy:** Use new offset and position dom utilities
  ([dc68eef](https://github.com/bootstrap-vue/bootstrap-vue/commit/dc68eef97d5d7dbcbf1af93d2787bcb02a6723b0))
- **table:** filtered event not firing when filter cleared (issue
  [#859](https://github.com/bootstrap-vue/bootstrap-vue/issues/859))
  ([#863](https://github.com/bootstrap-vue/bootstrap-vue/issues/863))
  ([8ff2623](https://github.com/bootstrap-vue/bootstrap-vue/commit/8ff2623208eabf493e4590b8cc4e3353fe3eb19f))
- **table:** fix for row-hovered event
  ([2448666](https://github.com/bootstrap-vue/bootstrap-vue/commit/2448666487c4fb66d4ed2e9fb58db5014ee4ab0c))
- **tabs:** Better handling of active tab and transitions
  ([#903](https://github.com/bootstrap-vue/bootstrap-vue/issues/903))
  ([d5b81dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/d5b81dd9be766998a81430d5e6e0b4fc93df5fad))
- **tabs:** minor logic update
  ([add0fb6](https://github.com/bootstrap-vue/bootstrap-vue/commit/add0fb6185d056aac473e002f133c2af704f2f63))
- **tabs:** Show first tab when set to active
  ([#912](https://github.com/bootstrap-vue/bootstrap-vue/issues/912))
  ([d920b1c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d920b1c0f134d579fd1963defa66b0d5d7b79253))
- **tolltip+popover:** Hide original element title attribute
  ([#970](https://github.com/bootstrap-vue/bootstrap-vue/issues/970))
  ([82e46e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/82e46e64ce8ddc9a72ac6242b9a82cca392f2585)),
  closes [#955](https://github.com/bootstrap-vue/bootstrap-vue/issues/955)
- **tooltip:** remove deprecated target-id prop
  ([a06d5a6](https://github.com/bootstrap-vue/bootstrap-vue/commit/a06d5a613ee1feaaaf3b7b538c8fd5c53f995d47))
- **tooltip:** ToolTip.fixTransition undefined value
  ([#960](https://github.com/bootstrap-vue/bootstrap-vue/issues/960))
  ([3c457e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c457e7e8618dc320449605aea7a7ae41c8497cd)),
  closes [#956](https://github.com/bootstrap-vue/bootstrap-vue/issues/956)
- **tooltip popover:** illegal invocation errors when tooltip inside v-if elements
  ([#1057](https://github.com/bootstrap-vue/bootstrap-vue/issues/1057))
  ([c1353a7](https://github.com/bootstrap-vue/bootstrap-vue/commit/c1353a74c4e651487bbeab30be52b9748db559aa)),
  closes [#1032](https://github.com/bootstrap-vue/bootstrap-vue/issues/1032)
- Add lodash.startcase to dependancies
  ([febecfc](https://github.com/bootstrap-vue/bootstrap-vue/commit/febecfceb5207c191c7373598d3d76d4a5750010))
- **alert:** add missing colon for binding `aria-label`
  ([#768](https://github.com/bootstrap-vue/bootstrap-vue/issues/768))
  ([93b009f](https://github.com/bootstrap-vue/bootstrap-vue/commit/93b009fe65a610730767046e4b974b4ca0eac8c1))
- **alert:** Event args array in meta.json
  ([c9e3fd2](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9e3fd2a4808f2224520063f31289bff47f6813a))
- **alert:** use v-model to update show value
  ([#721](https://github.com/bootstrap-vue/bootstrap-vue/issues/721))
  ([9b380d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b380d076842187db1e0173db60da179109ae8ef))
- **badge:** badge default variant
  ([1403ec4](https://github.com/bootstrap-vue/bootstrap-vue/commit/1403ec402603329b815cc3acb3d739c3da7b18ea))
- **button:** Minor code update
  ([378b932](https://github.com/bootstrap-vue/bootstrap-vue/commit/378b93221e336fda809b768afe61d3d5fe77fcaf))
- **button-toolbar:** keynav better element visibility test
  ([5c33b8e](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c33b8e3f1e8c875d7e9b6af326cf5abf566fb6e))
- **button-toolbar:** Typo on property `keyNav`
  ([#600](https://github.com/bootstrap-vue/bootstrap-vue/issues/600))
  ([60b1fd8](https://github.com/bootstrap-vue/bootstrap-vue/commit/60b1fd8b75760fd1d0acaecdcca12bfbd5cffabc))
- **card:** change prop no-block to no-body
  ([#826](https://github.com/bootstrap-vue/bootstrap-vue/issues/826))
  ([664bc98](https://github.com/bootstrap-vue/bootstrap-vue/commit/664bc9814f51163c71e417684728faa843eb7430))
- **card:** Fix classes, variants, borders
  [v4-beta](<[#815](https://github.com/bootstrap-vue/bootstrap-vue/issues/815)>)
  ([fc26811](https://github.com/bootstrap-vue/bootstrap-vue/commit/fc26811b7f7c3eec9b28f5a409a7aff12cb83082))
- **carousel:** boolean typo
  ([6a95410](https://github.com/bootstrap-vue/bootstrap-vue/commit/6a954102d13550bbf96a9c2a34f9c8e8d094ae76))
- **carousel:** Detect transitionend event name
  ([fa07949](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa0794919f54b94e5c114cf881d8da85317496bb))
- **carousel:** Ensure slideshow restarts when reaching the end
  ([e175c36](https://github.com/bootstrap-vue/bootstrap-vue/commit/e175c36599b8918db7bd79655737386f9770fc8f))
- **carousel:** ESLint
  ([8222222](https://github.com/bootstrap-vue/bootstrap-vue/commit/822222260d3928084db4ef587748afcdb94c921a))
- **carousel:** Handle changes in slide content
  ([#809](https://github.com/bootstrap-vue/bootstrap-vue/issues/809))
  ([6949e5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6949e5f764a0f0b3637257be908e92146224e763))
- **carousel:** minor fixes
  ([6b4f497](https://github.com/bootstrap-vue/bootstrap-vue/commit/6b4f49790645af89aced04b2dc904f770d26268e))
- **carousel:** oldVal!
  ([3ae2e2e](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ae2e2eb9ae40d7d203c8d40d67cb315fb2fe3de))
- **carousel:** Prevent going to slide if transitioning (issue
  [#764](https://github.com/bootstrap-vue/bootstrap-vue/issues/764))
  ([#765](https://github.com/bootstrap-vue/bootstrap-vue/issues/765))
  ([a2ab664](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2ab664a564353ac403888887aec1c18038d3d14))
- **carousel:** Typo
  ([4c80576](https://github.com/bootstrap-vue/bootstrap-vue/commit/4c80576eff2432d1ff0f428384aff740c01ce5ad))
- **carousel:** Unable to reach last slide
  ([3628bcb](https://github.com/bootstrap-vue/bootstrap-vue/commit/3628bcbaecf10d2e86d6677c82b7fbab27b3c0df))
- **collapse:** Close collapse when clicked in navbar
  ([#803](https://github.com/bootstrap-vue/bootstrap-vue/issues/803))
  ([3fdfbff](https://github.com/bootstrap-vue/bootstrap-vue/commit/3fdfbff8dd70573b9ee33acce2a47540a813fcaa))
- **collapse:** reference to this.$el
  ([eb01295](https://github.com/bootstrap-vue/bootstrap-vue/commit/eb012959ea220fbfedadf82f7a632ae5719c020a))
- **componentdoc:** Typo in required prop
  ([762d088](https://github.com/bootstrap-vue/bootstrap-vue/commit/762d08858e9825ea62cc5210e7ed1ac9f57967dc))
- **docs:** add root wrapper to templates
  ([ff6432d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ff6432d2b1bfca7dad80152ad1363544d863de23))
- **docs:** Adjust header tags CSS specificity (issue
  [#753](https://github.com/bootstrap-vue/bootstrap-vue/issues/753))
  ([#755](https://github.com/bootstrap-vue/bootstrap-vue/issues/755))
  ([25280ae](https://github.com/bootstrap-vue/bootstrap-vue/commit/25280ae280127d7d69d12d770b8e4aa6958b27cc))
- **docs:** broken setup page
  ([9d60069](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d600698d2972dda0bf0e2c81676dd465a662707))
- **docs:** button update example
  ([#804](https://github.com/bootstrap-vue/bootstrap-vue/issues/804))
  ([fb375aa](https://github.com/bootstrap-vue/bootstrap-vue/commit/fb375aaf60fae17364b54f57730a688eb6045828))
- **docs:** Collapse meta.jso typo fix
  ([6191bed](https://github.com/bootstrap-vue/bootstrap-vue/commit/6191bed13b8245a8235c12138743585436c25ad4))
- **docs:** conform args and fix spelling
  ([#659](https://github.com/bootstrap-vue/bootstrap-vue/issues/659))
  ([ed9906a](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed9906ad9940a59d08fb158a1a952f24584d2159))
- **docs:** fix invalid JSON trailing commas
  ([a635176](https://github.com/bootstrap-vue/bootstrap-vue/commit/a63517644a4d9c4a7ca29b4d00f4d238c0bafc98))
- **docs:** Fix ScrollSpy example
  ([0365208](https://github.com/bootstrap-vue/bootstrap-vue/commit/036520815640bdb3f005f93ca0ade571867b5ba1))
- **docs:** Fix typo in \_component.vue
  ([b90e92a](https://github.com/bootstrap-vue/bootstrap-vue/commit/b90e92a0a1ebf0b6a84da772f7a5724e26680b13))
- **docs:** form-radio typo fix
  ([db6d5d7](https://github.com/bootstrap-vue/bootstrap-vue/commit/db6d5d7d92042e01c125395cf8249fa4ff67c6af))
- **docs:** form-select docs typo fix
  ([630e02f](https://github.com/bootstrap-vue/bootstrap-vue/commit/630e02fae24c5ce152cc8107cac10eba558d3358))
- **docs:** Minor update to file-input example
  ([763a35a](https://github.com/bootstrap-vue/bootstrap-vue/commit/763a35a4669eedc27bd3c5ebae21edadeddde4f0))
- **docs:** Minor update to navbar example
  ([4a62e1b](https://github.com/bootstrap-vue/bootstrap-vue/commit/4a62e1bcb48c7055fc36495f6b03954b5ed30c58))
- **docs:** myToggle0
  ([a0ef988](https://github.com/bootstrap-vue/bootstrap-vue/commit/a0ef988f9d6d06f8140db97d4197f33a41af98f0))
- **docs:** serve fonts on https
  ([51209dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/51209dd9cc8b0a9d4d5d7a39e6faa57c6a183b18))
- **docs:** table example markup
  ([d3d7437](https://github.com/bootstrap-vue/bootstrap-vue/commit/d3d74371b392e5da527f1c37525c16af81114a5c))
- **docs:** typo in button docs
  ([8cd3ea1](https://github.com/bootstrap-vue/bootstrap-vue/commit/8cd3ea17b14bd875e301c192405d7a92b5a1c0f8))
- **docs:** update README.md for Bootstrap version
  ([#692](https://github.com/bootstrap-vue/bootstrap-vue/issues/692))
  ([5165531](https://github.com/bootstrap-vue/bootstrap-vue/commit/516553105f32edb86e2d5d8529560f275a938e7c))
- **docs.vue:** Fix link to edit setup doc
  ([#641](https://github.com/bootstrap-vue/bootstrap-vue/issues/641))
  ([836db33](https://github.com/bootstrap-vue/bootstrap-vue/commit/836db334861846006a7d0cbf1498dc0e14d5be42)),
  closes [#639](https://github.com/bootstrap-vue/bootstrap-vue/issues/639)
- **dropdown:** Clear leftover active state on menu open (fixes
  [#664](https://github.com/bootstrap-vue/bootstrap-vue/issues/664))
  ([80c1ceb](https://github.com/bootstrap-vue/bootstrap-vue/commit/80c1cebd001f6c109c386c3589c5fe7b6781dc0f))
- **dropdown:** Emit shown and hidden events (issue
  [#757](https://github.com/bootstrap-vue/bootstrap-vue/issues/757))
  ([814e94c](https://github.com/bootstrap-vue/bootstrap-vue/commit/814e94c1cd2bdb71c610d36751ae4aa123a5ba23))
- **dropdown:** Fix focus/hover custom CSS
  ([0cbbfb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/0cbbfb5ae436eaf8cba0817212d2750820e94b39))
- **dropdown:** focus on first item on show
  ([40a1347](https://github.com/bootstrap-vue/bootstrap-vue/commit/40a13474682fdaf729d3279f4ece478b37a62321))
- **dropdown:** twbs/bootstrap[#23329](https://github.com/bootstrap-vue/bootstrap-vue/issues/23329)
  ([fab5d22](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab5d2291f8fdfba19058f76b165ea05d275582f))
- **dropdowns:** Change how dropdown items are highlighted
  ([#717](https://github.com/bootstrap-vue/bootstrap-vue/issues/717))
  ([a02270e](https://github.com/bootstrap-vue/bootstrap-vue/commit/a02270ef2d27b21c419b5e8a9906fce2d884d7cc))
- **dropdowns:** Focus dropdown item on hover
  ([#823](https://github.com/bootstrap-vue/bootstrap-vue/issues/823))
  ([2e863d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/2e863d9296ff409a69c0f8dabcc28153e4efdaf7))
- **form:** Emit native submit on component
  ([#636](https://github.com/bootstrap-vue/bootstrap-vue/issues/636))
  ([0ba6f94](https://github.com/bootstrap-vue/bootstrap-vue/commit/0ba6f94ae91f2dc24f73e5243def7d8183700ae4)),
  closes [#588](https://github.com/bootstrap-vue/bootstrap-vue/issues/588)
- **form controls:** Apply only required props & classes
  ([#609](https://github.com/bootstrap-vue/bootstrap-vue/issues/609))
  ([c773f79](https://github.com/bootstrap-vue/bootstrap-vue/commit/c773f7991bdd432eeb2cff4a9b4d11042b30efd4))
- **form fieldset:** 'label for' prop not being applied to label - ARIA
  ([#669](https://github.com/bootstrap-vue/bootstrap-vue/issues/669))
  ([aafea81](https://github.com/bootstrap-vue/bootstrap-vue/commit/aafea81676adabdc3fd0a633658481e596f1c667))
- **form-checkbox:** Better focus handling in button mode
  ([06e1c7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/06e1c7bb895983a30288e24441da4f7ab654bc39))
- **form-checkbox:** Remove duplicate computed prop
  ([f47ab79](https://github.com/bootstrap-vue/bootstrap-vue/commit/f47ab794c7afc7294faa5b479fd00a9e4c60af17))
- **form-control-static:** change class to form-control-plaintext
  ([66eda01](https://github.com/bootstrap-vue/bootstrap-vue/commit/66eda01a74477e6710d78e18c02755b95dfa3b09))
- **form-file:** remove inputClass
  ([2415617](https://github.com/bootstrap-vue/bootstrap-vue/commit/24156177890d40277e9a14086df79be937880a38))
- **form-input:** Fix reactivity (issue
  [#817](https://github.com/bootstrap-vue/bootstrap-vue/issues/817))
  ([88e2dbb](https://github.com/bootstrap-vue/bootstrap-vue/commit/88e2dbbd78e2c0651d688fe1eb9abff93e2f806d))
- **form-input:** isTextArea varname correction
  ([#785](https://github.com/bootstrap-vue/bootstrap-vue/issues/785))
  ([cb44652](https://github.com/bootstrap-vue/bootstrap-vue/commit/cb44652f2e49b6399bd12cb31b1575f94922b666))
- **form-options:** pull out custom text field for object notation
  ([#625](https://github.com/bootstrap-vue/bootstrap-vue/issues/625))
  ([83cec54](https://github.com/bootstrap-vue/bootstrap-vue/commit/83cec5463818261ad13d5514e8d3357f24cd3b22)),
  closes [#622](https://github.com/bootstrap-vue/bootstrap-vue/issues/622)
- **form-radio:** Add missing classes in button mode
  ([#779](https://github.com/bootstrap-vue/bootstrap-vue/issues/779))
  ([ed4f4ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed4f4ef80b9ac0d7bab06998be65b672cd89f3b5))
- **form-radio:** Better focus handling in button mode
  ([#801](https://github.com/bootstrap-vue/bootstrap-vue/issues/801))
  ([a9bfbde](https://github.com/bootstrap-vue/bootstrap-vue/commit/a9bfbde2f666d9cbb7e20deb256fefbe1fa23423))
- **form-radio:** extra this in template
  ([cc4a442](https://github.com/bootstrap-vue/bootstrap-vue/commit/cc4a4421e07eaa00ad71d38327d445c8de269d0f))
- **form-radio:** isChecked to work with arrays & non-arrays.
  ([#629](https://github.com/bootstrap-vue/bootstrap-vue/issues/629))
  ([578d451](https://github.com/bootstrap-vue/bootstrap-vue/commit/578d451b820b502013c96e492c1ca01a32b7fc6a)),
  closes [#623](https://github.com/bootstrap-vue/bootstrap-vue/issues/623)
- **form-radio, form-checkbox:** Set autocomplete off
  ([#616](https://github.com/bootstrap-vue/bootstrap-vue/issues/616))
  ([e127313](https://github.com/bootstrap-vue/bootstrap-vue/commit/e127313e4c07403a160486bba9665380f93cbc7d))
- **modal:** Event args list in meta.json
  ([7b8ce01](https://github.com/bootstrap-vue/bootstrap-vue/commit/7b8ce0162e8bd4a35e3822a4c6b811aa7bc047f0))
- **modal:** meta.json property order consistency
  ([3d204a4](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d204a41ddc51c808d3557963e7018508a008c0e))
- **modal:** use listenOnRoot mixin
  ([#593](https://github.com/bootstrap-vue/bootstrap-vue/issues/593))
  ([531a6ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/531a6abff10b346079e84c9a0642ed1f83418ef1))
- **nav-item-dropdown:** add show class
  ([921dac5](https://github.com/bootstrap-vue/bootstrap-vue/commit/921dac5d7991529d1d855e9f4b88157914d5c029))
- **nav-toggle:** typo in method name
  ([5e0bb2a](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e0bb2abda48784664839e9b50a1cc97c1069b1d))
- **navbar-brand:** Refactored component logic
  ([#759](https://github.com/bootstrap-vue/bootstrap-vue/issues/759))
  ([c752fc8](https://github.com/bootstrap-vue/bootstrap-vue/commit/c752fc83c367a63e0c573ddc716ac58096d86a29))
- **navbar-brand:** Removed erroneous this in template
  ([#806](https://github.com/bootstrap-vue/bootstrap-vue/issues/806))
  ([0842043](https://github.com/bootstrap-vue/bootstrap-vue/commit/084204349863822cdabd66a7d7c07b07fdf989ab))
- **pagination:** Added missing href & ARIA adjustments
  ([#693](https://github.com/bootstrap-vue/bootstrap-vue/issues/693))
  ([7091262](https://github.com/bootstrap-vue/bootstrap-vue/commit/7091262e3cc757e0cb72a4d00472084d3aead91c))
- **pagination:** Improved ARIA roles and attributes
  ([#741](https://github.com/bootstrap-vue/bootstrap-vue/issues/741))
  ([b12b06e](https://github.com/bootstrap-vue/bootstrap-vue/commit/b12b06edb0fe349ff2aed6e1e76ca965d8e0ce45))
- **popover.js:** destroy check for trigger & classes (issue
  [#735](https://github.com/bootstrap-vue/bootstrap-vue/issues/735))
  ([30fa778](https://github.com/bootstrap-vue/bootstrap-vue/commit/30fa7789378d1d9943ba9bba94d79dff3141c15d))
- **root-listeners:** apply listen-on-root mixin to other components
  ([#684](https://github.com/bootstrap-vue/bootstrap-vue/issues/684))
  ([f2b7b44](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2b7b44a08d6ca8b8878b06b00dc430fce2d0836))
- **scrollspy:** Adjust throttle default
  ([3d6eb98](https://github.com/bootstrap-vue/bootstrap-vue/commit/3d6eb980a4cac0d2cac5d740ac4599140675669c))
- **scrollspy:** Adjustments to the resizeThrottle scheduler
  ([#640](https://github.com/bootstrap-vue/bootstrap-vue/issues/640))
  ([bfaef7d](https://github.com/bootstrap-vue/bootstrap-vue/commit/bfaef7d7d578d5c99249786c902edc4f0181a7e3))
- **table:** aria-labeledby set to header element
  ([e13e093](https://github.com/bootstrap-vue/bootstrap-vue/commit/e13e093624f6659f9e500e3ca9cdb20a2eb893a3))
- **table:** Remove redundant ARIA roles from b-table
  ([#662](https://github.com/bootstrap-vue/bootstrap-vue/issues/662))
  ([6919cc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/6919cc5a026f1168df5ea29d98aed3d01e40afce))
- **table:** Sorting directions & arrows
  ([de1de97](https://github.com/bootstrap-vue/bootstrap-vue/commit/de1de97e8b7b4d0f99546fce9e39f790244934d7))
- **table:** workaround for Vue 2.4 SSR rendering bug
  ([ab7767f](https://github.com/bootstrap-vue/bootstrap-vue/commit/ab7767f689a6c2b17b38ff350a448f6c888806b8))
- **table:** workaround for Vue 2.4 SSR rendering bug
  ([dc8d238](https://github.com/bootstrap-vue/bootstrap-vue/commit/dc8d23898d52a839fd3bad9ac1631b00026feb9b))
- **table demo.html:** remove deprecated fieldset prop
  ([#630](https://github.com/bootstrap-vue/bootstrap-vue/issues/630))
  ([18e8547](https://github.com/bootstrap-vue/bootstrap-vue/commit/18e85477576769b4dd564b02ffd55adb1fb70303))
- **tabs:** Default current tab to null (issue
  [#687](https://github.com/bootstrap-vue/bootstrap-vue/issues/687))
  ([#701](https://github.com/bootstrap-vue/bootstrap-vue/issues/701))
  ([bc7ca26](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc7ca26a71316b17d537b6b69d6dc58542f6d7f9))
- **tabs:** Remove aria-expanded in favor of aria-seleted
  ([5790b39](https://github.com/bootstrap-vue/bootstrap-vue/commit/5790b39bb8f470300026a294f097db01ae1cf073))
- **tabs:** Tabls not clickable (issue
  [#789](https://github.com/bootstrap-vue/bootstrap-vue/issues/789))
  ([#790](https://github.com/bootstrap-vue/bootstrap-vue/issues/790))
  ([c234580](https://github.com/bootstrap-vue/bootstrap-vue/commit/c2345805245b2b485bd282919064feef6a6238df))
- **tabs:** update to use card-block
  ([d881c37](https://github.com/bootstrap-vue/bootstrap-vue/commit/d881c379db18f2026e6f2bb3e1f229d961965f47))
- **tests:** Set jest max workers to 1
  ([f16fd8d](https://github.com/bootstrap-vue/bootstrap-vue/commit/f16fd8deef6ce922ffb68b0c227a572fbe4d15cf))
- **toggle:** Remove $root listener on unbind (Issue
  [#680](https://github.com/bootstrap-vue/bootstrap-vue/issues/680))
  ([#698](https://github.com/bootstrap-vue/bootstrap-vue/issues/698))
  ([ec5000c](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec5000c0eca49df98b0399c90f5a6d57145247bb))
- **tooltip:** Emit correct $root event name
  ([#1094](https://github.com/bootstrap-vue/bootstrap-vue/issues/1094))
  ([87e5eb2](https://github.com/bootstrap-vue/bootstrap-vue/commit/87e5eb29e889f4910cf34e77f65e467ddb6f200c))
- **tooltip:** visibility check
  ([df4a015](https://github.com/bootstrap-vue/bootstrap-vue/commit/df4a0159fd4f2b3c274d580196994a2a688e68bb))
- **tooltip-popover:** Click not triggered for elements with inner HTML elements in Chrome
  ([#1006](https://github.com/bootstrap-vue/bootstrap-vue/issues/1006))
  ([39caf8a](https://github.com/bootstrap-vue/bootstrap-vue/commit/39caf8ad40c80e2e350a4b92de3104b8d135115f)),
  closes [#1005](https://github.com/bootstrap-vue/bootstrap-vue/issues/1005)
- **tooltip+popover:** Check if trigger element is in DOM during vsibility check
  ([55c4ff0](https://github.com/bootstrap-vue/bootstrap-vue/commit/55c4ff03a8994ddb273923d02f577935fb8d7480))
- **tooltip+popover:** Hide tooltip/popover when $route changes
  ([#965](https://github.com/bootstrap-vue/bootstrap-vue/issues/965))
  ([e403225](https://github.com/bootstrap-vue/bootstrap-vue/commit/e403225194161d9ce71e349e6d84508093549eb6)),
  closes [#964](https://github.com/bootstrap-vue/bootstrap-vue/issues/964)
- **tooltip+popover:** Remove relatedTarget on hidden event object
  ([8af36ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/8af36ba2d29a71dfb2e08553eee03f8753748f97))
- Remove usage of es2015 Array.prototype.includes
  ([#589](https://github.com/bootstrap-vue/bootstrap-vue/issues/589))
  ([b3fc095](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3fc0950f907ef9bbcac6a92c6be1d5aec2af0dd))
- this is not defined in props
  ([fe4ff06](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe4ff063fb505a0277e5cb10e93bfec54e2b9723))
- **tooltip:** inline-block element for wrappers
  ([#572](https://github.com/bootstrap-vue/bootstrap-vue/issues/572))
  ([4b680ee](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b680eeac32f635c9b898e1d5c6704db2401d437)),
  closes [#571](https://github.com/bootstrap-vue/bootstrap-vue/issues/571)
- **tooltip+popover:** improve blur trigger handling
  ([c08b815](https://github.com/bootstrap-vue/bootstrap-vue/commit/c08b815266976564ba5ebb3eab3df0c05e6693db))
- **tooltip+popover:** Prevent leftover tooltip/popover divs
  ([f8cdf26](https://github.com/bootstrap-vue/bootstrap-vue/commit/f8cdf2693e2aa7e00cb5a786dfb01b33fda3863d)),
  closes [#1208](https://github.com/bootstrap-vue/bootstrap-vue/issues/1208)
- **tooltip+popover components:** Delay instantiation on mounted()
  ([#969](https://github.com/bootstrap-vue/bootstrap-vue/issues/969))
  ([4fc18ec](https://github.com/bootstrap-vue/bootstrap-vue/commit/4fc18ec3c54f04ebcf207a6de2043518b86d4d83))
- **tooltip+popover components:** Emit events and minor adjustments
  ([#972](https://github.com/bootstrap-vue/bootstrap-vue/issues/972))
  ([cf7c538](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf7c53853f27856614af6790a6a8893bd8c644a0))
- **v-play:** disable vue global errorHandler
  ([9a7bdaf](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a7bdaffb5c77b4783af2ab56f87c220174a444c))

* feat, docs: update input-group to BS 4.0.0.
  ([790c0de](https://github.com/bootstrap-vue/bootstrap-vue/commit/790c0de95125f7c4b6cb9328a488c70f36007a55))
* Dropdown ARIA keyboard nav (#274)
  ([d1a676a](https://github.com/bootstrap-vue/bootstrap-vue/commit/d1a676a873e5f73df82e564a033c5929d749a3ca)),
  closes [#274](https://github.com/bootstrap-vue/bootstrap-vue/issues/274)

### misc

- better packaging of css files
  ([87edbb9](https://github.com/bootstrap-vue/bootstrap-vue/commit/87edbb9d71bf2b5fa6b3ccb649724176fa3a1a15))

### Performance

- **alert:** convert template to render function
  ([#1308](https://github.com/bootstrap-vue/bootstrap-vue/issues/1308))
  ([8b0c7cd](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b0c7cda9f43453a964b5457b88c822f74341bb6))
- **b-link:** convert functional component to regular component (addresses
  [#3634](https://github.com/bootstrap-vue/bootstrap-vue/issues/3634))
  ([#3637](https://github.com/bootstrap-vue/bootstrap-vue/issues/3637))
  ([d3641ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/d3641ba7dd6b90929499cf099dbeb7855b8119ed))
- **b-table:** cache cell slot names each render cycle (addresses
  [#4008](https://github.com/bootstrap-vue/bootstrap-vue/issues/4008))
  ([#4011](https://github.com/bootstrap-vue/bootstrap-vue/issues/4011))
  ([78c604c](https://github.com/bootstrap-vue/bootstrap-vue/commit/78c604c6f4b5987f04ed86f272e6dc5922069bca))
- **b-table, b-table-lite:** delegate row event handlers to the tbody element
  ([#4192](https://github.com/bootstrap-vue/bootstrap-vue/issues/4192))
  ([3f0d46a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f0d46a3afb5113d60a9624729a675af1d42ccd0))
- **b-table, b-table-lite:** improve render performance (closes
  [#4211](https://github.com/bootstrap-vue/bootstrap-vue/issues/4211),
  [#4155](https://github.com/bootstrap-vue/bootstrap-vue/issues/4155))
  ([#4213](https://github.com/bootstrap-vue/bootstrap-vue/issues/4213))
  ([f3f42f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/f3f42f2780d56db2b7f6f89bd0af007f8f652668))
- **build:** reduce minified code size
  ([#1337](https://github.com/bootstrap-vue/bootstrap-vue/issues/1337))
  ([9d0ae3e](https://github.com/bootstrap-vue/bootstrap-vue/commit/9d0ae3e0c28d7289ac2c45dead9516e926b02e59))
- **button-toolbar:** convert template to render function
  ([#1315](https://github.com/bootstrap-vue/bootstrap-vue/issues/1315))
  ([765bfe3](https://github.com/bootstrap-vue/bootstrap-vue/commit/765bfe3b1baff692946b432547ae048db3ed1f17))
- **carousel:** convert templates to render functions
  ([#1339](https://github.com/bootstrap-vue/bootstrap-vue/issues/1339))
  ([13f429f](https://github.com/bootstrap-vue/bootstrap-vue/commit/13f429fc7b577552ab92a3e8c1db1c8eeaf153dd))
- **collapse:** convert template to render function
  ([#1316](https://github.com/bootstrap-vue/bootstrap-vue/issues/1316))
  ([722ea12](https://github.com/bootstrap-vue/bootstrap-vue/commit/722ea128a038ee61b70029b6f88a0a28b5ef8b61))
- **docs:** Better TOC SSR generation
  ([#1080](https://github.com/bootstrap-vue/bootstrap-vue/issues/1080))
  ([b3489d0](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3489d0ee9811d0d668444102f84f895c5701ade))
- **docs:** lodash dependency
  ([a02f10d](https://github.com/bootstrap-vue/bootstrap-vue/commit/a02f10d6375e506377a066d7f29087934be571ef))
- **docs:** only import debounce from lodash
  ([a6abd6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/a6abd6dee748083f764bb867b13e8a568af1e0f4))
- **dom:** Improve DOM utils code for minification & tree-shaking
  ([#1284](https://github.com/bootstrap-vue/bootstrap-vue/issues/1284))
  ([e1e701b](https://github.com/bootstrap-vue/bootstrap-vue/commit/e1e701ba4ec8850117ccd5d983dc47898f961abb))
- **dropdown:** changed 'this' to 't'
  ([#1500](https://github.com/bootstrap-vue/bootstrap-vue/issues/1500))
  ([ace3e94](https://github.com/bootstrap-vue/bootstrap-vue/commit/ace3e94a0b5724ea37954d7fd784086c2fe57155))
- **dropdowns:** convert templates to render functions
  ([#1314](https://github.com/bootstrap-vue/bootstrap-vue/issues/1314))
  ([3168e93](https://github.com/bootstrap-vue/bootstrap-vue/commit/3168e93f1c70d2064a7afe8bfa2d3965ec440f65))
- **dropdowns:** use non reactive property to store popper.js instance
  ([#1416](https://github.com/bootstrap-vue/bootstrap-vue/issues/1416))
  ([379d9a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/379d9a821fbbf1b1064cc69a46c8ecf14417baac))
- **events:** use passive event listeners where possible
  ([#2435](https://github.com/bootstrap-vue/bootstrap-vue/issues/2435))
  ([a01dee4](https://github.com/bootstrap-vue/bootstrap-vue/commit/a01dee40b6282797cd51cfb3163be8928dfa6ece))
- **form-checkboxes:** convert templates to render functions
  ([#1338](https://github.com/bootstrap-vue/bootstrap-vue/issues/1338))
  ([49bc50b](https://github.com/bootstrap-vue/bootstrap-vue/commit/49bc50b65b77f4a0445ec6b7f7df32d254559341))
- **form-file:** convert template to render function
  ([#1329](https://github.com/bootstrap-vue/bootstrap-vue/issues/1329))
  ([ec96f82](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec96f820a5840c90af00b7e1f7d2859cbaee6570))
- **form-group:** convert template to render function
  ([#1332](https://github.com/bootstrap-vue/bootstrap-vue/issues/1332))
  ([f409392](https://github.com/bootstrap-vue/bootstrap-vue/commit/f4093925525876b2deea9cf428607f230aff8442))
- **form-input:** convert template to render function
  ([#1330](https://github.com/bootstrap-vue/bootstrap-vue/issues/1330))
  ([12f0423](https://github.com/bootstrap-vue/bootstrap-vue/commit/12f04236cd944a0ba0784bb5d5737840a4454d19))
- **form-radios:** convert templates to render functions
  ([#1336](https://github.com/bootstrap-vue/bootstrap-vue/issues/1336))
  ([3a2aa0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a2aa0a19024ce1454e5d62f513fd8bc9a6a4707))
- **form-select:** convert template to render function
  ([#1333](https://github.com/bootstrap-vue/bootstrap-vue/issues/1333))
  ([9adfc12](https://github.com/bootstrap-vue/bootstrap-vue/commit/9adfc1268b53d3529907bb50588fcbe2188a2f86))
- **form-textarea:** convert template to render function
  ([#1331](https://github.com/bootstrap-vue/bootstrap-vue/issues/1331))
  ([5293e71](https://github.com/bootstrap-vue/bootstrap-vue/commit/5293e7161074e73d12521b76a3270c7d4a5d6b7e))
- **id mixin:** make localId\_ a computed field
  ([873b0e7](https://github.com/bootstrap-vue/bootstrap-vue/commit/873b0e7164a834cb5cc4f62696e453c37dcf0ce0))
- **modal:** convert template to render function
  ([#1340](https://github.com/bootstrap-vue/bootstrap-vue/issues/1340))
  ([bb7ec04](https://github.com/bootstrap-vue/bootstrap-vue/commit/bb7ec04740c148475d2595216c25ae1b705baf36))
- **modal:** Get scrollbar width just before modal opens rather than mount (fixes
  [#1800](https://github.com/bootstrap-vue/bootstrap-vue/issues/1800))
  ([#2165](https://github.com/bootstrap-vue/bootstrap-vue/issues/2165))
  ([e1729b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/e1729b476c2b29f93d8c5a6c88f64e823bc60727))
- **modal:** optimize model.resetScrollbar, resolves
  [#1831](https://github.com/bootstrap-vue/bootstrap-vue/issues/1831)
  ([#1837](https://github.com/bootstrap-vue/bootstrap-vue/issues/1837))
  ([a622358](https://github.com/bootstrap-vue/bootstrap-vue/commit/a622358444cdb494fe04c025d88b07996edfe2fc))
- **pkg:** remove lodash dependency from src
  ([#2523](https://github.com/bootstrap-vue/bootstrap-vue/issues/2523))
  ([b34ada3](https://github.com/bootstrap-vue/bootstrap-vue/commit/b34ada3c362c7fb50387f772c7b7d69860c49092))
- **progress:** use provide and inject for inter component communication
  ([#2540](https://github.com/bootstrap-vue/bootstrap-vue/issues/2540))
  ([80b7e5f](https://github.com/bootstrap-vue/bootstrap-vue/commit/80b7e5fed6be1f14ffe30ff827afe638962b502b))
- **table:** improve provide/inject performance (addresses
  [#4155](https://github.com/bootstrap-vue/bootstrap-vue/issues/4155))
  ([#4164](https://github.com/bootstrap-vue/bootstrap-vue/issues/4164))
  ([152fefc](https://github.com/bootstrap-vue/bootstrap-vue/commit/152fefc8638008e9d0b43c80fb512ceb8e822b78))
- **tables:** make `b-th` extend `b-td` instead of using functional wrappers
  ([#4156](https://github.com/bootstrap-vue/bootstrap-vue/issues/4156))
  ([c9715a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9715a89b1d693974dff8db7e24f97cdf908ff99))
- add event KeyCode constants in utils
  ([#1346](https://github.com/bootstrap-vue/bootstrap-vue/issues/1346))
  ([714d748](https://github.com/bootstrap-vue/bootstrap-vue/commit/714d74881982bade01d0f6f0540eefaacb570f83))
- evalute slots() once in functional component render functions
  ([#1438](https://github.com/bootstrap-vue/bootstrap-vue/issues/1438))
  ([3c42477](https://github.com/bootstrap-vue/bootstrap-vue/commit/3c42477137a4d4459c5d16b4c138426bd3121442))
- only call vueUse in main index.js entrypoint
  ([#2542](https://github.com/bootstrap-vue/bootstrap-vue/issues/2542))
  ([c0d469b](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0d469b833d42abe2f81c17dac5886ed11429942))
- remove default array/object polyfills
  ([#3641](https://github.com/bootstrap-vue/bootstrap-vue/issues/3641))
  ([8b34bf2](https://github.com/bootstrap-vue/bootstrap-vue/commit/8b34bf21965332b6f85dc229b39e140908dcb192))
- use re-usable fade transition component
  ([#3281](https://github.com/bootstrap-vue/bootstrap-vue/issues/3281))
  ([ceeb70e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ceeb70e3509db158e3ce91318b9333ef94449056))
- **img-lazy:** convert template to render function
  ([#1309](https://github.com/bootstrap-vue/bootstrap-vue/issues/1309))
  ([1736eb9](https://github.com/bootstrap-vue/bootstrap-vue/commit/1736eb943c10f05a9df5d4ba066fb77cdd2e741e))
- **input-group:** convert to functional component
  ([#1288](https://github.com/bootstrap-vue/bootstrap-vue/issues/1288))
  ([bd4c3c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd4c3c38ce0c4317b8a95e1ab4bae3ef06bd61ea))
- **navbar-toggle:** convert template to render function
  ([#1313](https://github.com/bootstrap-vue/bootstrap-vue/issues/1313))
  ([88657fb](https://github.com/bootstrap-vue/bootstrap-vue/commit/88657fba257e2d43b9ff1d848f6fd184c1c07074))
- **navbar-toggle:** Remove unused code
  ([1e95383](https://github.com/bootstrap-vue/bootstrap-vue/commit/1e95383959e48b6f926738b4d600967879c5c354))
- **pagination:** Move common code to pagination mixin
  ([#1069](https://github.com/bootstrap-vue/bootstrap-vue/issues/1069))
  ([0d41e83](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d41e830974867fac21969bebb059174ab70c0c5))
- **pagination+pagination-nav:** convert templates to render function
  ([#1348](https://github.com/bootstrap-vue/bootstrap-vue/issues/1348))
  ([e04291f](https://github.com/bootstrap-vue/bootstrap-vue/commit/e04291f0aac2014059b27e09e1c1bb9ab825f70c))
- **popover:** convert template to render function
  ([#1311](https://github.com/bootstrap-vue/bootstrap-vue/issues/1311))
  ([de24eec](https://github.com/bootstrap-vue/bootstrap-vue/commit/de24eecd2139c88afc365235ad795f7b1818c93c))
- **progress:** convert template to render function
  ([#1312](https://github.com/bootstrap-vue/bootstrap-vue/issues/1312))
  ([20d7d0b](https://github.com/bootstrap-vue/bootstrap-vue/commit/20d7d0b1db95944f608073751244d16fa2cbce6e))
- **table:** convert template to render function
  ([#1350](https://github.com/bootstrap-vue/bootstrap-vue/issues/1350))
  ([6a1ef4f](https://github.com/bootstrap-vue/bootstrap-vue/commit/6a1ef4f99370b34731e5e74ec48a7726714447fb))
- **table:** minor tweaks to primary key usage
  ([#2741](https://github.com/bootstrap-vue/bootstrap-vue/issues/2741))
  ([d083385](https://github.com/bootstrap-vue/bootstrap-vue/commit/d08338575590876248fb90d06d5ffa24c204d566))
- **tabs:** convert templates to render functions
  ([#1319](https://github.com/bootstrap-vue/bootstrap-vue/issues/1319))
  ([b45f550](https://github.com/bootstrap-vue/bootstrap-vue/commit/b45f550e9d5978402b1880b710c8687d75ac19fc))
- **tooltip:** convert template to render function
  ([#1310](https://github.com/bootstrap-vue/bootstrap-vue/issues/1310))
  ([c812cb0](https://github.com/bootstrap-vue/bootstrap-vue/commit/c812cb0996993ceeea8e80a7f7084462a9929dac))
- **utils/dom:** use passive event listeners where possible
  ([#2419](https://github.com/bootstrap-vue/bootstrap-vue/issues/2419))
  ([78fe776](https://github.com/bootstrap-vue/bootstrap-vue/commit/78fe776496953c617e6dedf9be409f30245c0a21))
- Move redudant code into plugin utility
  ([#1272](https://github.com/bootstrap-vue/bootstrap-vue/issues/1272))
  ([779b70d](https://github.com/bootstrap-vue/bootstrap-vue/commit/779b70d166981906143b34e3220adb96a626c8b3))
- move repetitive plugin code to plugin.js
  ([#1285](https://github.com/bootstrap-vue/bootstrap-vue/issues/1285))
  ([6ba8c46](https://github.com/bootstrap-vue/bootstrap-vue/commit/6ba8c46da4b8abca145970bc506718c8a73b14b8))

## [2.23.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.23.0...v2.23.1) (2022-10-26)

### Bug Fixes

- correctly pass parent relations for Vue.js2
  ([58e2d7e](https://github.com/bootstrap-vue/bootstrap-vue/commit/58e2d7e4f5e883207c4f7baa856532d3ae924a0c))

## [2.23.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.22.0...v2.23.0) (2022-10-25)

### Bug Fixes

- **vue3:** do not rely on \_\_vueParentComponent in tooltip
  ([fe13503](https://github.com/bootstrap-vue/bootstrap-vue/commit/fe13503f7aa6d0bd6f7e1ed4f4a2e7acff421106))
- update refs inside v-for to work for @vue/compat
  ([ae4bac8](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae4bac8a4327a1f293afbcf571e84ed1de4497f8))

### Other v2.23.0

- add support for @vue/compat

## [2.22.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.21.2...v2.22.0) (2022-04-17)

### Features

- **b-dropdown:** add `toggle-attrs` prop (closes
  [#3694](https://github.com/bootstrap-vue/bootstrap-vue/issues/3694))
  ([#6339](https://github.com/bootstrap-vue/bootstrap-vue/issues/6339))
  ([6cfcbb3](https://github.com/bootstrap-vue/bootstrap-vue/commit/6cfcbb300877e7e1fc03e847c540c6f2c8b0742b))
- **b-form-group:** add `content-cols` props and scoped `default` slot (closes
  [#6095](https://github.com/bootstrap-vue/bootstrap-vue/issues/6095),
  [#6118](https://github.com/bootstrap-vue/bootstrap-vue/issues/6118))
  ([#6178](https://github.com/bootstrap-vue/bootstrap-vue/issues/6178))
  ([fab6dc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab6dc57e974f14b7fb50f6f413f3fa9a4504290))
- **b-form-tags:** add `feedback-aria-live` prop
  ([#6347](https://github.com/bootstrap-vue/bootstrap-vue/issues/6347))
  ([5332970](https://github.com/bootstrap-vue/bootstrap-vue/commit/533297054ce98e879071b35da11a3dd5927beafe))
- **b-form-tags:** add `no-tags-remove` prop (closes
  [#6162](https://github.com/bootstrap-vue/bootstrap-vue/issues/6162))
  ([#6163](https://github.com/bootstrap-vue/bootstrap-vue/issues/6163))
  ([92de1f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/92de1f9f7772c595afcd16d25d8f71b54a2e077b))
- **b-form-tags:** add `reset` method
  ([#6104](https://github.com/bootstrap-vue/bootstrap-vue/issues/6104))
  ([d610291](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6102913a5f9a3295f646fad50ba58ffc31533e8))
- **b-form-tags:** adds `focusin` & `focusout` to wrapper and prevents firing multiple
  `focus`/`blur` events ([#6395](https://github.com/bootstrap-vue/bootstrap-vue/issues/6395))
  ([44e558f](https://github.com/bootstrap-vue/bootstrap-vue/commit/44e558f73c2ae0d4daafbdbc2616002c7c7a763f))
- **b-link:** support `exact-path` and `exact-path-active-class` props for router link (fixes
  [#6434](https://github.com/bootstrap-vue/bootstrap-vue/issues/6434))
  ([#6811](https://github.com/bootstrap-vue/bootstrap-vue/issues/6811))
  ([576e67b](https://github.com/bootstrap-vue/bootstrap-vue/commit/576e67b3af434037a5ee17533a232465527d5edd))
- add `headerTag` and `footerTag` props to all componets with header and footer
  ([#6375](https://github.com/bootstrap-vue/bootstrap-vue/issues/6375))
  ([c6dd70a](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6dd70a787cdc711b3ce539a65f6aac273749874))
- **b-media:** improve aside right handling
  ([#5965](https://github.com/bootstrap-vue/bootstrap-vue/issues/5965))
  ([49a3f00](https://github.com/bootstrap-vue/bootstrap-vue/commit/49a3f00420bf9958deda3a6be0ccb76cc3ea06ba))
- **b-sidebar:** add `header` slot
  ([#6179](https://github.com/bootstrap-vue/bootstrap-vue/issues/6179))
  ([341b7f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/341b7f07943d6079d2bf5d6ab88bbcc50f91d0c5))
- **config:** improved defaults handling (closes
  [#4507](https://github.com/bootstrap-vue/bootstrap-vue/issues/4507),
  [#5138](https://github.com/bootstrap-vue/bootstrap-vue/issues/5138),
  [#5291](https://github.com/bootstrap-vue/bootstrap-vue/issues/5291),
  [#5459](https://github.com/bootstrap-vue/bootstrap-vue/issues/5459),
  [#5958](https://github.com/bootstrap-vue/bootstrap-vue/issues/5958))
  ([#5981](https://github.com/bootstrap-vue/bootstrap-vue/issues/5981))
  ([7ea0cc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ea0cc4a16d27b179eca47d351eaa9fe6fdfd56e))
- **refactor:** code enhancements for easier Vue 3 migration (closes
  [#6124](https://github.com/bootstrap-vue/bootstrap-vue/issues/6124),
  [#6139](https://github.com/bootstrap-vue/bootstrap-vue/issues/6139))
  ([#6141](https://github.com/bootstrap-vue/bootstrap-vue/issues/6141))
  ([5bf6733](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bf6733595091cc204d3acc0641f8f0301bcbe9c))

### Bug Fixes

- **b-avatar:** badge `z-index` handling
  ([#5975](https://github.com/bootstrap-vue/bootstrap-vue/issues/5975))
  ([ecb33bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecb33bdb510832096bc5a5196a11c97388bf6411))
- **b-avatar:** prevent avatar from being squished
  ([#5963](https://github.com/bootstrap-vue/bootstrap-vue/issues/5963))
  ([b3946ed](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3946ed7a7b327fb7c66b44caaf122460fc24005)),
  closes [#5962](https://github.com/bootstrap-vue/bootstrap-vue/issues/5962)
- **b-badge:** attribute inheritance
  ([#6217](https://github.com/bootstrap-vue/bootstrap-vue/issues/6217))
  ([2d31f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/2d31f31909c002faa2a9d8bd8620115ddf8ce603))
- **b-dropdown:** click handling on close (closes
  [#5982](https://github.com/bootstrap-vue/bootstrap-vue/issues/5982))
  ([#6009](https://github.com/bootstrap-vue/bootstrap-vue/issues/6009))
  ([cf7a1cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf7a1cb017e2263939a64e300abbbbac35c121d4))
- **b-dropdown:** decrease delay when hiding inside a navbar on no-touch devices (closes
  [#6306](https://github.com/bootstrap-vue/bootstrap-vue/issues/6306))
  ([#6367](https://github.com/bootstrap-vue/bootstrap-vue/issues/6367))
  ([7d72605](https://github.com/bootstrap-vue/bootstrap-vue/commit/7d726056eb40a148afbafd0710035cb306582bb6))
- **b-dropdown:** only apply `heading` role to header when not a `header` tag
  ([#6274](https://github.com/bootstrap-vue/bootstrap-vue/issues/6274))
  ([bd67da0](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd67da0c40744e6b245a4e514e2319ca7bfafe2d))
- **b-dropdown:** root events ([#6198](https://github.com/bootstrap-vue/bootstrap-vue/issues/6198))
  ([6dcd233](https://github.com/bootstrap-vue/bootstrap-vue/commit/6dcd23334f2870220ed5c4d8b30bd556e57c03d5))
- **b-dropdown:** Sets correct `aria-haspopup` attribute for the toggle button
  ([#6865](https://github.com/bootstrap-vue/bootstrap-vue/issues/6865))
  ([d92c2f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/d92c2f1237b44102f0bf6eadd26d97423b9f8c2b))
- **b-form-checkbox/b-form-radio:** `chnage` event timing
  ([#6008](https://github.com/bootstrap-vue/bootstrap-vue/issues/6008))
  ([37ec7e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/37ec7e9991b66af51ff81420da8eb88928615f9d))
- **b-form-datepicker:** `valueAsDate` prop handling
  ([#6159](https://github.com/bootstrap-vue/bootstrap-vue/issues/6159))
  ([5cb8e0c](https://github.com/bootstrap-vue/bootstrap-vue/commit/5cb8e0c474ab750868379b4293d0eb5d52f5dd85))
- **b-form-datepicker/b-form-timepicker:** control size
  ([#6249](https://github.com/bootstrap-vue/bootstrap-vue/issues/6249))
  ([f2ffbeb](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2ffbeb85a71f0e3ac5c6ea55622771357c703e1))
- **b-form-datepicker/b-form-timepicker:** label styles when in `button-only` mode (closes
  [#6172](https://github.com/bootstrap-vue/bootstrap-vue/issues/6172))
  ([#6186](https://github.com/bootstrap-vue/bootstrap-vue/issues/6186))
  ([e8842ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8842bae98e83d16f3429b37f219ae61890a5c38))
- **b-form-group:** accessibility when `label-for` prop not set
  ([#6006](https://github.com/bootstrap-vue/bootstrap-vue/issues/6006))
  ([16f777b](https://github.com/bootstrap-vue/bootstrap-vue/commit/16f777b14bdcf9ebb6fae0325d355c7f5272bd98))
- **b-form-input:** modified value handling
  ([#6084](https://github.com/bootstrap-vue/bootstrap-vue/issues/6084))
  ([d6d8e3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6d8e3c0f309ca16ede0c874bb787ab2fed7b380))
- **b-form-input/b-form-textarea:** legacy browser support (closes
  [#6283](https://github.com/bootstrap-vue/bootstrap-vue/issues/6283))
  ([#6345](https://github.com/bootstrap-vue/bootstrap-vue/issues/6345))
  ([a79d98a](https://github.com/bootstrap-vue/bootstrap-vue/commit/a79d98a78f68ba3c15e626928f5e5208aba05d2f))
- **b-form-spinbutton:** button markup
  ([#6101](https://github.com/bootstrap-vue/bootstrap-vue/issues/6101))
  ([5082976](https://github.com/bootstrap-vue/bootstrap-vue/commit/5082976e90264cadd84a4c9dbf339ce90fe49456))
- **b-form-tags:** required handling (closes
  [#6094](https://github.com/bootstrap-vue/bootstrap-vue/issues/6094))
  ([#6103](https://github.com/bootstrap-vue/bootstrap-vue/issues/6103))
  ([2dc6b9d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dc6b9d5bc5fcb3cf1febda7d9e5b03d1ee9a3d0))
- **b-icon:** title render handling
  ([#6233](https://github.com/bootstrap-vue/bootstrap-vue/issues/6233))
  ([b025047](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0250477e6b4228f1f228c2776c8c211d8a57f00))
- **b-img-lazy:** `blank` placeholder for Firefox (closes
  [#6320](https://github.com/bootstrap-vue/bootstrap-vue/issues/6320))
  ([#6349](https://github.com/bootstrap-vue/bootstrap-vue/issues/6349))
  ([9b297c9](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b297c9415744ddb7bd3d50bbe5957859a61123e))
- **b-img-lazy:** fix blank-src not work error
  ([#6302](https://github.com/bootstrap-vue/bootstrap-vue/issues/6302))
  ([a6ace2f](https://github.com/bootstrap-vue/bootstrap-vue/commit/a6ace2f229680e13b0f91c17458461b8afda9f7b))
- **b-link:** remove default values from `vue-router` pass-down props (closes
  [#6373](https://github.com/bootstrap-vue/bootstrap-vue/issues/6373))
  ([#6374](https://github.com/bootstrap-vue/bootstrap-vue/issues/6374))
  ([0a14828](https://github.com/bootstrap-vue/bootstrap-vue/commit/0a14828961846b907cf8243e1a14954911f802cf))
- **b-skeleton:** accepts custom attributes
  ([#6858](https://github.com/bootstrap-vue/bootstrap-vue/issues/6858))
  ([9b1edc9](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b1edc978f7029facaf5a4f2a512b13cd43987a8))
- **b-table:** fix range selection of b-table
  ([#6606](https://github.com/bootstrap-vue/bootstrap-vue/issues/6606))
  ([c11f0db](https://github.com/bootstrap-vue/bootstrap-vue/commit/c11f0db211aa2c45209a4081ae4e02337ec55015))
- **b-table:** selected table header text no longer prevents table row selection
  ([#6645](https://github.com/bootstrap-vue/bootstrap-vue/issues/6645))
  ([010ab31](https://github.com/bootstrap-vue/bootstrap-vue/commit/010ab3180eaeb9f43e9c922fb6e47419504b8f99))
- replace sass division with multiplication
  ([#6834](https://github.com/bootstrap-vue/bootstrap-vue/issues/6834))
  ([dd051e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd051e93cbb2ce41d3060eda2b5a82ce28fe183c))
- **b-form-group:** remove `role="alert"` from valid/invalid feedback (closes
  [#6300](https://github.com/bootstrap-vue/bootstrap-vue/issues/6300),
  [#6307](https://github.com/bootstrap-vue/bootstrap-vue/issues/6307))
  ([#6346](https://github.com/bootstrap-vue/bootstrap-vue/issues/6346))
  ([c0959c4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c0959c4df2552929d7fa68e28fb700297df291f8))
- **b-input-tags:** not respecting custom `$input-color` (closes
  [#6388](https://github.com/bootstrap-vue/bootstrap-vue/issues/6388))
  ([#6389](https://github.com/bootstrap-vue/bootstrap-vue/issues/6389))
  ([9f045d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f045d47b1eae4036910a1e397ed17b664e259c5))
- **b-pagination:** don't set initial page count twice
  ([#6200](https://github.com/bootstrap-vue/bootstrap-vue/issues/6200))
  ([d7394e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7394e3426e5b06797caef070137ec47b25ef62a))
- **b-sidebar:** make sure to not exceed 100% in height (closes
  [#6176](https://github.com/bootstrap-vue/bootstrap-vue/issues/6176))
  ([#6234](https://github.com/bootstrap-vue/bootstrap-vue/issues/6234))
  ([782e11d](https://github.com/bootstrap-vue/bootstrap-vue/commit/782e11dedf8ed9f362a1c44772d660adf24975a5))
- **b-table:** add missing `role="grid"` when selectable (closes
  [#6305](https://github.com/bootstrap-vue/bootstrap-vue/issues/6305))
  ([#6372](https://github.com/bootstrap-vue/bootstrap-vue/issues/6372))
  ([bc02fb8](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc02fb86198701f8f2ef7b05dadf59cd2c0381cd))
- **b-table:** add missing `sortKey` field type and correct a typo
  ([#6355](https://github.com/bootstrap-vue/bootstrap-vue/issues/6355))
  ([f5ca62f](https://github.com/bootstrap-vue/bootstrap-vue/commit/f5ca62faec6d5fb9e873b362b6efb153d419a7cc))
- **b-table:** allow `responsive` and `stacked` props together
  ([#6266](https://github.com/bootstrap-vue/bootstrap-vue/issues/6266))
  ([fa977a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa977a83cf21dd118e30f81aacf80d1c25b5c484))
- **b-table:** default `role` to `grid` when `selectable` and `table` otherwise
  ([#6383](https://github.com/bootstrap-vue/bootstrap-vue/issues/6383))
  ([3f5a309](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f5a3095500c706a75f0f0d6015b0b2777051e1f)),
  closes [#6326](https://github.com/bootstrap-vue/bootstrap-vue/issues/6326)
- **b-table:** header cell overflow for `.sr-only` sort label
  ([#6371](https://github.com/bootstrap-vue/bootstrap-vue/issues/6371))
  ([11617b4](https://github.com/bootstrap-vue/bootstrap-vue/commit/11617b4c78d06a0f48306983621fdb4ec1aa9932))
- **b-table:** only set `aria-describedby` when caption really exists
  ([#6251](https://github.com/bootstrap-vue/bootstrap-vue/issues/6251))
  ([b980017](https://github.com/bootstrap-vue/bootstrap-vue/commit/b980017139613db5d7c8df4293a4d80673c9e646))
- **b-table:** only set `tabindex="0"` for sortable TH's
  ([#6102](https://github.com/bootstrap-vue/bootstrap-vue/issues/6102))
  ([dd23742](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd237425e4e7a7e73d5c17210780b02dab2110e2))
- **b-table:** prefer user-provided `role` attribute
  ([#6382](https://github.com/bootstrap-vue/bootstrap-vue/issues/6382))
  ([9e25a3b](https://github.com/bootstrap-vue/bootstrap-vue/commit/9e25a3b97e911e84473991def78c9b4307b6f822))
- **b-table:** set `aria-sort` when using `sortKey` and `no-local-sorting` (closes
  [#6602](https://github.com/bootstrap-vue/bootstrap-vue/issues/6602))
  ([#6603](https://github.com/bootstrap-vue/bootstrap-vue/issues/6603))
  ([2438137](https://github.com/bootstrap-vue/bootstrap-vue/commit/2438137c3757b28657e7185432805079ee25c559))
- **b-table:** sort handling for numeric string values (closes
  [#6092](https://github.com/bootstrap-vue/bootstrap-vue/issues/6092))
  ([#6105](https://github.com/bootstrap-vue/bootstrap-vue/issues/6105))
  ([29fbcb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/29fbcb58c5efed0dbbafa8b0bb5fc1d1651079cd))
- **b-tabs:** cleanup rendering logic
  ([#6154](https://github.com/bootstrap-vue/bootstrap-vue/issues/6154))
  ([8aeb9e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/8aeb9e941e84ec45a3415ab7238729458f56e427))
- **b-tabs:** restore correct active tab detection logic (closes
  [#6205](https://github.com/bootstrap-vue/bootstrap-vue/issues/6205))
  ([#6208](https://github.com/bootstrap-vue/bootstrap-vue/issues/6208))
  ([6d92a43](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d92a4376c227a02a7c24e19c04e437bb8909c1c))
- **docs:** completing the url so that the link is correct
  ([#6545](https://github.com/bootstrap-vue/bootstrap-vue/issues/6545))
  ([c9c85a9](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9c85a92460c583439f96b61095e2fa0f3c41378))
- **nav-item-dropdown:** update dropdown to set correct aria-controls
  ([97bb97b](https://github.com/bootstrap-vue/bootstrap-vue/commit/97bb97b004b28bc34a49fc20dcc5b247f228404f))
- **utils/dom:** bind `requestAF()` to `window`
  ([#6508](https://github.com/bootstrap-vue/bootstrap-vue/issues/6508))
  ([#6511](https://github.com/bootstrap-vue/bootstrap-vue/issues/6511))
  ([f8caaec](https://github.com/bootstrap-vue/bootstrap-vue/commit/f8caaec837b184d3f2736a6fdb4b8ceea28942ae))
- clean up props inheritance ([#6265](https://github.com/bootstrap-vue/bootstrap-vue/issues/6265))
  ([79784ae](https://github.com/bootstrap-vue/bootstrap-vue/commit/79784ae6e03f90ee14ce90f8f5e02d0249eb5c4a))
- environment detection based on `userAgent`
  ([#6226](https://github.com/bootstrap-vue/bootstrap-vue/issues/6226))
  ([cdfd16c](https://github.com/bootstrap-vue/bootstrap-vue/commit/cdfd16c32296072e49596a8acf722c77709f1b93))
- **table:** default sort compare logic for date strings
  ([#6153](https://github.com/bootstrap-vue/bootstrap-vue/issues/6153))
  ([3696a1f](https://github.com/bootstrap-vue/bootstrap-vue/commit/3696a1f888f2462a428431a593e235fd89bf54d4))
- user supplied prop function detection
  ([#6070](https://github.com/bootstrap-vue/bootstrap-vue/issues/6070))
  ([cea6051](https://github.com/bootstrap-vue/bootstrap-vue/commit/cea6051efc901325d63c22f65381242bd6e774e7))
- user supplied prop function detection (closes
  [#6112](https://github.com/bootstrap-vue/bootstrap-vue/issues/6112))
  ([#6113](https://github.com/bootstrap-vue/bootstrap-vue/issues/6113))
  ([1d85839](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d85839fa76c88f1a411a81945d03a4c895b3f4f))
- **table:** use original value for fallback when number parsing fails in `defaultSortCompare()`
  ([c375ce9](https://github.com/bootstrap-vue/bootstrap-vue/commit/c375ce9093ed91060b4ab199ad771dd667a68589))

<a name="2.21.2"></a>

### [v2.21.2](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.21.1...v2.21.2)

Released: 2021-01-01

### Bug Fixes v2.21.2

- **b-dropdown:** only apply `heading` role to header when not a `header` tag
  ([#6274](https://github.com/bootstrap-vue/bootstrap-vue/issues/6274))
  ([bd67da0](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd67da0c40744e6b245a4e514e2319ca7bfafe2d))
- **b-table:** allow `responsive` and `stacked` props together
  ([#6266](https://github.com/bootstrap-vue/bootstrap-vue/issues/6266))
  ([fa977a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/fa977a83cf21dd118e30f81aacf80d1c25b5c484))
- clean up props inheritance ([#6265](https://github.com/bootstrap-vue/bootstrap-vue/issues/6265))
  ([79784ae](https://github.com/bootstrap-vue/bootstrap-vue/commit/79784ae6e03f90ee14ce90f8f5e02d0249eb5c4a))
- **b-form-datepicker/b-form-timepicker:** control size
  ([#6249](https://github.com/bootstrap-vue/bootstrap-vue/issues/6249))
  ([f2ffbeb](https://github.com/bootstrap-vue/bootstrap-vue/commit/f2ffbeb85a71f0e3ac5c6ea55622771357c703e1))
- **b-icon:** title render handling
  ([#6233](https://github.com/bootstrap-vue/bootstrap-vue/issues/6233))
  ([b025047](https://github.com/bootstrap-vue/bootstrap-vue/commit/b0250477e6b4228f1f228c2776c8c211d8a57f00))
- **b-sidebar:** make sure to not exceed 100% in height (closes
  [#6176](https://github.com/bootstrap-vue/bootstrap-vue/issues/6176))
  ([#6234](https://github.com/bootstrap-vue/bootstrap-vue/issues/6234))
  ([782e11d](https://github.com/bootstrap-vue/bootstrap-vue/commit/782e11dedf8ed9f362a1c44772d660adf24975a5))
- **b-table:** only set `aria-describedby` when caption really exists
  ([#6251](https://github.com/bootstrap-vue/bootstrap-vue/issues/6251))
  ([b980017](https://github.com/bootstrap-vue/bootstrap-vue/commit/b980017139613db5d7c8df4293a4d80673c9e646))
- environment detection based on `userAgent`
  ([#6226](https://github.com/bootstrap-vue/bootstrap-vue/issues/6226))
  ([cdfd16c](https://github.com/bootstrap-vue/bootstrap-vue/commit/cdfd16c32296072e49596a8acf722c77709f1b93))

<a name="2.21.1"></a>

## [v2.21.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.21.0...v2.21.1)

Released: 2020-12-16

### Bug Fixes v2.21.1

- **b-badge:** attribute inheritance
  ([#6217](https://github.com/bootstrap-vue/bootstrap-vue/issues/6217))
  ([2d31f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/2d31f31909c002faa2a9d8bd8620115ddf8ce603))
- **b-dropdown:** root events ([#6198](https://github.com/bootstrap-vue/bootstrap-vue/issues/6198))
  ([6dcd233](https://github.com/bootstrap-vue/bootstrap-vue/commit/6dcd23334f2870220ed5c4d8b30bd556e57c03d5))
- **b-pagination:** don't set initial page count twice
  ([#6200](https://github.com/bootstrap-vue/bootstrap-vue/issues/6200))
  ([d7394e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/d7394e3426e5b06797caef070137ec47b25ef62a))
- **b-tabs:** restore correct active tab detection logic (closes
  [#6205](https://github.com/bootstrap-vue/bootstrap-vue/issues/6205))
  ([#6208](https://github.com/bootstrap-vue/bootstrap-vue/issues/6208))
  ([6d92a43](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d92a4376c227a02a7c24e19c04e437bb8909c1c))

<a name="2.21.0"></a>

## [v2.21.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.20.1...v2.21.0)

Released: 2020-12-14

### Features v2.21.0

- **b-form-group:** add `content-cols` props and scoped `default` slot (closes
  [#6095](https://github.com/bootstrap-vue/bootstrap-vue/issues/6095),
  [#6118](https://github.com/bootstrap-vue/bootstrap-vue/issues/6118))
  ([#6178](https://github.com/bootstrap-vue/bootstrap-vue/issues/6178))
  ([fab6dc5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab6dc57e974f14b7fb50f6f413f3fa9a4504290))
- **b-form-tags:** add `no-tags-remove` prop (closes
  [#6162](https://github.com/bootstrap-vue/bootstrap-vue/issues/6162))
  ([#6163](https://github.com/bootstrap-vue/bootstrap-vue/issues/6163))
  ([92de1f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/92de1f9f7772c595afcd16d25d8f71b54a2e077b))
- **b-sidebar:** add `header` slot
  ([#6179](https://github.com/bootstrap-vue/bootstrap-vue/issues/6179))
  ([341b7f0](https://github.com/bootstrap-vue/bootstrap-vue/commit/341b7f07943d6079d2bf5d6ab88bbcc50f91d0c5))
- **refactor:** code enhancements for easier Vue 3 migration (closes
  [#6124](https://github.com/bootstrap-vue/bootstrap-vue/issues/6124),
  [#6139](https://github.com/bootstrap-vue/bootstrap-vue/issues/6139))
  ([#6141](https://github.com/bootstrap-vue/bootstrap-vue/issues/6141))
  ([5bf6733](https://github.com/bootstrap-vue/bootstrap-vue/commit/5bf6733595091cc204d3acc0641f8f0301bcbe9c))
- **icons:** update Bootstrap Icons to v1.2.1
  ([#6194](https://github.com/bootstrap-vue/bootstrap-vue/issues/6194))
  ([799e272](https://github.com/bootstrap-vue/bootstrap-vue/commit/799e272d5ae5c19425c4c912a72becfaafaac447))
- **icons:** update Bootstrap Icons to v1.2.0
  ([#6180](https://github.com/bootstrap-vue/bootstrap-vue/issues/6180))
  ([00682e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/00682e549e1a104156e3f701e2e6e6cffd13cb70))

### Bug Fixes v2.21.0

- **b-form-datepicker:** `valueAsDate` prop handling
  ([#6159](https://github.com/bootstrap-vue/bootstrap-vue/issues/6159))
  ([5cb8e0c](https://github.com/bootstrap-vue/bootstrap-vue/commit/5cb8e0c474ab750868379b4293d0eb5d52f5dd85))
- **b-form-datepicker/b-form-timepicker:** label styles when in `button-only` mode (closes
  [#6172](https://github.com/bootstrap-vue/bootstrap-vue/issues/6172))
  ([#6186](https://github.com/bootstrap-vue/bootstrap-vue/issues/6186))
  ([e8842ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/e8842bae98e83d16f3429b37f219ae61890a5c38))
- **b-tabs:** cleanup rendering logic
  ([#6154](https://github.com/bootstrap-vue/bootstrap-vue/issues/6154))
  ([8aeb9e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/8aeb9e941e84ec45a3415ab7238729458f56e427))
- **table:** default sort compare logic for date strings
  ([#6153](https://github.com/bootstrap-vue/bootstrap-vue/issues/6153))
  ([3696a1f](https://github.com/bootstrap-vue/bootstrap-vue/commit/3696a1f888f2462a428431a593e235fd89bf54d4))
- **table:** use original value for fallback when number parsing fails in `defaultSortCompare()`
  ([c375ce9](https://github.com/bootstrap-vue/bootstrap-vue/commit/c375ce9093ed91060b4ab199ad771dd667a68589))

<a name="2.20.1"></a>

## [v2.20.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.20.0...v2.20.1)

Released: 2020-12-01

### Bug Fixes v2.20.1

- user supplied prop function detection (closes
  [#6112](https://github.com/bootstrap-vue/bootstrap-vue/issues/6112))
  ([#6113](https://github.com/bootstrap-vue/bootstrap-vue/issues/6113))
  ([1d85839](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d85839fa76c88f1a411a81945d03a4c895b3f4f))

<a name="2.20.0"></a>

## [v2.20.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.19.0...v2.20.0)

Released: 2020-11-30

### Features v2.20.0

- **b-form-tags:** add `reset` method
  ([#6104](https://github.com/bootstrap-vue/bootstrap-vue/issues/6104))
  ([d610291](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6102913a5f9a3295f646fad50ba58ffc31533e8))

### Bug Fixes v2.20.0

- **b-form-input:** modified value handling
  ([#6084](https://github.com/bootstrap-vue/bootstrap-vue/issues/6084))
  ([d6d8e3c](https://github.com/bootstrap-vue/bootstrap-vue/commit/d6d8e3c0f309ca16ede0c874bb787ab2fed7b380))
- **b-form-spinbutton:** button markup
  ([#6101](https://github.com/bootstrap-vue/bootstrap-vue/issues/6101))
  ([5082976](https://github.com/bootstrap-vue/bootstrap-vue/commit/5082976e90264cadd84a4c9dbf339ce90fe49456))
- **b-form-tags:** required handling (closes
  [#6094](https://github.com/bootstrap-vue/bootstrap-vue/issues/6094))
  ([#6103](https://github.com/bootstrap-vue/bootstrap-vue/issues/6103))
  ([2dc6b9d](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dc6b9d5bc5fcb3cf1febda7d9e5b03d1ee9a3d0))
- **b-table:** only set `tabindex="0"` for sortable TH's
  ([#6102](https://github.com/bootstrap-vue/bootstrap-vue/issues/6102))
  ([dd23742](https://github.com/bootstrap-vue/bootstrap-vue/commit/dd237425e4e7a7e73d5c17210780b02dab2110e2))
- **b-table:** sort handling for numeric string values (closes
  [#6092](https://github.com/bootstrap-vue/bootstrap-vue/issues/6092))
  ([#6105](https://github.com/bootstrap-vue/bootstrap-vue/issues/6105))
  ([29fbcb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/29fbcb58c5efed0dbbafa8b0bb5fc1d1651079cd))
- user supplied prop function detection
  ([#6070](https://github.com/bootstrap-vue/bootstrap-vue/issues/6070))
  ([cea6051](https://github.com/bootstrap-vue/bootstrap-vue/commit/cea6051efc901325d63c22f65381242bd6e774e7))

<a name="2.19.0"></a>

## [v2.19.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.18.1...v2.19.0)

Released: 2020-11-08

### Features v2.19.0

- **b-media:** improve aside right handling
  ([#5965](https://github.com/bootstrap-vue/bootstrap-vue/issues/5965))
  ([49a3f00](https://github.com/bootstrap-vue/bootstrap-vue/commit/49a3f00420bf9958deda3a6be0ccb76cc3ea06ba))
- **config:** improved defaults handling (closes
  [#4507](https://github.com/bootstrap-vue/bootstrap-vue/issues/4507),
  [#5138](https://github.com/bootstrap-vue/bootstrap-vue/issues/5138),
  [#5291](https://github.com/bootstrap-vue/bootstrap-vue/issues/5291),
  [#5459](https://github.com/bootstrap-vue/bootstrap-vue/issues/5459),
  [#5958](https://github.com/bootstrap-vue/bootstrap-vue/issues/5958))
  ([#5981](https://github.com/bootstrap-vue/bootstrap-vue/issues/5981))
  ([7ea0cc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ea0cc4a16d27b179eca47d351eaa9fe6fdfd56e))
- **icons:** update Bootstrap Icons to v1.1.0
  ([#5977](https://github.com/bootstrap-vue/bootstrap-vue/issues/5977))
  ([8e45ad4](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e45ad4d2d62c667113fe85db4fd755821c2eada))

### Bug Fixes v2.19.0

- **b-avatar:** badge `z-index` handling
  ([#5975](https://github.com/bootstrap-vue/bootstrap-vue/issues/5975))
  ([ecb33bd](https://github.com/bootstrap-vue/bootstrap-vue/commit/ecb33bdb510832096bc5a5196a11c97388bf6411))
- **b-avatar:** prevent avatar from being squished
  ([#5963](https://github.com/bootstrap-vue/bootstrap-vue/issues/5963))
  ([b3946ed](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3946ed7a7b327fb7c66b44caaf122460fc24005)),
  closes [#5962](https://github.com/bootstrap-vue/bootstrap-vue/issues/5962)
- **b-dropdown:** click handling on close (closes
  [#5982](https://github.com/bootstrap-vue/bootstrap-vue/issues/5982))
  ([#6009](https://github.com/bootstrap-vue/bootstrap-vue/issues/6009))
  ([cf7a1cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/cf7a1cb017e2263939a64e300abbbbac35c121d4))
- **b-form-checkbox/b-form-radio:** `change` event timing
  ([#6008](https://github.com/bootstrap-vue/bootstrap-vue/issues/6008))
  ([37ec7e9](https://github.com/bootstrap-vue/bootstrap-vue/commit/37ec7e9991b66af51ff81420da8eb88928615f9d))
- **b-form-group:** accessibility when `label-for` prop not set
  ([#6006](https://github.com/bootstrap-vue/bootstrap-vue/issues/6006))
  ([16f777b](https://github.com/bootstrap-vue/bootstrap-vue/commit/16f777b14bdcf9ebb6fae0325d355c7f5272bd98))

<a name="2.18.1"></a>

## [v2.18.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.18.0...v2.18.1)

Released: 2020-10-21

### Bug Fixes v2.18.1

- **b-form-group:** content element ID handling (closes
  [#5930](https://github.com/bootstrap-vue/bootstrap-vue/issues/5930))
  ([#5933](https://github.com/bootstrap-vue/bootstrap-vue/issues/5933))
  ([fecd558](https://github.com/bootstrap-vue/bootstrap-vue/commit/fecd55814c4f4553348d8016cdf0d449f22228f7))
- **b-icon:** local component lookup
  ([#5939](https://github.com/bootstrap-vue/bootstrap-vue/issues/5939))
  ([4586b49](https://github.com/bootstrap-vue/bootstrap-vue/commit/4586b49d99e4239dbebe2518f57022d6e4e20224))
- **b-link:** `href` handling with live router (closes
  [#5927](https://github.com/bootstrap-vue/bootstrap-vue/issues/5927))
  ([#5934](https://github.com/bootstrap-vue/bootstrap-vue/issues/5934))
  ([8a367b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/8a367b6296b0aa9700f67633fd60fb351e2f7373))

<a name="2.18.0"></a>

## [v2.18.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.17.3...v2.18.0)

Released: 2020-10-19

### Features v2.18.0

- **b-calendar:** add `no-key-nav` property (closes
  [#5861](https://github.com/bootstrap-vue/bootstrap-vue/issues/5861))
  ([#5883](https://github.com/bootstrap-vue/bootstrap-vue/issues/5883))
  ([955ad63](https://github.com/bootstrap-vue/bootstrap-vue/commit/955ad631698f82a83de214ce9cd37271367d8c45))
- update `core-js` to v3 ([#5894](https://github.com/bootstrap-vue/bootstrap-vue/issues/5894))
  ([aeed981](https://github.com/bootstrap-vue/bootstrap-vue/commit/aeed9812afe770b6561c9513709e4be852250022))

### Bug Fixes v2.18.0

- **b-calendar:** month formatting for certain dates
  ([#5911](https://github.com/bootstrap-vue/bootstrap-vue/issues/5911))
  ([7de1844](https://github.com/bootstrap-vue/bootstrap-vue/commit/7de1844c6d5c0014d25c930527a7fc49a2b0cc25))
- **b-card:** properly support header/footer with body image overlay
  ([#5872](https://github.com/bootstrap-vue/bootstrap-vue/issues/5872))
  ([bd8319d](https://github.com/bootstrap-vue/bootstrap-vue/commit/bd8319da8c6166f9fe3e64d9a3ac5c490c6b2f48))
- **b-carousel:** fix glitching when switching slides fast (closes
  [#5810](https://github.com/bootstrap-vue/bootstrap-vue/issues/5810))
  ([#5845](https://github.com/bootstrap-vue/bootstrap-vue/issues/5845))
  ([761bc93](https://github.com/bootstrap-vue/bootstrap-vue/commit/761bc9381ba24aed751726c8213651e2014aa746))
- **b-link:** `href` handling inconsistencies to `<router-link>` (closes
  [#5820](https://github.com/bootstrap-vue/bootstrap-vue/issues/5820))
  ([#5876](https://github.com/bootstrap-vue/bootstrap-vue/issues/5876))
  ([daea0e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/daea0e5c638de9ec45d39af5aa1e9f8a9e455422))
- **b-skeleton:** animation overflow issue for Safari
  ([#5863](https://github.com/bootstrap-vue/bootstrap-vue/issues/5863))
  ([bfd4f96](https://github.com/bootstrap-vue/bootstrap-vue/commit/bfd4f960d7056edcd2ccb1ae3930639d543d8b34))
- **v-tooltip, v-popover:** render data-\* attributes on root components (closes
  [#5836](https://github.com/bootstrap-vue/bootstrap-vue/issues/5836))
  ([#5882](https://github.com/bootstrap-vue/bootstrap-vue/issues/5882))
  ([f6b51e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6b51e04f074e45e98650034e88c2b5629ad25f6))

<a name="2.17.3"></a>

## [v2.17.3](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.17.2...v2.17.3)

Released: 2020-09-18

- No changes to v2.17.2.

<a name="2.17.2"></a>

## [v2.17.2](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.17.1...v2.17.2)

Released: 2020-09-18

### Bug Fixes v2.17.2

- **b-nav-item-dropdown:** `boundary` handling in `<b-navbar>` (closes
  [#5789](https://github.com/bootstrap-vue/bootstrap-vue/issues/5789))
  ([#5794](https://github.com/bootstrap-vue/bootstrap-vue/issues/5794))
  ([73383bf](https://github.com/bootstrap-vue/bootstrap-vue/commit/73383bfd935c097604bf5ad39a9cc2d18961ba87))
- **b-skeleton:** add missing component exports
  ([#5806](https://github.com/bootstrap-vue/bootstrap-vue/issues/5806))
  ([871ce22](https://github.com/bootstrap-vue/bootstrap-vue/commit/871ce22504c4e64348b844c0e4306161317abf60))
- **b-tooltip, b-popover:** fix `title` not being reset on hide
  ([#5793](https://github.com/bootstrap-vue/bootstrap-vue/issues/5793))
  ([31eeb0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/31eeb0ab5ef262c33579f43969c7d6ee6c802e3d))

<a name="2.17.1"></a>

## [v2.17.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.17.0...v2.17.1)

Released: 2020-09-16

### Bug Fixes v2.17.1

- **b-modal:** solve body padding not being removed
  ([#5771](https://github.com/bootstrap-vue/bootstrap-vue/issues/5771))
  ([78d51f1](https://github.com/bootstrap-vue/bootstrap-vue/commit/78d51f1e7146cbed756853003a93b991c9f0d8bc))
- **b-table:** properly handle empty included/excluded filter fields (closes
  [#5775](https://github.com/bootstrap-vue/bootstrap-vue/issues/5775))
  ([#5780](https://github.com/bootstrap-vue/bootstrap-vue/issues/5780))
  ([78ac383](https://github.com/bootstrap-vue/bootstrap-vue/commit/78ac383c0c727be4f970874e73bf05e3f23b1a3b))

<a name="2.17.0"></a>

## [v2.17.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.16.0...v2.17.0)

Released: 2020-09-13

### Features v2.17.0

- **b-avatar:** add size classes for `sm` and `lg` sizes (closes
  [#5592](https://github.com/bootstrap-vue/bootstrap-vue/issues/5592))
  ([#5768](https://github.com/bootstrap-vue/bootstrap-vue/issues/5768))
  ([942bf31](https://github.com/bootstrap-vue/bootstrap-vue/commit/942bf31546179abce8f0bb8252f8716c85c6de86))
- **b-calendar:** add `nav-button-variant` prop (closes
  [#5702](https://github.com/bootstrap-vue/bootstrap-vue/issues/5702))
  ([#5705](https://github.com/bootstrap-vue/bootstrap-vue/issues/5705))
  ([aa291fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/aa291fce6df52df4d2396b9499c964ce0ac5962b))
- **b-form-file:** improved drag and drop handling (closes
  [#3673](https://github.com/bootstrap-vue/bootstrap-vue/issues/3673))
  ([#5727](https://github.com/bootstrap-vue/bootstrap-vue/issues/5727))
  ([3b12a73](https://github.com/bootstrap-vue/bootstrap-vue/commit/3b12a73d3856a0b14f630d45d236570698b75e50))
- **b-icon:** add proper `title` support (closes
  [#5711](https://github.com/bootstrap-vue/bootstrap-vue/issues/5711))
  ([#5724](https://github.com/bootstrap-vue/bootstrap-vue/issues/5724))
  ([3756b2c](https://github.com/bootstrap-vue/bootstrap-vue/commit/3756b2c0e07fc85f73769ea312ede8917d1e1de5))
- **b-pagination/b-pagination-nav:** allow page change to be prevented (closes
  [#5679](https://github.com/bootstrap-vue/bootstrap-vue/issues/5679))
  ([#5755](https://github.com/bootstrap-vue/bootstrap-vue/issues/5755))
  ([7e18c61](https://github.com/bootstrap-vue/bootstrap-vue/commit/7e18c615fec871fb99a947ca5e247bcef04b7c6f))
- **b-sidebar:** add `noEnforceFocus` prop (closes
  [#5707](https://github.com/bootstrap-vue/bootstrap-vue/issues/5707))
  ([#5734](https://github.com/bootstrap-vue/bootstrap-vue/issues/5734))
  ([c11c237](https://github.com/bootstrap-vue/bootstrap-vue/commit/c11c237143230f533404af75933d86a2de7bfb56))
- **b-skeleton:** add skeleton components (closes
  [#5413](https://github.com/bootstrap-vue/bootstrap-vue/issues/5413))
  ([#5575](https://github.com/bootstrap-vue/bootstrap-vue/issues/5575))
  ([31c06b5](https://github.com/bootstrap-vue/bootstrap-vue/commit/31c06b5fa697b5f13cc888a1d72effae21eb5e73))
- **b-table:** add `sortKey` option for `no-local-sorting` events
  ([#5746](https://github.com/bootstrap-vue/bootstrap-vue/issues/5746))
  ([f847dae](https://github.com/bootstrap-vue/bootstrap-vue/commit/f847daeb797b84ed80b49a31294a5088fc32b59d))
- **b-tags:** add `limit` prop ([#5543](https://github.com/bootstrap-vue/bootstrap-vue/issues/5543))
  ([caa0f1a](https://github.com/bootstrap-vue/bootstrap-vue/commit/caa0f1a2e6d96637c216eb306c77a67254af1caf))
- **docs:** auto-detect settings props in component reference
  ([#5761](https://github.com/bootstrap-vue/bootstrap-vue/issues/5761))
  ([0ddb2e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0ddb2e051c0ce42bdd599415ba93e82e1a6584f1))
- **icons:** update Bootstrap Icons to v1.0.0
  ([#5708](https://github.com/bootstrap-vue/bootstrap-vue/issues/5708))
  ([edc2d35](https://github.com/bootstrap-vue/bootstrap-vue/commit/edc2d35dfc3eb9a550517b10e18f53673670e145))

### Bug Fixes v2.17.0

- **b-avatar:** image fit and scale (closes
  [#5610](https://github.com/bootstrap-vue/bootstrap-vue/issues/5610),
  [#5655](https://github.com/bootstrap-vue/bootstrap-vue/issues/5655))
  ([#5675](https://github.com/bootstrap-vue/bootstrap-vue/issues/5675))
  ([9812248](https://github.com/bootstrap-vue/bootstrap-vue/commit/9812248ea686e339f32604c0020a1714bb228d75))
- **b-button-toolbar:** allow focus to leave toolbar by keyboard
  ([#5737](https://github.com/bootstrap-vue/bootstrap-vue/issues/5737))
  ([f54e427](https://github.com/bootstrap-vue/bootstrap-vue/commit/f54e4275881947cfb504235aa9330c03444e08bb))
- **b-form-checkbox:** `change` event value when in multiple mode
  ([#5716](https://github.com/bootstrap-vue/bootstrap-vue/issues/5716))
  ([5150b94](https://github.com/bootstrap-vue/bootstrap-vue/commit/5150b943f25ff6b2f331aaef64321973bd60dd0e))
- **b-form-checkbox/b-form-radio:** remove `autocomplete="off"` attribute
  ([#5764](https://github.com/bootstrap-vue/bootstrap-vue/issues/5764))
  ([443aaf1](https://github.com/bootstrap-vue/bootstrap-vue/commit/443aaf1afc38dc029e0b142c11a39d360bbc98d2))
- **b-form-datepicker/b-form-timepicker/b-nav-item-dropdown:** dropdown positioning handling (closes
  [#5700](https://github.com/bootstrap-vue/bootstrap-vue/issues/5700),
  [#5630](https://github.com/bootstrap-vue/bootstrap-vue/issues/5630))
  ([#5765](https://github.com/bootstrap-vue/bootstrap-vue/issues/5765))
  ([7ec2205](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ec2205a96e0d14772f1ed6c047a9808a32fbf82))
- **b-form-file:** drop handling for huge amounts of files (closes
  [#5615](https://github.com/bootstrap-vue/bootstrap-vue/issues/5615))
  ([#5685](https://github.com/bootstrap-vue/bootstrap-vue/issues/5685))
  ([d54b240](https://github.com/bootstrap-vue/bootstrap-vue/commit/d54b240adeb6eadfe8736f4926384a5c4d351bde))
- **b-form-input:** fix debounce when value does not change
  ([#5632](https://github.com/bootstrap-vue/bootstrap-vue/issues/5632))
  ([111ca65](https://github.com/bootstrap-vue/bootstrap-vue/commit/111ca65240ab6941e2173ca44806aa0a75691c95))
- **b-form-tags:** ensure same height with or without tags
  ([#5752](https://github.com/bootstrap-vue/bootstrap-vue/issues/5752))
  ([07102f9](https://github.com/bootstrap-vue/bootstrap-vue/commit/07102f988cfe8e8290189e73f50790f70bbb4639))
- **b-form-textarea:** `setStyle()` util usage
  ([bf7a65f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf7a65f87caf0d725033c35ee85c1e32ced82adc))
- **b-pagination:** properly calculate number of links with `hide-ellipsis` option (closes
  [#5514](https://github.com/bootstrap-vue/bootstrap-vue/issues/5514))
  ([#5678](https://github.com/bootstrap-vue/bootstrap-vue/issues/5678))
  ([98e17ca](https://github.com/bootstrap-vue/bootstrap-vue/commit/98e17ca85588b858f5d74e217c48fa82f11f487f))
- **bv-tooltip:** hide the tooltip when the title is set to empty (closes
  [#5648](https://github.com/bootstrap-vue/bootstrap-vue/issues/5648))
  ([#5677](https://github.com/bootstrap-vue/bootstrap-vue/issues/5677))
  ([5363a31](https://github.com/bootstrap-vue/bootstrap-vue/commit/5363a3132df898cb5f0cac172c0510aead62d66e))
- **perf:** reactivity issues with `bvAttrs` and `bvListeners` (closes
  [#5520](https://github.com/bootstrap-vue/bootstrap-vue/issues/5520))
  ([#5753](https://github.com/bootstrap-vue/bootstrap-vue/issues/5753))
  ([d83a2b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/d83a2b179cac2f7449a7138fce71e07139e18c94))
- **v-b-toggle:** prevent scroll anchoring behavior (closes
  [#5715](https://github.com/bootstrap-vue/bootstrap-vue/issues/5715))
  ([#5769](https://github.com/bootstrap-vue/bootstrap-vue/issues/5769))
  ([390a5c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/390a5c7045432c98999ae8bf9259fb9ae03bcb19))
- component destroy handling on parent destroy
  ([#5749](https://github.com/bootstrap-vue/bootstrap-vue/issues/5749))
  ([e67d341](https://github.com/bootstrap-vue/bootstrap-vue/commit/e67d34190358cb5e9d3e6d45ec74f045bf20caef))
- don't display BootstrapVue warning messages when in production
  ([bf8966f](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf8966f6de725bf2828ca4609056c27dd4a96399))
- don't display warning messages when in production (closes
  [#5598](https://github.com/bootstrap-vue/bootstrap-vue/issues/5598))
  ([#5763](https://github.com/bootstrap-vue/bootstrap-vue/issues/5763))
  ([4b5d916](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b5d9162b8a6531c0ada66f646498b0ba40a0e9b))
- **b-table:** make sure to apply all formatters of field configuration (closes
  [#5672](https://github.com/bootstrap-vue/bootstrap-vue/issues/5672))
  ([#5674](https://github.com/bootstrap-vue/bootstrap-vue/issues/5674))
  ([c7c14ea](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7c14ea1d023b26af8a12c12dbc2c3d8220b7f67))
- **ssr:** avoid tree missmatches by either using `domProps` or `children` (closes
  [#5453](https://github.com/bootstrap-vue/bootstrap-vue/issues/5453),
  [#5557](https://github.com/bootstrap-vue/bootstrap-vue/issues/5557))
  ([#5723](https://github.com/bootstrap-vue/bootstrap-vue/issues/5723))
  ([5e8dad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/5e8dad84c094ff1f7810f69293418b81e676af26))
- **v-b-toggle:** handle component updates on click listeners
  ([#5690](https://github.com/bootstrap-vue/bootstrap-vue/issues/5690))
  ([156b1d6](https://github.com/bootstrap-vue/bootstrap-vue/commit/156b1d6a3a1ebb6548ea0dbfac346d61a92f6ed9))

<a name="2.16.0"></a>

## [v2.16.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.15.0...v2.16.0)

Released: 2020-07-27

### Features v2.16.0

- **b-form-tags:** add `ignoreInputFocusSelector` prop to make input focus behavior configurable
  (closes [#5425](https://github.com/bootstrap-vue/bootstrap-vue/issues/5425))
  ([#5429](https://github.com/bootstrap-vue/bootstrap-vue/issues/5429))
  ([26d5953](https://github.com/bootstrap-vue/bootstrap-vue/commit/26d5953f834684d36b0af99da912dba08fd37bd8))
- **docs:** launch themes page with first BootstrapVue theme
  ([#5549](https://github.com/bootstrap-vue/bootstrap-vue/issues/5549))
  ([ec51ef0](https://github.com/bootstrap-vue/bootstrap-vue/commit/ec51ef062f7ed39339cde59b2d9d4cee40347dcc))
- **icons:** update Bootstrap Icons to v1.0.0-alpha5
  ([#5533](https://github.com/bootstrap-vue/bootstrap-vue/issues/5533))
  ([d52ce0b](https://github.com/bootstrap-vue/bootstrap-vue/commit/d52ce0bd400e94c9a7c99787356e7c277e8d8f0c))

### Bug Fixes v2.16.0

- properly handle special characters in user-provided IDs (closes
  [#4927](https://github.com/bootstrap-vue/bootstrap-vue/issues/4927),
  [#5561](https://github.com/bootstrap-vue/bootstrap-vue/issues/5561))
  ([#5564](https://github.com/bootstrap-vue/bootstrap-vue/issues/5564))
  ([1fabd68](https://github.com/bootstrap-vue/bootstrap-vue/commit/1fabd68bb44b28a9127810f35bd07e1fdf3d12ec))
- **b-form-checkbox-group:** only emit `input` when value loosely changes
  ([#5432](https://github.com/bootstrap-vue/bootstrap-vue/issues/5432))
  ([e76d408](https://github.com/bootstrap-vue/bootstrap-vue/commit/e76d40874bd2a42126162101e94bb18e9042840b))
- **b-form-tags:** unit test ([#5586](https://github.com/bootstrap-vue/bootstrap-vue/issues/5586))
  ([f4d509a](https://github.com/bootstrap-vue/bootstrap-vue/commit/f4d509af647eaf87e2b635d08ff9431b25150650))
- **b-icon:** use `aria-label` attribute instead of `alt`
  ([#5581](https://github.com/bootstrap-vue/bootstrap-vue/issues/5581))
  ([72a1363](https://github.com/bootstrap-vue/bootstrap-vue/commit/72a13635b94aedfab1fb6800f2a297fa306f63ef))
- **b-img:** Allow empty `alt` prop (fixes
  [#5524](https://github.com/bootstrap-vue/bootstrap-vue/issues/5524))
  ([#5545](https://github.com/bootstrap-vue/bootstrap-vue/issues/5545))
  ([b22829d](https://github.com/bootstrap-vue/bootstrap-vue/commit/b22829d064b6e3820ef66168ec766a57520f31eb))
- **b-table:** prevent endless reevaluation when using v-model and object/array literal prop values
  ([#5554](https://github.com/bootstrap-vue/bootstrap-vue/issues/5554))
  ([f127d91](https://github.com/bootstrap-vue/bootstrap-vue/commit/f127d916d1ddd3a3da37bcb081150f86b356a7a4))
- **b-tags:** replace spacing utility with static CSS (fixes
  [#5523](https://github.com/bootstrap-vue/bootstrap-vue/issues/5523))
  ([#5544](https://github.com/bootstrap-vue/bootstrap-vue/issues/5544))
  ([e0de687](https://github.com/bootstrap-vue/bootstrap-vue/commit/e0de6871640db405e7b0bfa23f3c33f348894cea))

<a name="2.15.0"></a>

## [v2.15.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.14.0...v2.15.0)

Released: 2020-05-22

### Features v2.15.0

- **css:** update Bootstrap to v4.5.0
  ([#5395](https://github.com/bootstrap-vue/bootstrap-vue/issues/5395))
  ([ba7a55e](https://github.com/bootstrap-vue/bootstrap-vue/commit/ba7a55ea094049fd1e3ae492a5a95196252b1da9))
- **icons:** update Bootstrap Icons to v1.0.0-alpha4
  ([#5420](https://github.com/bootstrap-vue/bootstrap-vue/issues/5420))
  ([3208309](https://github.com/bootstrap-vue/bootstrap-vue/commit/3208309c649b4cce73c68643d7c911237a713ebc))
- **b-sidebar:** add prop `backdrop-variant`
  ([#5411](https://github.com/bootstrap-vue/bootstrap-vue/issues/5411))
  ([4b0c163](https://github.com/bootstrap-vue/bootstrap-vue/commit/4b0c163156b6ac5be6c1b0a2801d7c169c87cb49))
- **b-link:** add support 3rd party router links such as Gridsome's `<g-link>` (closes
  [#2627](https://github.com/bootstrap-vue/bootstrap-vue/issues/2627))
  ([#5358](https://github.com/bootstrap-vue/bootstrap-vue/issues/5358))
  ([6d29e1c](https://github.com/bootstrap-vue/bootstrap-vue/commit/6d29e1cff6c4fd42b3f60f86bd017d8601de3956))
- **b-navbar-toggle:** add `disabled` prop
  ([#5397](https://github.com/bootstrap-vue/bootstrap-vue/issues/5397))
  ([0b7082b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b7082b792ee49847ba7c99c61758c0d9fd6d222))
- **v-b-toggle:** check for target ID via `href` if a link
  ([#5398](https://github.com/bootstrap-vue/bootstrap-vue/issues/5398))
  ([33e39b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/33e39b007225ba86a0c84a66e3ee60b9d2f01fed))
- **types:** create declarations for `<b-calendar>` and `<b-time>` context event objects (closes
  [#5366](https://github.com/bootstrap-vue/bootstrap-vue/issues/5366))
  ([#5374](https://github.com/bootstrap-vue/bootstrap-vue/issues/5374))
  ([8f3ca30](https://github.com/bootstrap-vue/bootstrap-vue/commit/8f3ca30e4d51b5e97f9c4f301c31254a8b060980))
- support `<nuxt-link>`'s `prefetch` property (closes
  [#5125](https://github.com/bootstrap-vue/bootstrap-vue/issues/5125))
  ([#5355](https://github.com/bootstrap-vue/bootstrap-vue/issues/5355))
  ([b9416cb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b9416cb3824d680e297347af61a934b1536224de))

### Bug Fixes v2.15.0

- **v-b-toggle:** don't check for evt.defaultPrevented (closes
  [#5391](https://github.com/bootstrap-vue/bootstrap-vue/issues/5391))
  ([#5396](https://github.com/bootstrap-vue/bootstrap-vue/issues/5396))
  ([a1543b2](https://github.com/bootstrap-vue/bootstrap-vue/commit/a1543b297040ea593306ec55d7de5f1e2e776bce))
- **b-link:** default new `<nuxt-link>` prop `prefetch` to `null` for true tri-state prop
  ([#5357](https://github.com/bootstrap-vue/bootstrap-vue/issues/5357))
  ([3f41c91](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f41c91961c29988ba13ca11f4dc8f81810e761f))
- ensure all intervals/timeouts/observers are cleared when component is destroyed
  ([#5362](https://github.com/bootstrap-vue/bootstrap-vue/issues/5362))
  ([064cdf4](https://github.com/bootstrap-vue/bootstrap-vue/commit/064cdf4f7e7c6b779c1bd689a6d300efdf81bc0d))
- properly handle HTML props render order (closes
  [#5363](https://github.com/bootstrap-vue/bootstrap-vue/issues/5363))
  ([#5365](https://github.com/bootstrap-vue/bootstrap-vue/issues/5365))
  ([844ecda](https://github.com/bootstrap-vue/bootstrap-vue/commit/844ecda654a2db50d9b84c193f1ab031e291d024))
- fix docs CodeSandbox integration
  ([#5381](https://github.com/bootstrap-vue/bootstrap-vue/issues/5381))
  ([a948846](https://github.com/bootstrap-vue/bootstrap-vue/commit/a948846400c37fca0fa3ed673b1c4684fc6f69e1))

<a name="2.14.0"></a>

## [v2.14.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.13.1...v2.14.0)

Released: 2020-05-12

### Features v2.14.0

- **b-avatar-group:** new helper component `<b-avatar-group>`
  ([#5272](https://github.com/bootstrap-vue/bootstrap-vue/issues/5272))
  ([c84faae](https://github.com/bootstrap-vue/bootstrap-vue/commit/c84faaebe18bbf652583d6c302447e931a4ab741))
- **b-nav-item-dropdown:** improve default handling of dropdown toggle link (closes
  [#3942](https://github.com/bootstrap-vue/bootstrap-vue/issues/3942))
  ([#5344](https://github.com/bootstrap-vue/bootstrap-vue/issues/5344))
  ([62c6105](https://github.com/bootstrap-vue/bootstrap-vue/commit/62c6105e25bc4590f9e2fa92069b77ccbc17fac6))
- **v-b-toggle:** support specifying target ID via directive argument, and array of target IDs via
  directive value (closes [#4834](https://github.com/bootstrap-vue/bootstrap-vue/issues/4834))
  ([#5336](https://github.com/bootstrap-vue/bootstrap-vue/issues/5336))
  ([260ef72](https://github.com/bootstrap-vue/bootstrap-vue/commit/260ef7259e46d343823767374322db0ae3a74803))

### Bug Fixes v2.14.0

- **b-modal:** remove `role="document"` from `.modal-content`
  ([#5345](https://github.com/bootstrap-vue/bootstrap-vue/issues/5345))
  ([0c2b406](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c2b406e8dadc274e8433d3a4c414e799d0fa228))
- **perf:** avoid useless re-renders of component on parent update
  ([#4825](https://github.com/bootstrap-vue/bootstrap-vue/issues/4825))
  ([2cb3fe0](https://github.com/bootstrap-vue/bootstrap-vue/commit/2cb3fe0fa822a8284e023ccf71f8e451f124016a))

### Other v2.14.0

- dev dependency upgrades
- docs updates
- upgrade to vue test utils 1.0.x

<a name="2.13.1"></a>

## [v2.13.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.13.0...v2.13.1)

Released: 2020-05-05

### Bug Fixes v2.13.1

- **b-table, b-table-lite, b-table-simple:** handle head/foot variant for sticky columns (fixes
  [#5278](https://github.com/bootstrap-vue/bootstrap-vue/issues/5278))
  ([#5279](https://github.com/bootstrap-vue/bootstrap-vue/issues/5279))
  ([53e309e](https://github.com/bootstrap-vue/bootstrap-vue/commit/53e309e947b4710fcf8d989cc9ef0f31c58487ae))

### Other v2.13.1

- documentation updates
- dev dependency updates

<a name="2.13.0"></a>

## [v2.13.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.12.0...v2.13.0)

Released: 2020-04-27

### Features v2.13.0

- **b-calendar, b-form-datepicker:** relax `YYYY-MM-DD` string parsing (closes
  [#5232](https://github.com/bootstrap-vue/bootstrap-vue/issues/5232))
  ([#5242](https://github.com/bootstrap-vue/bootstrap-vue/issues/5242))
  ([f362802](https://github.com/bootstrap-vue/bootstrap-vue/commit/f362802b2794f0e5d294bbb004d91ccd623a1e25))
- **b-form-rating:** add `show-value-max` prop to show possible max rating when `show-value` is
  `true` ([#5200](https://github.com/bootstrap-vue/bootstrap-vue/issues/5200))
  ([e9d54e6](https://github.com/bootstrap-vue/bootstrap-vue/commit/e9d54e6c6a736b2a4f9dbf232dd2b20afa0e990c))
- **b-overlay:** add support for overlay `click` event (closes
  [#5243](https://github.com/bootstrap-vue/bootstrap-vue/issues/5243))
  ([#5248](https://github.com/bootstrap-vue/bootstrap-vue/issues/5248))
  ([582560f](https://github.com/bootstrap-vue/bootstrap-vue/commit/582560ff97690ab1e5c1f609d76804b7b3daa104))

### Bug Fixes v2.13.0

- **b-avatar:** set `align-items: center` for default slot content (fixes:
  [#5205](https://github.com/bootstrap-vue/bootstrap-vue/issues/5205))
  ([#5207](https://github.com/bootstrap-vue/bootstrap-vue/issues/5207))
  ([c4981fd](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4981fd098253840a37e731331de65b0e732fc79))
- **b-calendar, b-form-datepicker:** minor adjustments to styling and example updates
  ([#5211](https://github.com/bootstrap-vue/bootstrap-vue/issues/5211))
  ([f0d8ffe](https://github.com/bootstrap-vue/bootstrap-vue/commit/f0d8ffe4253079939008108fe86529a2f69553f1))
- **b-form-datepicker, b-form-timepicker:** fix menu padding in button only mode (fixes
  [#5251](https://github.com/bootstrap-vue/bootstrap-vue/issues/5251))
  ([#5252](https://github.com/bootstrap-vue/bootstrap-vue/issues/5252))
  ([d57a643](https://github.com/bootstrap-vue/bootstrap-vue/commit/d57a643f0c6b5e805a42a3387fb0db4443bfc01f))
- **b-form-datepicker, b-form-timepicker:** adjust scss to support input-groups
  ([#5231](https://github.com/bootstrap-vue/bootstrap-vue/issues/5231))
  ([7b1adc4](https://github.com/bootstrap-vue/bootstrap-vue/commit/7b1adc460f11c2ee54466fe0d204579f3f6f1bd2))
- **b-form-datepicker, b-form-timepicker:** prevent duplicate validation icons (fixes
  [#5237](https://github.com/bootstrap-vue/bootstrap-vue/issues/5237))
  ([#5238](https://github.com/bootstrap-vue/bootstrap-vue/issues/5238))
  ([6354e6e](https://github.com/bootstrap-vue/bootstrap-vue/commit/6354e6eb90b93e668c2794b3b4c2117a7cfc0ab0))
- **types:** update table field definition types to include sticky column (fixes
  [#5263](https://github.com/bootstrap-vue/bootstrap-vue/issues/5263))
  ([#5265](https://github.com/bootstrap-vue/bootstrap-vue/issues/5265))
  ([20eb3ac](https://github.com/bootstrap-vue/bootstrap-vue/commit/20eb3ac9e22ddbcc41d1f1aa923871007abe0dc0))
- handle nested form options normalization
  ([#5247](https://github.com/bootstrap-vue/bootstrap-vue/issues/5247))
  ([0c57ffe](https://github.com/bootstrap-vue/bootstrap-vue/commit/0c57ffe31c946475498fa3554b8b4aba4e9d19df))

### Other v2.13.0

- dev dependencies updates
- documentation updates
- new docs domain [`https://bootstrap-vue3-compat.org/`](https://bootstrap-vue3-compat.org/)

<a name="2.12.0"></a>

## [v2.12.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.11.0...v2.12.0)

Released: 2020-04-20

### Features v2.12.0

- **b-avatar:** add support for badges on avatars
  ([#5124](https://github.com/bootstrap-vue/bootstrap-vue/issues/5124))
  ([a2e465b](https://github.com/bootstrap-vue/bootstrap-vue/commit/a2e465b6457cabb88e42bcefd86a86e36c4602de))
- **b-avatar:** if `variant` is empty string, then remove spacing around image (closes
  [#5154](https://github.com/bootstrap-vue/bootstrap-vue/issues/5154))
  ([#5156](https://github.com/bootstrap-vue/bootstrap-vue/issues/5156))
  ([7ff87fc](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ff87fc560a2ad005bdca394cccf1fafa9d5e696))
- **b-calendar, b-form-datepicker:** add prop `weekday-header-format` to specify weekday header
  length (closes [#5171](https://github.com/bootstrap-vue/bootstrap-vue/issues/5171))
  ([#5175](https://github.com/bootstrap-vue/bootstrap-vue/issues/5175))
  ([8241644](https://github.com/bootstrap-vue/bootstrap-vue/commit/8241644477b174042bb163ba1741c3066165d9f9))
- **b-calendar, b-form-datepicker:** add scoped slots for date navigation buttons (closes
  [#5117](https://github.com/bootstrap-vue/bootstrap-vue/issues/5117))
  ([#5147](https://github.com/bootstrap-vue/bootstrap-vue/issues/5147))
  ([5f69864](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f69864497a13a9b18a96b508af6b9ba89a43add))
- **b-form-datepicker:** add pass through prop `date-info-fn` (closes
  [#4826](https://github.com/bootstrap-vue/bootstrap-vue/issues/4826))
  ([#5150](https://github.com/bootstrap-vue/bootstrap-vue/issues/5150))
  ([bf35f80](https://github.com/bootstrap-vue/bootstrap-vue/commit/bf35f80d1c4619cf4494dc8a6256d093140d4052))
- **b-form-rating:** new `b-form-rating` custom component
  ([#5132](https://github.com/bootstrap-vue/bootstrap-vue/issues/5132))
  ([30ad7fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/30ad7fe746cd6187311c86319abf6e9519b81f15))
- **b-sidebar:** add optional backdrop support
  ([#5182](https://github.com/bootstrap-vue/bootstrap-vue/issues/5182))
  ([c6375e5](https://github.com/bootstrap-vue/bootstrap-vue/commit/c6375e5513cb0ec33a9bc9fc894a123d74cf7768))
- **custom components:** avoid using padding/margin utility classes where possible (closes
  [#5117](https://github.com/bootstrap-vue/bootstrap-vue/issues/5117))
  ([#5121](https://github.com/bootstrap-vue/bootstrap-vue/issues/5121))
  ([8c6cfe0](https://github.com/bootstrap-vue/bootstrap-vue/commit/8c6cfe0af919a4e54667bcb4b29d2ba6b6576b67))
- **icons:** new `throb` and `fade` animations
  ([#5122](https://github.com/bootstrap-vue/bootstrap-vue/issues/5122))
  ([bc0117c](https://github.com/bootstrap-vue/bootstrap-vue/commit/bc0117cc794c948b202daf2e17f22eb4c36235cc))

### Bug Fixes v2.12.0

- **b-alert:** fix memory leak by using the correct method to clear the countdown timeout
  ([#5158](https://github.com/bootstrap-vue/bootstrap-vue/issues/5158))
  ([7a7f33d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a7f33d74f906e5feecf2bf177636c7f85bc4537))
- **b-avatar:** fix button type font size inheritance
  ([#5177](https://github.com/bootstrap-vue/bootstrap-vue/issues/5177))
  ([441ebdc](https://github.com/bootstrap-vue/bootstrap-vue/commit/441ebdc8a262c6c6ed494ddc6a6c0c06604045ef))
- **b-calendar:** use `Intl.NumberFormat` for formatting the number in the date buttons (closes
  [#5171](https://github.com/bootstrap-vue/bootstrap-vue/issues/5171))
  ([#5179](https://github.com/bootstrap-vue/bootstrap-vue/issues/5179))
  ([cbf2cd0](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbf2cd007cce81a5f664fa649b08af6735fe16e4))
- **b-form-datepicker:** make datepicker respect `no-highlight-today` prop
  ([#5159](https://github.com/bootstrap-vue/bootstrap-vue/issues/5159))
  ([c4ead33](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4ead3302b176e4a90fbfcfe6380de0edc22640f))

### Other v2.12.0

- documentation updates
- dev dependency updates

<a name="2.11.0"></a>

## [v2.11.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.10.1...v2.11.0)

Released: 2020-04-07

### Features v2.11.0

- **b-avatar:** if image `src` fails to load, then show icon, text or fallback icon
  ([#5079](https://github.com/bootstrap-vue/bootstrap-vue/issues/5079))
  ([ed6704d](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed6704d0971ade485393b7f711f05d93ca42ebc3))
- **b-calendar, b-form-datepicker:** add optional decade navigation buttons (addresses
  [#4976](https://github.com/bootstrap-vue/bootstrap-vue/issues/4976))
  ([#5112](https://github.com/bootstrap-vue/bootstrap-vue/issues/5112))
  ([b1f74a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/b1f74a84f4021022e606360ee6824c6645b6fbd0))

### Bug Fixes v2.11.0

- **b-calendar, b-form-datepicker:** handle keyboard navigation when selected date is out of range
  (fixes [#5057](https://github.com/bootstrap-vue/bootstrap-vue/issues/5057))
  ([#5108](https://github.com/bootstrap-vue/bootstrap-vue/issues/5108))
  ([6ed09f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/6ed09f40ae1594c7ad96dedc8c3d7c2a54d4d9c7))
- **b-link:** don't render `target` or `rel` attrs when `router-tag` other than `a` or `area`
  provided ([#5107](https://github.com/bootstrap-vue/bootstrap-vue/issues/5107))
  ([33c6cef](https://github.com/bootstrap-vue/bootstrap-vue/commit/33c6cefc2f46ab8110e39f110d984f230d525c86))
- **tooltip, popover:** handle `'click blur'` trigger on iOS webkit browsers (fixes
  [#5099](https://github.com/bootstrap-vue/bootstrap-vue/issues/5099))
  ([#5103](https://github.com/bootstrap-vue/bootstrap-vue/issues/5103))
  ([27da76c](https://github.com/bootstrap-vue/bootstrap-vue/commit/27da76cdc70449b0564e31f5733df97d758652ea))

### Other v2.11.0

- additional unit testing
- dev dependencies updates
- minor documentation updates

<a name="2.10.1"></a>

## [v2.10.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.10.0...v2.10.1)

Released: 2020-04-02

### Bug Fixes v2.10.1

- **b-avatar:** remove default padding when in button mode (fixes
  [#5073](https://github.com/bootstrap-vue/bootstrap-vue/issues/5073))
  ([#5076](https://github.com/bootstrap-vue/bootstrap-vue/issues/5076))
  ([26377b3](https://github.com/bootstrap-vue/bootstrap-vue/commit/26377b3479f323baa2d702fab7f5200949ed680d))
- **b-table:** fix context object `currentPage` issue introduced in v2.10.0 (fixes
  [#5065](https://github.com/bootstrap-vue/bootstrap-vue/issues/5065))
  ([#5067](https://github.com/bootstrap-vue/bootstrap-vue/issues/5067))
  ([874dca2](https://github.com/bootstrap-vue/bootstrap-vue/commit/874dca2c8c385fecf7cec76e6cfa44eda9fcabf4))

### Other v2.10.1

- dev dependency updates

<a name="2.10.0"></a>

## [v2.10.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.9.0...v2.10.0)

Released: 2020-04-01

### Features v2.10.0

- **b-sidebar:** new custom component `<b-sidebar>` (closes
  [#3324](https://github.com/bootstrap-vue/bootstrap-vue/issues/3324),
  [#3210](https://github.com/bootstrap-vue/bootstrap-vue/issues/3210),
  [#1702](https://github.com/bootstrap-vue/bootstrap-vue/issues/1702))
  ([#5021](https://github.com/bootstrap-vue/bootstrap-vue/issues/5021))
  ([a77866f](https://github.com/bootstrap-vue/bootstrap-vue/commit/a77866f6d032f1a5a22be2d12d60be507825769c))

### Bug Fixes v2.10.0

- **b-avatar:** remove duplicate button variant class
  ([#5056](https://github.com/bootstrap-vue/bootstrap-vue/issues/5056))
  ([9f78f32](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f78f32d964b187f35a1feffb7aa4bc264587923))
- **b-card:** handle `header-html` and `footer-html` props correctly (fixes
  [#5038](https://github.com/bootstrap-vue/bootstrap-vue/issues/5038))
  ([#5039](https://github.com/bootstrap-vue/bootstrap-vue/issues/5039))
  ([f378aef](https://github.com/bootstrap-vue/bootstrap-vue/commit/f378aeffdebdc7922f6ad4c5d513642dfb93cf1d))
- **types:** add missing declaration for `b-form-timepicker` (closes
  [#5035](https://github.com/bootstrap-vue/bootstrap-vue/issues/5035))
  ([#5036](https://github.com/bootstrap-vue/bootstrap-vue/issues/5036))
  ([ae84118](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae841184dc3037b5d6f365311cc668bccb0e85da))

### Other v2.10.0

- documentation site improvements and updates
- dev dependency updates

<a name="2.9.0"></a>

## [v2.9.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.8.0...v2.9.0)

Released: 2020-03-25

### Features v2.9.0

- **b-aspect:** new custom component `<b-aspect>`
  ([#5008](https://github.com/bootstrap-vue/bootstrap-vue/issues/5008))
  ([662c8e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/662c8e0709c8c73fb2119976d1906943cfe6daad))
- **b-avatar:** add `alt` prop for adding alt attribute to image and icon avatars (closes
  [#4990](https://github.com/bootstrap-vue/bootstrap-vue/issues/4990))
  ([#4991](https://github.com/bootstrap-vue/bootstrap-vue/issues/4991))
  ([d1474f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/d1474f28729e4e13ad97b75a87d56f85543d4c96))
- **b-dropdown-item-button, b-dropdown-item-button:** add `button-class` and `link-class` prop
  ([#5014](https://github.com/bootstrap-vue/bootstrap-vue/issues/5014))
  ([b39d31c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b39d31cede76b594b5608fa472d53e3dac525e2b))
- **b-form-datepicker, b-form-timepicker:** emit `shown` and `hidden` events
  ([#5004](https://github.com/bootstrap-vue/bootstrap-vue/issues/5004))
  ([eb259b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/eb259b998dfd3e88a1b04ed8d3f4c97560f69dbb))
- **b-navbar-toggle:** make default slot scoped
  ([#4995](https://github.com/bootstrap-vue/bootstrap-vue/issues/4995))
  ([144d45f](https://github.com/bootstrap-vue/bootstrap-vue/commit/144d45fb0e4d66bbf243b4a4df39d7f3b9b5c7cc))

### Docs v2.9.0

- Ensure that the `IconsPlugin` is imported when exporting from playground to CodePen, CodeSandbox,
  and JsFiddle ([#5003](https://github.com/bootstrap-vue/bootstrap-vue/issues/5003))

### Other v2.9.0

- dev dependency updates

<a name="2.8.0"></a>

## [v2.8.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.7.0...v2.8.0)

Released: 2020-03-22

### Features v2.8.0

- **icons:** update Bootstrap Icons to v1.0.0.alpha3
  ([#4966](https://github.com/bootstrap-vue/bootstrap-vue/issues/4966))
  ([d481365](https://github.com/bootstrap-vue/bootstrap-vue/commit/d481365c9f8014e1573026881c3588f2d51999ee))
  - 200+ new icons
  - `skip-*` icon names fixed (closes [#4733](https://github.com/bootstrap-vue/bootstrap-vue/4733))
  - `document-*` icons renamed to `file-*`
  - `alert-*` icons renamed to `exclamation-*`
  - `columns-gutters` icon renamed to `columns-gap`
  - `diamond` icon renamed to `gem` because of new `diamond-*` shape icons
- **b-avatar:** new `<b-avatar>` component
  ([#4974](https://github.com/bootstrap-vue/bootstrap-vue/issues/4974))
  ([b2325a3](https://github.com/bootstrap-vue/bootstrap-vue/commit/b2325a3f87a58207603be0bad41afb3059a575a1))
- **b-form-spinbutton:** add slots for increment and decrement button content (closes
  [#4958](https://github.com/bootstrap-vue/bootstrap-vue/issues/4958))
  ([#4963](https://github.com/bootstrap-vue/bootstrap-vue/issues/4963))
  ([5684405](https://github.com/bootstrap-vue/bootstrap-vue/commit/5684405197c8dd03b0711b0efc11ab6d76fb7714))

### Other v2.8.0

- docs updates
- dev dependencies updates

<a name="2.7.0"></a>

## [v2.7.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.6.1...v2.7.0)

Released: 2020-03-14

### Features v2.7.0

- **b-overlay:** new component `b-overlay`
  ([#4907](https://github.com/bootstrap-vue/bootstrap-vue/issues/4907))
  ([134d64d](https://github.com/bootstrap-vue/bootstrap-vue/commit/134d64d073bb64fecd74ffc521476bfd97a99fc0))
- **b-calendar, b-form-datepicker:** add new `initial-date` prop, and constrain today/current month
  buttons between `min` and `max` (closes
  [#4899](https://github.com/bootstrap-vue/bootstrap-vue/issues/4899))
  ([#4906](https://github.com/bootstrap-vue/bootstrap-vue/issues/4906))
  ([1d957eb](https://github.com/bootstrap-vue/bootstrap-vue/commit/1d957ebd78a8693e91a8116d12c28fe24bd7c19c))
- **b-form-datepicker, b-form-timepicker:** add support for icon button only mode (closes
  [#4888](https://github.com/bootstrap-vue/bootstrap-vue/issues/4888))
  ([#4915](https://github.com/bootstrap-vue/bootstrap-vue/issues/4915))
  ([13660c3](https://github.com/bootstrap-vue/bootstrap-vue/commit/13660c3ad02f6c692d306ec95f0d2b19212f9423))
- **b-icon:** add animated icon options (closes
  [#4720](https://github.com/bootstrap-vue/bootstrap-vue/issues/4720))
  ([#4934](https://github.com/bootstrap-vue/bootstrap-vue/issues/4934),
  [#4945](https://github.com/bootstrap-vue/bootstrap-vue/issues/4945),
  [#4948](https://github.com/bootstrap-vue/bootstrap-vue/issues/4948))
  ([7c781fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/7c781faea78315a753b2db903b12c500d6547ae1),
  [b786f67](https://github.com/bootstrap-vue/bootstrap-vue/commit/b786f671c3d69bbf9dbfb088840a332d4a066b14),
  [927c234](https://github.com/bootstrap-vue/bootstrap-vue/commit/927c234a6b5d68e23e86f7d1782b179b1ccb8786))

### Bug Fixes v2.7.0

- **b-form-file:** fix value prop validation when using directory mode (fixes
  [#4912](https://github.com/bootstrap-vue/bootstrap-vue/issues/4912))
  ([#4913](https://github.com/bootstrap-vue/bootstrap-vue/issues/4913))
  ([498a262](https://github.com/bootstrap-vue/bootstrap-vue/commit/498a26219571bb6108aaa7134dc25c8e1ff6c98f))
- **b-form-file:** make sure to catch all errors when resetting the input
  ([#4936](https://github.com/bootstrap-vue/bootstrap-vue/issues/4936))
  ([682bc46](https://github.com/bootstrap-vue/bootstrap-vue/commit/682bc46028cacfdb570fe416a051160ee9789fe2))

### Other v2.7.0

- `deps`: update devDependency rollup to 2.0.x
- minor docs updates

<a name="2.6.1"></a>

## [v2.6.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.6.0...v2.6.1)

Released: 2020-03-06

### Bug Fixes v2.6.1

- **b-form-spinbutton:** respect step value for initial decrement when `wrap` enabled (closes
  [#4884](https://github.com/bootstrap-vue/bootstrap-vue/issues/4884))
  ([#4885](https://github.com/bootstrap-vue/bootstrap-vue/issues/4885))
  ([28e7245](https://github.com/bootstrap-vue/bootstrap-vue/commit/28e724536be4762382328648f203bd46d8f52fdc))

### Other v2.6.1

- documentation updates and fixes
- dev dependency updates

<a name="2.6.0"></a>

## [v2.6.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.5.0...v2.6.0)

Released: 2020-03-05

### Features v2.6.0

- **b-calendar, b-form-datepicker:** allow customization of in-component displayed date format
  (closes [#4797](https://github.com/bootstrap-vue/bootstrap-vue/issues/4797))
  ([#4835](https://github.com/bootstrap-vue/bootstrap-vue/issues/4835))
  ([85c7e75](https://github.com/bootstrap-vue/bootstrap-vue/commit/85c7e759bc78d2ffb5b026cb5ee484b2567136aa))
- **b-form-datepicker:** add `button-content` optionally scoped slot for calendar icon
  ([#4795](https://github.com/bootstrap-vue/bootstrap-vue/issues/4795))
  ([7a00910](https://github.com/bootstrap-vue/bootstrap-vue/commit/7a0091099025d8bdcf953b00d8619726b54fa937))
- **b-form-datepicker:** add `calendar-width` prop (closes
  [#4817](https://github.com/bootstrap-vue/bootstrap-vue/issues/4817))
  ([#4822](https://github.com/bootstrap-vue/bootstrap-vue/issues/4822))
  ([91b77bc](https://github.com/bootstrap-vue/bootstrap-vue/commit/91b77bc9a6b1a4796698ce3185c0b354156ce563))
- **b-pagination, b-pagination-nav:** improve aria accessibility - changes to inner structure and
  aria attributes (closes: [#4811](https://github.com/bootstrap-vue/bootstrap-vue/issues/4811),
  [#4160](https://github.com/bootstrap-vue/bootstrap-vue/issues/4160))
  ([#4810](https://github.com/bootstrap-vue/bootstrap-vue/issues/4810))
  ([7ee4baa](https://github.com/bootstrap-vue/bootstrap-vue/commit/7ee4baa9a843411cd30a3ee499fc7272b7cf48f2))
- **b-tabs:** add ability to provide custom tab button attributes (closes:
  [#4803](https://github.com/bootstrap-vue/bootstrap-vue/issues/4803))
  ([#4806](https://github.com/bootstrap-vue/bootstrap-vue/issues/4806))
  ([c541d3d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c541d3d89ae88f3193305b61ae8ddc735aa6ec03))
- **b-time, b-form-timepicker:** new components `b-time` and `b-form-timepicker`
  ([#4783](https://github.com/bootstrap-vue/bootstrap-vue/issues/4783))
  ([417ef8f](https://github.com/bootstrap-vue/bootstrap-vue/commit/417ef8f2165e68d182e942219d847511b0fd6e9c))

### Bug Fixes v2.6.0

- **b-form-datepicker:** menu focus handling for Firefox and Safari on MacOS, and fix v-model update
  issue (closes [#4814](https://github.com/bootstrap-vue/bootstrap-vue/issues/4814),
  [#4827](https://github.com/bootstrap-vue/bootstrap-vue/issues/4827))
  ([#4824](https://github.com/bootstrap-vue/bootstrap-vue/issues/4824))
  ([09fa920](https://github.com/bootstrap-vue/bootstrap-vue/commit/09fa920e4a904c6340c60586b40451dce94efc44))
- **b-form-spinbutton:** prevent buttons from re-ordering when parent element is RTL
  ([#4802](https://github.com/bootstrap-vue/bootstrap-vue/issues/4802))
  ([ae2cce9](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae2cce9d593bd310b3d2256ade41df0243447970))
- **b-form-spinbutton:** prevent double increment/decrement on mobile (fixes
  [#4838](https://github.com/bootstrap-vue/bootstrap-vue/issues/4838))
  ([#4842](https://github.com/bootstrap-vue/bootstrap-vue/issues/4842))
  ([9c2c700](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c2c700a91d7a6e57572f579f68996eaceda5c00))

### Other v2.6.0

- documentation updates
- dev dependency updates

<a name="2.5.0"></a>

## [v2.5.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.4.2...v2.5.0)

Released: 2020-02-18

### Features v2.5.0

- **b-calendar, b-form-datepicker:** new components `b-calendar` and `b-form-datepicker` (closes
  [#3676](https://github.com/bootstrap-vue/bootstrap-vue/issues/3676),
  [#1428](https://github.com/bootstrap-vue/bootstrap-vue/issues/1428))
  ([#4712](https://github.com/bootstrap-vue/bootstrap-vue/issues/4712))
  ([af0ded0](https://github.com/bootstrap-vue/bootstrap-vue/commit/af0ded0a3bdc9d69653e9c55f874d550e4909662))
- **b-form-spinbutton:** new form control component `b-form-spinbutton`
  ([#4744](https://github.com/bootstrap-vue/bootstrap-vue/issues/4744))
  ([da5e473](https://github.com/bootstrap-vue/bootstrap-vue/commit/da5e473bee8866f2940e027e5e7e87e3a2ff8f11))
- **v-b-hover:** new directive for reacting to hover changes
  ([#4771](https://github.com/bootstrap-vue/bootstrap-vue/issues/4771))
  ([b7adc6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/b7adc6dc726f75c0578b3de5208f112bef58b4ad))

### Bug Fixes v2.5.0

- **b-form-tags:** improve accessibility for screen reader users
  ([#4775](https://github.com/bootstrap-vue/bootstrap-vue/issues/4775))
  ([2328630](https://github.com/bootstrap-vue/bootstrap-vue/commit/2328630542defc395912165a964a95107f8a4ba9))
- **b-modal:** additional fixes for show transition behaviour (closes
  [#4761](https://github.com/bootstrap-vue/bootstrap-vue/issues/4761))
  ([#4777](https://github.com/bootstrap-vue/bootstrap-vue/issues/4777))
  ([1113c6f](https://github.com/bootstrap-vue/bootstrap-vue/commit/1113c6f951d86b7e6e6ba2161f935d2b6e0b5ce8))

### Other v2.5.0

- documentation updates
- documentation accessibility improvements
- dev dependency updates

<a name="2.4.2"></a>

## [v2.4.2](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.4.1...v2.4.2)

Released: 2020-02-15

### Bug Fixes v2.4.2

- **b-button:** when `href` is "#" add `role=button` and appropriate keydown handlers for A11Y
  ([#4768](https://github.com/bootstrap-vue/bootstrap-vue/issues/4768))
  ([087a128](https://github.com/bootstrap-vue/bootstrap-vue/commit/087a1283977061c44d5b059c203f13d2326dabae))
- **b-modal:** fix transition show enter timing (closes
  [#4761](https://github.com/bootstrap-vue/bootstrap-vue/issues/4761))
  ([#4766](https://github.com/bootstrap-vue/bootstrap-vue/issues/4766))
  ([968c957](https://github.com/bootstrap-vue/bootstrap-vue/commit/968c95758e45610a8c002507790c79d87d8fe956))

### Other v2.4.2

- documentation updates
- dev dependency updates

<a name="2.4.1"></a>

## [v2.4.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.4.0...v2.4.1)

Released: 2020-02-12

### Bug Fixes v2.4.1

- **b-form-input, b-form-textarea:** handle change event for all mobile device keyboards (closes
  [#4724](https://github.com/bootstrap-vue/bootstrap-vue/issues/4724))
  ([#4739](https://github.com/bootstrap-vue/bootstrap-vue/issues/4739))
  ([166a932](https://github.com/bootstrap-vue/bootstrap-vue/commit/166a932fb11fa552714aba7df67992e1265b9047))
- **b-tooltip, v-b-tooltip:** fix arrow margin
  ([#4727](https://github.com/bootstrap-vue/bootstrap-vue/issues/4727))
  ([865a655](https://github.com/bootstrap-vue/bootstrap-vue/commit/865a6557fbf49115c05326f9a96c4f9fdf135e96))

### Other v2.4.1

- dev dependency updates
- minor docs updates

<a name="2.4.0"></a>

## [v2.4.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.3.0...v2.4.0)

Released: 2020-02-01

### Features v2.4.0

- **b-modal:** add `ignore-enforce-focus-selector` prop (closes
  [#4537](https://github.com/bootstrap-vue/bootstrap-vue/issues/4537))
  ([#4702](https://github.com/bootstrap-vue/bootstrap-vue/issues/4702))
  ([c3ac992](https://github.com/bootstrap-vue/bootstrap-vue/commit/c3ac99283927b5261d1df05d3c479c534011d7c5))
- **b-nav-item-dropdown:** add `boundary` prop, applicable when not in `b-navbar` (closes
  [#4684](https://github.com/bootstrap-vue/bootstrap-vue/issues/4684))
  ([#4691](https://github.com/bootstrap-vue/bootstrap-vue/issues/4691))
  ([3a50ad8](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a50ad85e85e1c6dc55a36665062180687078708))

### Bug Fixes v2.4.0

- **b-dropdown:** focus-in handling for Safari and Firefox on macOS/iOS (closes
  [#4328](https://github.com/bootstrap-vue/bootstrap-vue/issues/4328))
  ([#4426](https://github.com/bootstrap-vue/bootstrap-vue/issues/4426))
  ([2eab55b](https://github.com/bootstrap-vue/bootstrap-vue/commit/2eab55b4672a35a487b30f0f64c63b887b361473))
- **b-form-input, b-form-textarea:** properly handle out-of-sync values (closes
  [#4695](https://github.com/bootstrap-vue/bootstrap-vue/issues/4695))
  ([#4701](https://github.com/bootstrap-vue/bootstrap-vue/issues/4701))
  ([954176d](https://github.com/bootstrap-vue/bootstrap-vue/commit/954176d733dccdd074f5b6cb31c4041081a3b206))

<a name="2.3.0"></a>

## [v2.3.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.2.2...v2.3.0)

Released: 2020-01-24

### Features v2.3.0

- **b-button-close:** add `content` prop
  ([#4574](https://github.com/bootstrap-vue/bootstrap-vue/issues/4574))
  ([7379c6d](https://github.com/bootstrap-vue/bootstrap-vue/commit/7379c6dd0bac76307720645080741b3b0ed7ed99))
- **b-form-tags:** new option to specify input type (closes
  [#4644](https://github.com/bootstrap-vue/bootstrap-vue/issues/4644))
  ([#4645](https://github.com/bootstrap-vue/bootstrap-vue/issues/4645))
  ([b899fac](https://github.com/bootstrap-vue/bootstrap-vue/commit/b899faceb4c1fd8562454fa93432e70d7113401b))
- **b-pagination, b-pagination-nav:** add page button class props and option to show first/last page
  numbers (closes [#4597](https://github.com/bootstrap-vue/bootstrap-vue/issues/4597),
  [#4533](https://github.com/bootstrap-vue/bootstrap-vue/issues/4533))
  ([#4622](https://github.com/bootstrap-vue/bootstrap-vue/issues/4622))
  ([3a3ee1d](https://github.com/bootstrap-vue/bootstrap-vue/commit/3a3ee1dc9312a1a8c530a5ea42d1d239d5a24351))
- **icons:** add stacking support
  ([#4658](https://github.com/bootstrap-vue/bootstrap-vue/issues/4658))
  ([b185cdb](https://github.com/bootstrap-vue/bootstrap-vue/commit/b185cdb686ddddcde1b98585b1fbc48859fc541a))

### Bug Fixes v2.3.0

- **v-b-modal:** only unbind/rebind during componentUpdated hook if trigger element or modal ID
  changes (closes [#4669](https://github.com/bootstrap-vue/bootstrap-vue/issues/4669))
  ([#4672](https://github.com/bootstrap-vue/bootstrap-vue/issues/4672))
  ([e53a05d](https://github.com/bootstrap-vue/bootstrap-vue/commit/e53a05d960a9de0ca9636ee31e0197e7e554ddbc))
- **utils:** pass all Array/Object util shortcuts as functions, for handling late loaded polyfills
  ([#4647](https://github.com/bootstrap-vue/bootstrap-vue/issues/4647))
  ([f584425](https://github.com/bootstrap-vue/bootstrap-vue/commit/f5844256a03d2f4b8006900419acfa2c5e3803c3))

<a name="2.2.2"></a>

## [v2.2.2](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.2.1...v2.2.2)

Released: 2020-01-15

### Bug Fixes v2.2.2

- **nuxt module:** remove unnecessary export statements
  ([#4624](https://github.com/bootstrap-vue/bootstrap-vue/issues/4624))
  ([27f066c](https://github.com/bootstrap-vue/bootstrap-vue/commit/27f066cfa07ee311fe1e312d9a9ebd0eb76750c7))

### Other v2.2.2

- dev dependencies updates
- minor docs updates

<a name="2.2.1"></a>

## [v2.2.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.2.0...v2.2.1)

Released: 2020-01-13

### Bug Fixes v2.2.1

- **icons:** make icon transform props work with IE 11 (closes
  [#4607](https://github.com/bootstrap-vue/bootstrap-vue/issues/4607))
  ([#4608](https://github.com/bootstrap-vue/bootstrap-vue/issues/4608))
  ([899779f](https://github.com/bootstrap-vue/bootstrap-vue/commit/899779f20015f719198a763136137eea01aa11ea))
- **types:** add missing declarations for `b-form-select-option` & `b-form-select-option-group`
  ([#4595](https://github.com/bootstrap-vue/bootstrap-vue/issues/4595))
  ([8d60832](https://github.com/bootstrap-vue/bootstrap-vue/commit/8d60832d38e74231a4bda15aa045b84aae97d2ed))
- **types:** include named export BootstrapVue in declaration file
  ([#4590](https://github.com/bootstrap-vue/bootstrap-vue/issues/4590))
  ([603307a](https://github.com/bootstrap-vue/bootstrap-vue/commit/603307aeccf6141b94eff2186baee4ec43439033))
- **modal, tooltips, popovers**: remove `nextTick` delay when updating content in transporter portal
  (closes [#4589](https://github.com/bootstrap-vue/bootstrap-vue/issues/4589))
  ([#4604](https://github.com/bootstrap-vue/bootstrap-vue/issues/4604))
  ([0e3e7e0](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e3e7e03370685367ac69949e596c9fff5c68163))
- **utils:** correct `identity` spelling error
  ([#4579](https://github.com/bootstrap-vue/bootstrap-vue/issues/4579))
  ([7fed191](https://github.com/bootstrap-vue/bootstrap-vue/commit/7fed1911d6d9f7eae81526010483c71e1679e770))

### Docs v2.2.1

- add live validation examples in validation reference section
  ([#4584](https://github.com/bootstrap-vue/bootstrap-vue/issues/4584))
  ([aca4a5c](https://github.com/bootstrap-vue/bootstrap-vue/commit/aca4a5c8f9a9ed0d7526de396ff072f0c1f4ebdf))

### Other v2.2.1

- dev dependencies updates

<a name="2.2.0"></a>

## [v2.2.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.1.0...v2.2.0)

Released: 2020-01-08

### Overview v2.2.0

- New optional icon components based on `BootstrapIcons v1.0.0-alpha2`
- New tagged input component `<b-form-tags>`
- Support for `Bootstrap v4.4.1` CSS/SCSS

### Features v2.2.0

- **icons:** new optional icon components
  ([#4489](https://github.com/bootstrap-vue/bootstrap-vue/issues/4489))
  ([d2bef17](https://github.com/bootstrap-vue/bootstrap-vue/commit/d2bef1715636fcb83de6d51808683e6feda671d0))
- **b-collapse:** add new prop `appear` to animate an initially visible collapse
  ([#4317](https://github.com/bootstrap-vue/bootstrap-vue/issues/4317))
  ([136a72b](https://github.com/bootstrap-vue/bootstrap-vue/commit/136a72b0352d4bb1339ab31f791087cbcda42fa5))
- **b-collapse:** add optional scoping to default slot
  ([#4405](https://github.com/bootstrap-vue/bootstrap-vue/issues/4405))
  ([8e95bac](https://github.com/bootstrap-vue/bootstrap-vue/commit/8e95bacf9d00562f2676689d067ae0db009cbbb6))
- **b-container:** add support for Bootstrap v4.4.x new responsive containers
  ([0e318f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/0e318f4755e65eb569dcc579938d0d72c02abd62))
- **b-dropdown:** add splitClass property to dropdown component
  ([#4394](https://github.com/bootstrap-vue/bootstrap-vue/issues/4394))
  ([a5f342e](https://github.com/bootstrap-vue/bootstrap-vue/commit/a5f342e0e4de2186259e36e42cecda8c20e1c8ab))
- **b-dropdown-form:** new `form-class` prop for adding classes to the form element (closes
  [#4474](https://github.com/bootstrap-vue/bootstrap-vue/issues/4474))
  ([#4475](https://github.com/bootstrap-vue/bootstrap-vue/issues/4475))
  ([eef4200](https://github.com/bootstrap-vue/bootstrap-vue/commit/eef4200976f7921b1bb03f50c0ece8ee7c41ed0e))
- **b-form-select:** add group/tree support and dedicated option and option-group components (closes
  [#3222](https://github.com/bootstrap-vue/bootstrap-vue/issues/3222))
  ([#4267](https://github.com/bootstrap-vue/bootstrap-vue/issues/4267))
  ([f1ed017](https://github.com/bootstrap-vue/bootstrap-vue/commit/f1ed0177c20f9d7e7e340a8815d1b6bc66f7cb76))
- **b-form-select:** support paths for `valueField`, `textField`, `htmlField` and `disabledField`
  props ([#4386](https://github.com/bootstrap-vue/bootstrap-vue/issues/4386))
  ([ed3b736](https://github.com/bootstrap-vue/bootstrap-vue/commit/ed3b7360af415dc3cc56f0b6662c9d48cc165781))
- **b-form-tags:** new tagged input component
  ([#4409](https://github.com/bootstrap-vue/bootstrap-vue/issues/4409))
  ([00eb9d9](https://github.com/bootstrap-vue/bootstrap-vue/commit/00eb9d9fd460adca8227b3b344284b5cc49a734f))
- **b-row:** add Bootstrap v4.4 row columns support
  ([#4439](https://github.com/bootstrap-vue/bootstrap-vue/issues/4439))
  ([833b028](https://github.com/bootstrap-vue/bootstrap-vue/commit/833b028a2d6101d01b7012a7378359db1c801695))
- **b-table:** better sort labeling for screen readers (closes
  [#4487](https://github.com/bootstrap-vue/bootstrap-vue/issues/4487))
  ([#4488](https://github.com/bootstrap-vue/bootstrap-vue/issues/4488))
  ([d4e66fa](https://github.com/bootstrap-vue/bootstrap-vue/commit/d4e66fa48fdd1cd7fd4b93907fe999de3fc577f8))
- **b-table, b-table-lite:** new `tbody-tr-attr` prop for arbitrary row attributes (closes
  [#1864](https://github.com/bootstrap-vue/bootstrap-vue/issues/1864))
  ([#4481](https://github.com/bootstrap-vue/bootstrap-vue/issues/4481))
  ([4acf6ed](https://github.com/bootstrap-vue/bootstrap-vue/commit/4acf6ed863dd5edd85897a01b099c42322097d1b))
- **b-tooltip:** add `noninteractive` prop (closes
  [#4556](https://github.com/bootstrap-vue/bootstrap-vue/issues/4556))
  ([#4563](https://github.com/bootstrap-vue/bootstrap-vue/issues/4563))
  ([b3ad726](https://github.com/bootstrap-vue/bootstrap-vue/commit/b3ad7264d9b10fb1b8dfba70c62eed11a56519d6))
- **build:** configure pre-commit hook (closes
  [#4532](https://github.com/bootstrap-vue/bootstrap-vue/issues/4532))
  ([#4552](https://github.com/bootstrap-vue/bootstrap-vue/issues/4552))
  ([1bf9e59](https://github.com/bootstrap-vue/bootstrap-vue/commit/1bf9e59e8888a7a2cd6f135665103419f603a32d))

### Bug Fixes v2.2.0

- **b-table, b-table-lite:** handle edge case with row events when table is removed from dom.
  instantiate row event handlers only when listeners are registered (fixes
  [#4384](https://github.com/bootstrap-vue/bootstrap-vue/issues/4384))
  ([#4388](https://github.com/bootstrap-vue/bootstrap-vue/issues/4388))
  ([9a81cd4](https://github.com/bootstrap-vue/bootstrap-vue/commit/9a81cd414a2c534b96de0d82c3d00d94651e5a7b))
- **b-toast:** fix internal `ensureToaster` method call when toaster name changes
  ([#4468](https://github.com/bootstrap-vue/bootstrap-vue/issues/4468))
  ([744bb7a](https://github.com/bootstrap-vue/bootstrap-vue/commit/744bb7a77092a04184af31bf285e432110e1ab44))
- **tooltips, popovers:** fix memory leak (closes
  [#4400](https://github.com/bootstrap-vue/bootstrap-vue/issues/4400))
  ([#4401](https://github.com/bootstrap-vue/bootstrap-vue/issues/4401))
  ([c71352d](https://github.com/bootstrap-vue/bootstrap-vue/commit/c71352d674347e5e2d72fe8b82334fc87a4ffd8c))
- **docs:** handle undocumented breaking changes in babel-standalone for IE 11
  ([#4484](https://github.com/bootstrap-vue/bootstrap-vue/issues/4484))
  ([56f8bb5](https://github.com/bootstrap-vue/bootstrap-vue/commit/56f8bb5af7fb7188da035210e8be28d7ae1c7bc1))

<a name="2.1.0"></a>

## [v2.1.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.0.4...v2.1.0)

Released: 2019-11-12

### Features v2.1.0

- auto-generate file `web-types.json` for WebStorm, and files `vetur-tags.json` and
  `vetur-attributes.json` for Vetur (closes
  [#4107](https://github.com/bootstrap-vue/bootstrap-vue/issues/4107))
  ([#4110](https://github.com/bootstrap-vue/bootstrap-vue/issues/4110))
  ([1a3e6a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/1a3e6a5))
- **b-dropdown:** add `block` support to toggle button (closes
  [#4266](https://github.com/bootstrap-vue/bootstrap-vue/issues/4266))
  ([#4269](https://github.com/bootstrap-vue/bootstrap-vue/issues/4269))
  ([30029e3](https://github.com/bootstrap-vue/bootstrap-vue/commit/30029e3))
- **b-form-group:** allow setting label cols props to `auto` (closes
  [#4217](https://github.com/bootstrap-vue/bootstrap-vue/issues/4217))
  ([#4218](https://github.com/bootstrap-vue/bootstrap-vue/issues/4218))
  ([21a822b](https://github.com/bootstrap-vue/bootstrap-vue/commit/21a822b))
- **b-form-input, b-form-textarea:** add `lazy` modifier prop to update v-model on change/blur event
  ([#4169](https://github.com/bootstrap-vue/bootstrap-vue/issues/4169))
  ([55787dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/55787dd))
- **b-form-input, b-form-textarea:** add `v-model` debouncing feature, and deprecate `<b-table>`
  prop `filter-debounce` (closes
  [#4150](https://github.com/bootstrap-vue/bootstrap-vue/issues/4150))
  ([#4314](https://github.com/bootstrap-vue/bootstrap-vue/issues/4314))
  ([3ecdfa2](https://github.com/bootstrap-vue/bootstrap-vue/commit/3ecdfa2))
- **b-img, b-img-lazy:** add support for `srcset` and `sizes` props (closes
  [#4348](https://github.com/bootstrap-vue/bootstrap-vue/issues/4348))
  ([#4350](https://github.com/bootstrap-vue/bootstrap-vue/issues/4350))
  ([f419cb4](https://github.com/bootstrap-vue/bootstrap-vue/commit/f419cb4))
- **b-pagination, b-pagination-nav:** add `pills` style option
  ([#4236](https://github.com/bootstrap-vue/bootstrap-vue/issues/4236))
  ([605d4c4](https://github.com/bootstrap-vue/bootstrap-vue/commit/605d4c4))
- **b-table:** add `selectRow()` and `unselectRow()` methods to cell and row-details slot scopes,
  and new prop `no-select-on-click`
  ([#4283](https://github.com/bootstrap-vue/bootstrap-vue/issues/4283))
  ([64b881f](https://github.com/bootstrap-vue/bootstrap-vue/commit/64b881f))
- **b-table:** default the row select feature `selected-variant` to the `active` variant
  ([#4128](https://github.com/bootstrap-vue/bootstrap-vue/issues/4128))
  ([af372b0](https://github.com/bootstrap-vue/bootstrap-vue/commit/af372b0))
- **b-table, b-table-lite:** add in head/foot row variant prop (addresses
  [#4215](https://github.com/bootstrap-vue/bootstrap-vue/issues/4215))
  ([#4216](https://github.com/bootstrap-vue/bootstrap-vue/issues/4216))
  ([b222c7c](https://github.com/bootstrap-vue/bootstrap-vue/commit/b222c7c))
- **b-table, b-table-lite:** add prop `details-td-class` for applying classes to the details row
  `<td>` ([#4276](https://github.com/bootstrap-vue/bootstrap-vue/issues/4276))
  ([702a1ef](https://github.com/bootstrap-vue/bootstrap-vue/commit/702a1ef))
- **b-tabs:** emit cancelable BvEvent before changing tabs via new `activate-tab` event (closes
  [#4273](https://github.com/bootstrap-vue/bootstrap-vue/issues/4273))
  ([#4274](https://github.com/bootstrap-vue/bootstrap-vue/issues/4274))
  ([9b195dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/9b195dd))
- **v-b-visible:** make `v-b-visible` directive available for public use
  ([#4318](https://github.com/bootstrap-vue/bootstrap-vue/issues/4318))
  ([5fa7e22](https://github.com/bootstrap-vue/bootstrap-vue/commit/5fa7e22))

### Bug Fixes v2.1.0

- **b-dropdown:** handle issue with touch devices on MacOS using Safari/Firefox (Fixes
  [#4328](https://github.com/bootstrap-vue/bootstrap-vue/issues/4328),
  [#4344](https://github.com/bootstrap-vue/bootstrap-vue/issues/4344))
  ([#4329](https://github.com/bootstrap-vue/bootstrap-vue/issues/4329))
  ([2779a0a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2779a0a))
- **b-nav-form, b-nav-text:** ensure these sub-components have `<li>` as root element for
  accessibility ([#4100](https://github.com/bootstrap-vue/bootstrap-vue/issues/4100))
  ([6774800](https://github.com/bootstrap-vue/bootstrap-vue/commit/6774800))
- **b-pagination, b-pagination-nav:** add UP/DOWN keyboard navigation support for JAWS (fixes
  [#4322](https://github.com/bootstrap-vue/bootstrap-vue/issues/4322))
  ([#4325](https://github.com/bootstrap-vue/bootstrap-vue/issues/4325))
  ([c686088](https://github.com/bootstrap-vue/bootstrap-vue/commit/c686088))
- **b-table, b-table-lite, b-table-simple:** fix issue with sticky columns when table is not
  responsive but has sticky headers (fixes
  [#4354](https://github.com/bootstrap-vue/bootstrap-vue/issues/4354))
  ([#4356](https://github.com/bootstrap-vue/bootstrap-vue/issues/4356))
  ([56b3958](https://github.com/bootstrap-vue/bootstrap-vue/commit/56b3958))
- **b-table, b-table-lite, b-tbody:** fix delegated event handlers when transition + minor
  adjustment to row `key` generation (fixes
  [#4370](https://github.com/bootstrap-vue/bootstrap-vue/issues/4370),
  [#4360](https://github.com/bootstrap-vue/bootstrap-vue/issues/4360))
  ([#4372](https://github.com/bootstrap-vue/bootstrap-vue/issues/4372))
  ([030a3d8](https://github.com/bootstrap-vue/bootstrap-vue/commit/030a3d8))
- **b-tabs:** allow space to trigger tab activation when `no-key-nav` is enabled (fixes
  [#4323](https://github.com/bootstrap-vue/bootstrap-vue/issues/4323))
  ([#4326](https://github.com/bootstrap-vue/bootstrap-vue/issues/4326))
  ([731365b](https://github.com/bootstrap-vue/bootstrap-vue/commit/731365b))
- **v-b-modal:** ensure trigger element is keyboard accessible if not a link or button, for A11Y
  ([#4365](https://github.com/bootstrap-vue/bootstrap-vue/issues/4365))
  ([f54ca29](https://github.com/bootstrap-vue/bootstrap-vue/commit/f54ca29))
- **v-b-modal:** open modal using `ENTER` key on non-button elements for A11Y
  ([#4364](https://github.com/bootstrap-vue/bootstrap-vue/issues/4364))
  ([0d27d7b](https://github.com/bootstrap-vue/bootstrap-vue/commit/0d27d7b))
- **v-b-tooltip, v-b-popover:** ensure reference to trigger element is passed to title/content
  function (fixes [#4331](https://github.com/bootstrap-vue/bootstrap-vue/issues/4331))
  ([#4332](https://github.com/bootstrap-vue/bootstrap-vue/issues/4332))
  ([ea0cbda](https://github.com/bootstrap-vue/bootstrap-vue/commit/ea0cbda))
- **v-b-visible:** fix type error in `componentUpdated` hook + minor docs update/fixes
  ([#4327](https://github.com/bootstrap-vue/bootstrap-vue/issues/4327))
  ([5f3ba9e](https://github.com/bootstrap-vue/bootstrap-vue/commit/5f3ba9e))
- **web-types:** update web-types code generation to match latest schema
  ([#4271](https://github.com/bootstrap-vue/bootstrap-vue/issues/4271))
  ([009431e](https://github.com/bootstrap-vue/bootstrap-vue/commit/009431e))

### Other v2.1.0

- **b-table:** deprecate prop `filter-debounce` in favour of `b-form-input` debouncing
- documentation updates and fixes

<a name="2.0.4"></a>

## [v2.0.4](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.0.3...v2.0.4)

Released: 2019-10-11

### Bug Fixes v2.0.4

- **b-carousel:** disable the next/prev controls when the carousel is sliding (closes
  [#4210](https://github.com/bootstrap-vue/bootstrap-vue/issues/4210))
  ([#4212](https://github.com/bootstrap-vue/bootstrap-vue/issues/4212))
  ([64d556d](https://github.com/bootstrap-vue/bootstrap-vue/commit/64d556d))
- **b-dropdown-form:** fix SCSS styling when placed in a nav dropdown (fixes
  [#4220](https://github.com/bootstrap-vue/bootstrap-vue/issues/4220))
  ([#4223](https://github.com/bootstrap-vue/bootstrap-vue/issues/4223))
  ([b852bba](https://github.com/bootstrap-vue/bootstrap-vue/commit/b852bba))
- **types:** correct the declared export name for `BCardSubTitle` component
  ([#4229](https://github.com/bootstrap-vue/bootstrap-vue/issues/4229))
  ([9f216df](https://github.com/bootstrap-vue/bootstrap-vue/commit/9f216df))

### Performance v2.0.4

- **b-table, b-table-lite:** improve render performance for large tables (closes
  [#4211](https://github.com/bootstrap-vue/bootstrap-vue/issues/4211),
  [#4155](https://github.com/bootstrap-vue/bootstrap-vue/issues/4155))
  ([#4213](https://github.com/bootstrap-vue/bootstrap-vue/issues/4213))
  ([f3f42f2](https://github.com/bootstrap-vue/bootstrap-vue/commit/f3f42f2))

### Other v2.0.4

- add `"sass"` entry in `package.json`
- minor docs fixes and updates

<a name="2.0.3"></a>

## [v2.0.3](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.0.2...v2.0.3)

Released: 2019-10-05

### Bug Fixes v2.0.3

- **b-form-file:** fix prop type checking for `value` prop
  ([#4168](https://github.com/bootstrap-vue/bootstrap-vue/issues/4168))
  ([a8e2e56](https://github.com/bootstrap-vue/bootstrap-vue/commit/a8e2e56))
- **b-nav-item-dropdown:** focus-out handling when new focus comes from another `dropdown-toggle`
  (closes [#4113](https://github.com/bootstrap-vue/bootstrap-vue/issues/4113))
  ([#4139](https://github.com/bootstrap-vue/bootstrap-vue/issues/4139))
  ([9c37875](https://github.com/bootstrap-vue/bootstrap-vue/commit/9c37875))
- **b-table:** minor code optimizations to filter debouncing
  ([#4167](https://github.com/bootstrap-vue/bootstrap-vue/issues/4167))
  ([018eef1](https://github.com/bootstrap-vue/bootstrap-vue/commit/018eef1))
- **b-table, b-table-lite, b-table-simple:** disable sticky header max-height on printers / print
  media ([#4147](https://github.com/bootstrap-vue/bootstrap-vue/issues/4147))
  ([24c62c5](https://github.com/bootstrap-vue/bootstrap-vue/commit/24c62c5))
- **b-tooltip, b-popover:** add `SVGElement` as acceptable prop type (closes
  [#4173](https://github.com/bootstrap-vue/bootstrap-vue/issues/4173))
  ([#4174](https://github.com/bootstrap-vue/bootstrap-vue/issues/4174))
  ([fab7fea](https://github.com/bootstrap-vue/bootstrap-vue/commit/fab7fea))
- **v-b-modal:** bind to inner link or button for dropdown items or nav items (fixes
  [#4149](https://github.com/bootstrap-vue/bootstrap-vue/issues/4149))
  ([#4187](https://github.com/bootstrap-vue/bootstrap-vue/issues/4187))
  ([5c28bd2](https://github.com/bootstrap-vue/bootstrap-vue/commit/5c28bd2))

### Performance v2.0.3

- **b-table, b-table-lite:** delegate row event handlers to the tbody element
  ([#4192](https://github.com/bootstrap-vue/bootstrap-vue/issues/4192))
  ([3f0d46a](https://github.com/bootstrap-vue/bootstrap-vue/commit/3f0d46a))
- **tables:** make `b-th` extend `b-td` instead of using functional wrappers
  ([#4156](https://github.com/bootstrap-vue/bootstrap-vue/issues/4156))
  ([c9715a8](https://github.com/bootstrap-vue/bootstrap-vue/commit/c9715a8))
- **tables:** improve provide/inject performance (addresses
  [#4155](https://github.com/bootstrap-vue/bootstrap-vue/issues/4155))
  ([#4164](https://github.com/bootstrap-vue/bootstrap-vue/issues/4164))
  ([152fefc](https://github.com/bootstrap-vue/bootstrap-vue/commit/152fefc))

### Docs v2.0.3

- add prop descriptions to component reference tables (closes
  [#3647](https://github.com/bootstrap-vue/bootstrap-vue/issues/3647))
  ([#4161](https://github.com/bootstrap-vue/bootstrap-vue/issues/4161))
  ([fdd2a83](https://github.com/bootstrap-vue/bootstrap-vue/commit/fdd2a83))
- add quick links (page table of contents) to docs pages for small screens, and add table of
  contents to section index pages (instead of a redirect to first child page)
  ([#4145](https://github.com/bootstrap-vue/bootstrap-vue/issues/4145))
  ([22268aa](https://github.com/bootstrap-vue/bootstrap-vue/commit/22268aa))

<a name="2.0.2"></a>

## [v2.0.2](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.0.1...v2.0.2)

Released: 2019-09-20

This patch release includes a few minor bug fixes and documentation updates.

### Bug Fixes v2.0.2

- **b-popover, b-tooltip:** ensure prop `boundary-padding` is passed to popper instance (fixes
  [#4131](https://github.com/bootstrap-vue/bootstrap-vue/issues/4131))
  ([#4133](https://github.com/bootstrap-vue/bootstrap-vue/issues/4133))
  ([a54a647](https://github.com/bootstrap-vue/bootstrap-vue/commit/a54a647))
- **b-collapse:** make `id` prop not required
  ([#4109](https://github.com/bootstrap-vue/bootstrap-vue/issues/4109))
  ([4f935ce](https://github.com/bootstrap-vue/bootstrap-vue/commit/4f935ce))
- **tables:** add in missing Bootstrap variant class `bg-active` for dark tables
  ([#4098](https://github.com/bootstrap-vue/bootstrap-vue/issues/4098))
  ([d9900ab](https://github.com/bootstrap-vue/bootstrap-vue/commit/d9900ab))
- **tables:** ensure row variant `active` (class `table-active`) takes precedence over other row
  variants (addresses [#3008](https://github.com/bootstrap-vue/bootstrap-vue/issues/3008))
  ([#4127](https://github.com/bootstrap-vue/bootstrap-vue/issues/4127))
  ([fdb8bb6](https://github.com/bootstrap-vue/bootstrap-vue/commit/fdb8bb6))
- **tooltips, popovers:** hide trigger element `title` attribute during show delay (fixes
  [#4114](https://github.com/bootstrap-vue/bootstrap-vue/issues/4114))
  ([#4120](https://github.com/bootstrap-vue/bootstrap-vue/issues/4120))
  ([2dd8d5a](https://github.com/bootstrap-vue/bootstrap-vue/commit/2dd8d5a))

<a name="2.0.1"></a>

## [v2.0.1](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.0.0...v2.0.1)

Released: 2019-09-13

This patch release includes a few minor bug fixes and documentation updates.

### Bug Fixes v2.0.1

- **b-media:** fix vertical align class when `top` or `bottom` selected (fixes
  [#4052](https://github.com/bootstrap-vue/bootstrap-vue/issues/4052))
  ([#4055](https://github.com/bootstrap-vue/bootstrap-vue/issues/4055))
  ([9ccfe4c](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ccfe4c))
- **b-table:** handle filter as an object when using items provider, and prevent duplicate provider
  calls on mount (fixes [#4065](https://github.com/bootstrap-vue/bootstrap-vue/issues/4065))
  ([#4068](https://github.com/bootstrap-vue/bootstrap-vue/issues/4068))
  ([9ddd115](https://github.com/bootstrap-vue/bootstrap-vue/commit/9ddd115))
- **b-table:** remove extra slashes in mixins imports
  ([#4087](https://github.com/bootstrap-vue/bootstrap-vue/issues/4087))
  ([77f5be1](https://github.com/bootstrap-vue/bootstrap-vue/commit/77f5be1))
- **tooltips, popovers:** check `document.body` instead of `document` for IE 11 support (fixes
  [#4074](https://github.com/bootstrap-vue/bootstrap-vue/issues/4074))
  ([#4075](https://github.com/bootstrap-vue/bootstrap-vue/issues/4075))
  ([1eda4fe](https://github.com/bootstrap-vue/bootstrap-vue/commit/1eda4fe))
- **v-b-tooltip, v-b-popover:** add missing `disabled` config option
  ([#4057](https://github.com/bootstrap-vue/bootstrap-vue/issues/4057))
  ([f488dc1](https://github.com/bootstrap-vue/bootstrap-vue/commit/f488dc1))
- **v-b-tooltip, v-b-popover:** don't show if no title/content provided (closes
  [#4064](https://github.com/bootstrap-vue/bootstrap-vue/issues/4064))
  ([#4076](https://github.com/bootstrap-vue/bootstrap-vue/issues/4076))
  ([0b7de29](https://github.com/bootstrap-vue/bootstrap-vue/commit/0b7de29))

<a name="2.0.0"></a>

## [v2.0.0](https://github.com/bootstrap-vue/bootstrap-vue/compare/v2.0.0-rc.28...v2.0.0)

Released: 2019-09-06

> **BootstrapVue 2.0.0 stable** introduces several new features and bug fixes. Please note that this
> release also _includes several breaking changes_.

**Notable improvements:**

- Tooltips and popovers have been completely re-written for better reactivity and stability. The
  directive versions are now reactive to trigger element `title` attribute changes and configuration
  changes. The component versions now perform better when quickly hovering/un-hovering the trigger
  element. Component and directive versions now have a default delay of `50`ms (affects `'hover'`
  and `'focus'` triggers only). They can now have a trigger of `'manual'` (when used by itself) of
  which they can only be opened or closed programmatically. Users can now optionally specify the ID
  that the tooltip or popover uses. For accessibility reasons, the `title` attribute is removed from
  the trigger element (target) only when the tooltip or popover is showing, and is restored when
  hidden.
- Modals, tooltips, popovers, and toasts now work with scoped style classes (requires the use of
  vue-loader's `/deep/`, `::v-deep` or `>>>`
  [deep selectors](https://vue-loader.vuejs.org/guide/scoped-css.html#child-component-root-elements)
  for targeting inner elements, just like with any other component).
- New SVG background image based sorting indicator icons for `<b-table>`, with the ability to place
  them on either the right (default) or left of the table cell headers (via a new prop).
- Programmatic selection of `<b-table>` selectable rows.
- Ability to provide your own custom footer structure for `<b-table>` and `<b-table-lite>`.

### Breaking changes and deprecated features removal v2.0.0

**Please carefully read the following before upgrading to v2.0.0 stable!**

- Vue `2.6`+ is now **required** at a minimum, `2.6.10`+ is recommended. Some components will fail
  to work as expected if using Vue `2.5` (notably tooltips and popovers, but other components may be
  affected as well).
- All **deprecated features** have been removed in v2.0.0 stable in order to reduce bundle size and
  simplify code.

**Two notable breaking changes are:**

- **changes to the table slot naming syntax:** the table slot syntax introduced in rc.28 has been
  modified in v2.0.0 stable for better compatibility with the new Vue `v-slot` syntax and its
  limitations (which currently are not documented in the Vue.JS docs).
- **the removal of the deprecated `/es` build directory:** Users should now be importing the new
  top-level named exports when importing individual components, directives, and plugins.

Read the following migration guide for more details.

### Migration guide v2.0.0

- **Removal of the deprecated `/es` build directory**. Users should now be using the new simplified
  import syntax introduced in v2.0.0-rc.22. Users should be importing the top-level _named exports_
  instead.
- `b-dropdown`: removal of deprecated `text` slot. Use the `button-content` slot instead.
- `b-form-*` controls, `b-form-group`, `b-form-invalid-feedback` and `b-form-valid-feedback`:
  validation prop `state` now only accepts `true`, `false`, or `null` values. Passing the strings
  `'invalid'` or `'valid'` will no longer work.
- `b-form-group`: removal of the deprecated `horizontal` and `breakpoint` props. Use props
  `label-cols{-{breakpoint}}` instead.
- `b-img-lazy`, `b-card-img-lazy`: now rely only on `IntersectionObserver` support (native or via a
  polyfill) to determine when to show the image. If `IntersectionObserver` support is not detected,
  then the image will _always_ be shown. Use a polyfill if you need to support older browsers (e.g.
  IE 11)
- `b-modal`: the deprecated `BvModalEvent` method `cancel()` has been removed. Use the method
  `preventDefault()` instead.
- `b-modal`: the deprecated `BvModalEvent` property `modalId` has been removed. Use the property
  `componentId` instead.
- `b-nav`: removal of the deprecated `is-nav` prop. Use `b-navbar-nav` component instead when
  placing navs in `b-navbar`.
- `b-nav-item-dropdown`: deprecated props `extra-menu-classes` and `extra-toggle-classes` have been
  removed. Used props `menu-class` and `toggle-class` (respectively) instead.
- `b-table` and `b-table-lite`: **table cell field, header and footer scoped slot naming convention
  has changed**. Users should be using the new table round bracketed slot naming syntax: use slot
  `cell(field)` instead of `field` or `[field]`, use slot `head(field)` instead of `HEAD_field` or
  `HEAD[field]`, use `foot(field)` instead of `FOOT_field` or `FOOT[field]`. This change was
  _required_ for better compatibility with the new Vue `v-slot` syntax. The square bracket syntax
  introduced in `2.0.0-rc.28` has been replaced with the round bracket syntax to reduce possible
  confusion and potential future issues with Vue 2.6's new
  [dynamic slot name](https://vuejs.org/v2/guide/components-slots.html#Dynamic-Slot-Names) syntax.
- `b-table`: the `filter` prop will no longer accept a function reference (previously deprecated).
  Instead, pass a function to the `filter-function` prop when using a custom filter function. The
  prop `filter` is only to be used for the filter's _criteria_ (i.e. the search value, search
  `RegExpr`, etc.).
- `b-table`: passing an object as a `fields` definition will no longer work. Use the _array of
  strings_ or _array of objects_ (or a combination of the two) fields definition format instead.
- `b-table`: sorting icon SASS variables have been changed to handle the new SVG backgrounds. If you
  previously had custom CSS styling/icons, they will not work as expected - but sorting will still
  work. the SVG backgrounds can be controlled via SASS variables.
- `b-tab`: removal of deprecated `href` prop. Use `<b-nav>` for controlling panes that change with
  URL changes.
- `b-tabs`: removal of deprecated `tabs` slot. Use slot `tabs-end` instead.
- `b-tabs`: removal of deprecated `bottom` prop. Use the `end` prop instead.
- Tooltip SCSS: deprecated variable `$bv-tooltip-bg-level` has been removed. Use variable
  `$b-tooltip-bg-level` instead.
- Popover SCSS: deprecated variables `$bv-popover-bg-level`, `$bv-popover-border-level`, and
  `$bv-popover-color-level` have been removed. Use variables `$b-popover-bg-level`,
  `$b-popover-border-level`, and `$b-popover-color-level` (respectively) instead.

Please refer to the [documentation](https://bootstrap-vue3-compat.org/) for the latest usage and
examples, and below for a list of fixes and new features.

### Bug Fixes v2.0.0

- **b-dropdown-\*:** ensure class bindings are placed on root element for all dropdown
  sub-components (closes [#4022](https://github.com/bootstrap-vue/bootstrap-vue/issues/4022))
  ([#4024](https://github.com/bootstrap-vue/bootstrap-vue/issues/4024))
  ([81efb89](https://github.com/bootstrap-vue/bootstrap-vue/commit/81efb89))
- **b-form-textarea:** handle initial auto-height when in modal, tabs, or other component with
  transition or which uses `v-show` (fixes
  [#3936](https://github.com/bootstrap-vue/bootstrap-vue/issues/3936),
  [#3702](https://github.com/bootstrap-vue/bootstrap-vue/issues/3702))
  ([#3937](https://github.com/bootstrap-vue/bootstrap-vue/issues/3937))
  ([be3ac62](https://github.com/bootstrap-vue/bootstrap-vue/commit/be3ac62))
- **b-link:** only add the `nativeOn` property to componentData when rendering a router link
  ([#3976](https://github.com/bootstrap-vue/bootstrap-vue/issues/3976))
  ([62fb0b6](https://github.com/bootstrap-vue/bootstrap-vue/commit/62fb0b6))
- **b-modal:** ensure non-prop attributes are transferred to the modal outer wrapper `div` (closes
  [#3896](https://github.com/bootstrap-vue/bootstrap-vue/issues/3896))
  ([#3921](https://github.com/bootstrap-vue/bootstrap-vue/issues/3921))
  ([8bf3a55](https://github.com/bootstrap-vue/bootstrap-vue/commit/8bf3a55))
- **b-modal:** fix scroll to top issue when modal has `no-fade` set
  ([#4004](https://github.com/bootstrap-vue/bootstrap-vue/issues/4004))
  ([332b79f](https://github.com/bootstrap-vue/bootstrap-vue/commit/332b79f))
- **b-table, b-table-lite:** handle edge case where field slot returns no vNodes (fixes
  [#3919](https://github.com/bootstrap-vue/bootstrap-vue/issues/3919))
  ([#3920](https://github.com/bootstrap-vue/bootstrap-vue/issues/3920))
  ([a392059](https://github.com/bootstrap-vue/bootstrap-vue/commit/a392059))
- **b-table, b-table-lite:** render header when not always stacked mode (fixes
  [#3886](https://github.com/bootstrap-vue/bootstrap-vue/issues/3886))
  ([#3887](https://github.com/bootstrap-vue/bootstrap-vue/issues/3887))
  ([2302b31](https://github.com/bootstrap-vue/bootstrap-vue/commit/2302b31))
- **b-table, b-table-lite:** generate `:key` for `row-details` row based on the `primary-key` field
  value if available ([#4025](https://github.com/bootstrap-vue/bootstrap-vue/issues/4025))
  ([c7cb16f](https://github.com/bootstrap-vue/bootstrap-vue/commit/c7cb16f))
- **v-b-toggle:** don't override `role` if element has a `role` assigned
  ([#3889](https://github.com/bootstrap-vue/bootstrap-vue/issues/3889))
  ([5d155ba](https://github.com/bootstrap-vue/bootstrap-vue/commit/5d155ba))
- **tooltip, popover:** overall code refactor for better reactivity and performance (fixes:
  [#1990](https://github.com/bootstrap-vue/bootstrap-vue/issues/1990),
  [#2937](https://github.com/bootstrap-vue/bootstrap-vue/issues/2937),
  [#3480](https://github.com/bootstrap-vue/bootstrap-vue/issues/3480),
  [#3717](https://github.com/bootstrap-vue/bootstrap-vue/issues/3717),
  [#3854](https://github.com/bootstrap-vue/bootstrap-vue/issues/3854), closes
  [#3451](https://github.com/bootstrap-vue/bootstrap-vue/issues/3451))
  ([#3908](https://github.com/bootstrap-vue/bootstrap-vue/issues/3908))
  ([eebab43](https://github.com/bootstrap-vue/bootstrap-vue/commit/eebab43))

### Features v2.0.0

- **b-carousel:** add prop `no-wrap` for disabling wrapping to start/end (closes
  [#3902](https://github.com/bootstrap-vue/bootstrap-vue/issues/3902))
  ([#3905](https://github.com/bootstrap-vue/bootstrap-vue/issues/3905))
  ([2c8bd23](https://github.com/bootstrap-vue/bootstrap-vue/commit/2c8bd23))
- **b-dropdown:** add `role=presentation` to `<li>` elements for improved a11y
  ([#3996](https://github.com/bootstrap-vue/bootstrap-vue/issues/3996))
  ([464d257](https://github.com/bootstrap-vue/bootstrap-vue/commit/464d257))
- **b-img-lazy:** switch IntersectionObserver to use private `v-b-visible` directive
  ([#3977](https://github.com/bootstrap-vue/bootstrap-vue/issues/3977))
  ([249ccfa](https://github.com/bootstrap-vue/bootstrap-vue/commit/249ccfa))
- **b-modal:** add scoped style support when portalled (non-static modal)
  ([#3962](https://github.com/bootstrap-vue/bootstrap-vue/issues/3962))
  ([77ad6b9](https://github.com/bootstrap-vue/bootstrap-vue/commit/77ad6b9))
- **b-nav:** add card header support
  ([#3883](https://github.com/bootstrap-vue/bootstrap-vue/issues/3883))
  ([4046a53](https://github.com/bootstrap-vue/bootstrap-vue/commit/4046a53))
- **b-pagination:** if number of pages changes, try and keep current page active (closes
  [#3716](https://github.com/bootstrap-vue/bootstrap-vue/issues/3716))
  ([#3990](https://github.com/bootstrap-vue/bootstrap-vue/issues/3990))
  ([ae8ce78](https://github.com/bootstrap-vue/bootstrap-vue/commit/ae8ce78))
- **b-modal:** add prop for auto focusing one of the built in-buttons once `shown` (closes
  [#3945](https://github.com/bootstrap-vue/bootstrap-vue/issues/3945))
  ([#3979](https://github.com/bootstrap-vue/bootstrap-vue/issues/3979))
  ([6f2827e](https://github.com/bootstrap-vue/bootstrap-vue/commit/6f2827e))
- **b-table:** allow field definition properties `filterByFormatted` and `sortByFormatted` to accept
  a formatter function reference (closes
  [#3892](https://github.com/bootstrap-vue/bootstrap-vue/issues/3892))
  ([#3898](https://github.com/bootstrap-vue/bootstrap-vue/issues/3898))
  ([5492b38](https://github.com/bootstrap-vue/bootstrap-vue/commit/5492b38))
- **b-table:** new sorting icons using SVG, plus option to place icon on left of header cell (closes
  [#3687](https://github.com/bootstrap-vue/bootstrap-vue/issues/3687),
  [#3696](https://github.com/bootstrap-vue/bootstrap-vue/issues/3696),
  [#3918](https://github.com/bootstrap-vue/bootstrap-vue/issues/3918),
  [#3966](https://github.com/bootstrap-vue/bootstrap-vue/issues/3966))
  ([#3968](https://github.com/bootstrap-vue/bootstrap-vue/issues/3968))
  ([c4442f4](https://github.com/bootstrap-vue/bootstrap-vue/commit/c4442f4))
- **b-table:** add `filter-debounce` prop for debouncing filter updates
  ([#3891](https://github.com/bootstrap-vue/bootstrap-vue/issues/3891))
  ([03536a5](https://github.com/bootstrap-vue/bootstrap-vue/commit/03536a5))
- **b-table:** add `selectAllRows()` and `clearSelected()` to thead/tfoot slot scopes (addresses
  [#3901](https://github.com/bootstrap-vue/bootstrap-vue/issues/3901))
  ([#3907](https://github.com/bootstrap-vue/bootstrap-vue/issues/3907))
  ([86c53dd](https://github.com/bootstrap-vue/bootstrap-vue/commit/86c53dd))
- **b-table, b-table-lite:** switch slot name syntax to use round brackets instead of square
  brackets ([#3986](https://github.com/bootstrap-vue/bootstrap-vue/issues/3986))
  ([fca7bd5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fca7bd5))
- **b-table, b-table-lite:** remove deprecated slot names, introduce new slot names
  ([#3866](https://github.com/bootstrap-vue/bootstrap-vue/issues/3866))
  ([249efd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/249efd9))
- **b-table, b-table-lite:** use `aria-details` rather than `aria-describedby` when details row
  showing (addresses [#3801](https://github.com/bootstrap-vue/bootstrap-vue/issues/3801))
  ([#3992](https://github.com/bootstrap-vue/bootstrap-vue/issues/3992))
  ([f6f73c7](https://github.com/bootstrap-vue/bootstrap-vue/commit/f6f73c7))
- **b-table, b-table-lite:** add support for custom header attributes (closes
  [#2244](https://github.com/bootstrap-vue/bootstrap-vue/issues/2244))
  ([#3876](https://github.com/bootstrap-vue/bootstrap-vue/issues/3876))
  ([8784f31](https://github.com/bootstrap-vue/bootstrap-vue/commit/8784f31))
- **b-table, b-table-lite:** add new scoped slot `custom-foot` to allow user to create their own
  table footer (closes [#3960](https://github.com/bootstrap-vue/bootstrap-vue/issues/3960))
  ([#4027](https://github.com/bootstrap-vue/bootstrap-vue/issues/4027))
  ([cbeeef9](https://github.com/bootstrap-vue/bootstrap-vue/commit/cbeeef9))
- **b-table, b-table-lite, b-table-simple:** add `no-border-collapse` prop and SCSS
  ([#3987](https://github.com/bootstrap-vue/bootstrap-vue/issues/3987))
  ([253b4f6](https://github.com/bootstrap-vue/bootstrap-vue/commit/253b4f6))
- **b-toast:** add support for scoped styles
  ([#3963](https://github.com/bootstrap-vue/bootstrap-vue/issues/3963))
  ([ca1b5de](https://github.com/bootstrap-vue/bootstrap-vue/commit/ca1b5de))
- **tooltip, popover:** overall code refactor for better reactivity and performance (fixes:
  [#1990](https://github.com/bootstrap-vue/bootstrap-vue/issues/1990),
  [#2937](https://github.com/bootstrap-vue/bootstrap-vue/issues/2937),
  [#3480](https://github.com/bootstrap-vue/bootstrap-vue/issues/3480),
  [#3717](https://github.com/bootstrap-vue/bootstrap-vue/issues/3717),
  [#3854](https://github.com/bootstrap-vue/bootstrap-vue/issues/3854), closes
  [#3451](https://github.com/bootstrap-vue/bootstrap-vue/issues/3451))
  ([#3908](https://github.com/bootstrap-vue/bootstrap-vue/issues/3908))
  ([eebab43](https://github.com/bootstrap-vue/bootstrap-vue/commit/eebab43))

### Deprecation removals v2.0.0

- **b-dropdown:** remove deprecated slot `text`
  ([#3868](https://github.com/bootstrap-vue/bootstrap-vue/issues/3868))
  ([29eb8b1](https://github.com/bootstrap-vue/bootstrap-vue/commit/29eb8b1))
- **b-form-group:** remove deprecated prop `horizontal` and `breakpoint`
  ([#3879](https://github.com/bootstrap-vue/bootstrap-vue/issues/3879))
  ([b301822](https://github.com/bootstrap-vue/bootstrap-vue/commit/b301822))
- **b-nav, b-nav-item-dropdown:** remove deprecated slot and props
  ([#3867](https://github.com/bootstrap-vue/bootstrap-vue/issues/3867))
  ([21fab35](https://github.com/bootstrap-vue/bootstrap-vue/commit/21fab35))
- **b-modal:** remove `BvModalEvent` deprecations
  ([#3864](https://github.com/bootstrap-vue/bootstrap-vue/issues/3864))
  ([90c299c](https://github.com/bootstrap-vue/bootstrap-vue/commit/90c299c))
- **b-table, b-table-lite:** switch slot name syntax to use round brackets instead of square
  brackets ([#3986](https://github.com/bootstrap-vue/bootstrap-vue/issues/3986))
  ([fca7bd5](https://github.com/bootstrap-vue/bootstrap-vue/commit/fca7bd5))
- **b-table, b-table-lite:** remove deprecated slot names, introduce new slot names
  ([#3866](https://github.com/bootstrap-vue/bootstrap-vue/issues/3866))
  ([249efd9](https://github.com/bootstrap-vue/bootstrap-vue/commit/249efd9))
- **b-tabs:** remove deprecations
  ([#3863](https://github.com/bootstrap-vue/bootstrap-vue/issues/3863))
  ([0edac49](https://github.com/bootstrap-vue/bootstrap-vue/commit/0edac49))
- **tooltip/popover:** remove SCSS deprecations
  ([#3869](https://github.com/bootstrap-vue/bootstrap-vue/issues/3869))
  ([bea49d4](https://github.com/bootstrap-vue/bootstrap-vue/commit/bea49d4))
- **build:** remove deprecated `es/` build
  ([#3604](https://github.com/bootstrap-vue/bootstrap-vue/issues/3604))
  ([3828f59](https://github.com/bootstrap-vue/bootstrap-vue/commit/3828f59))

<br>
<hr>

## Older releases

For prior release notes and commits, please refer to the
[CHANGELOG-OLD](https://github.com/bootstrap-vue/bootstrap-vue/blob/master/CHANGELOG-OLD.md) file.
