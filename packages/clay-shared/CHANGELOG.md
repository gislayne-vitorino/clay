# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# [3.47.0](https://github.com/liferay/clay/compare/v3.46.0...v3.47.0) (2022-02-23)

**Note:** Version bump only for package @clayui/shared

# [3.45.0](https://github.com/liferay/clay/compare/v3.44.2...v3.45.0) (2022-02-01)

### Bug Fixes

-   **@clayui/shared:** fix focus control collision when having FocusScope nested ([58bd27f](https://github.com/liferay/clay/commit/58bd27fc24d6754c9662b12332e01e2b209a9e84))

# [3.40.0](https://github.com/liferay/clay/compare/v3.39.0...v3.40.0) (2021-11-17)

### Bug Fixes

-   **@clayui/provider:** removes dependency from ClayModal to avoid circular dependency issues ([0b8eade](https://github.com/liferay/clay/commit/0b8eade03bc6a12284662cb5e42d7b1fdb87c20f))
-   **@clayui/shared:** fixes error when considering an element with negative tabIndex ([da143f0](https://github.com/liferay/clay/commit/da143f09b21c889a3f6586af0f1aa20bd944c60b))

# [3.39.0](https://github.com/liferay/clay/compare/v3.38.0...v3.39.0) (2021-10-29)

**Note:** Version bump only for package @clayui/shared

# [3.38.0](https://github.com/liferay/clay/compare/v3.37.0...v3.38.0) (2021-10-22)

**Note:** Version bump only for package @clayui/shared

# [3.37.0](https://github.com/liferay/clay/compare/v3.36.0...v3.37.0) (2021-10-06)

### Bug Fixes

-   **@clayui/shared:** fix error when controlling internal state using external value and internal controller ([d17eba5](https://github.com/liferay/clay/commit/d17eba5))

# [3.36.0](https://github.com/liferay/clay/compare/v3.35.3...v3.36.0) (2021-09-23)

**Note:** Version bump only for package @clayui/shared

## [3.35.3](https://github.com/liferay/clay/compare/v3.35.2...v3.35.3) (2021-09-09)

**Note:** Version bump only for package @clayui/shared

## [3.35.2](https://github.com/liferay/clay/compare/v3.35.1...v3.35.2) (2021-08-30)

### Bug Fixes

-   **@clayui/shared:** fix error export type from root in package distribution ([121e3cc](https://github.com/liferay/clay/commit/121e3cc))

## [3.35.1](https://github.com/liferay/clay/compare/v3.35.0...v3.35.1) (2021-08-30)

### Bug Fixes

-   **@clayui/shared:** fixes error when importing the type that is not available in the module ([3108383](https://github.com/liferay/clay/commit/3108383))

# [3.35.0](https://github.com/liferay/clay/compare/v3.34.0...v3.35.0) (2021-08-30)

**Note:** Version bump only for package @clayui/shared

# [3.32.0](https://github.com/liferay/clay/compare/v3.31.0...v3.32.0) (2021-07-28)

### Bug Fixes

-   **@clayui/shared:** fixes error when getting stuck in an input masked as hidden ([4c0c5cb](https://github.com/liferay/clay/commit/4c0c5cb))

# [3.29.0](https://github.com/liferay/clay/compare/v3.28.0...v3.29.0) (2021-05-28)

### Features

-   **@clayui/shared:** Add MouseSafeArea to the contextual menu ([7824f16](https://github.com/liferay/clay/commit/7824f16))

# [3.28.0](https://github.com/liferay/clay/compare/v3.27.0...v3.28.0) (2021-05-19)

### Features

-   **@clayui/drop-down:** Add the new ContainerProps API ([b106420](https://github.com/liferay/clay/commit/b106420))
-   **@clayui/shared:** add delegate event utility ([f46b6ef](https://github.com/liferay/clay/commit/f46b6ef))
-   **@clayui/shared:** Allow to pass className and/or id to the portal root element ([132ab1e](https://github.com/liferay/clay/commit/132ab1e))
-   **@clayui/shared:** Extract to a function so the div is created with all its attributes ([b7445bc](https://github.com/liferay/clay/commit/b7445bc))
-   **@clayui/shared:** simplify function ([d326ace](https://github.com/liferay/clay/commit/d326ace))

# [3.27.0](https://github.com/liferay/clay/compare/v3.26.0...v3.27.0) (2021-05-05)

### Bug Fixes

-   **@clayui/shared:** add unit test for FocusScope ([f84332f](https://github.com/liferay/clay/commit/f84332f))
-   **@clayui/shared:** update and simplify logic for focus management when focus moves in and out of the react tree ([e3a100f](https://github.com/liferay/clay/commit/e3a100f))

### Features

-   **@clayui/multi-select:** add async functionality for source items ([548aa2d](https://github.com/liferay/clay/commit/548aa2d))

## [3.5.1](https://github.com/liferay/clay/compare/@clayui/shared@3.5.0...@clayui/shared@3.5.1) (2021-02-11)

**Note:** Version bump only for package @clayui/shared

# [3.5.0](https://github.com/liferay/clay/compare/@clayui/shared@3.4.0...@clayui/shared@3.5.0) (2021-01-27)

### Features

-   **@clayui/drop-down:** add api for controlling the active state of the menu ([28e5191](https://github.com/liferay/clay/commit/28e5191))

# [3.4.0](https://github.com/liferay/clay/compare/@clayui/shared@3.3.2...@clayui/shared@3.4.0) (2021-01-13)

### Bug Fixes

-   **@clayui/shared:** remove useTransitionHeight in favor of react-transition-group ([d2311f9](https://github.com/liferay/clay/commit/d2311f9))
-   **@clayui/shared:** update types so that storybook build doesn't complain ([38903aa](https://github.com/liferay/clay/commit/38903aa))

### Features

-   **@clayui/shared:** add custom hook for using an internal state if an external control isn't provided ([a34ccd9](https://github.com/liferay/clay/commit/a34ccd9))

## [3.3.2](https://github.com/liferay/clay/compare/@clayui/shared@3.3.0...@clayui/shared@3.3.2) (2020-12-16)

### Bug Fixes

-   **shared:** avoid race condition with Senna.js ([f0754ea](https://github.com/liferay/clay/commit/f0754ea)), closes [/github.com/liferay-frontend/liferay-portal/pull/565#issuecomment-736854056](https://github.com//github.com/liferay-frontend/liferay-portal/pull/565/issues/issuecomment-736854056)

## [3.3.1](https://github.com/liferay/clay/compare/@clayui/shared@3.3.0...@clayui/shared@3.3.1) (2020-12-02)

### Bug Fixes

-   **shared:** avoid race condition with Senna.js ([f0754ea](https://github.com/liferay/clay/commit/f0754ea)), closes [/github.com/liferay-frontend/liferay-portal/pull/565#issuecomment-736854056](https://github.com//github.com/liferay-frontend/liferay-portal/pull/565/issues/issuecomment-736854056)

# [3.3.0](https://github.com/liferay/clay/compare/@clayui/shared@3.2.3...@clayui/shared@3.3.0) (2020-10-01)

### Bug Fixes

-   **@clayui/shared:** removes the onTransitionEnd listener from elements by setTimeout ([4cf740a](https://github.com/liferay/clay/commit/4cf740a))
-   **@clayui/shared:** useTransitionHeight should still expand and collapse if transitions aren't supported ([bb1a858](https://github.com/liferay/clay/commit/bb1a858)), closes [#3637](https://github.com/liferay/clay/issues/3637)

### Features

-   add displayName for all components ([cc3211d](https://github.com/liferay/clay/commit/cc3211d))

## [3.2.3](https://github.com/liferay/clay/compare/@clayui/shared@3.2.2...@clayui/shared@3.2.3) (2020-08-28)

### Bug Fixes

-   **@clayui/shared:** ignores elements within the scope with tabindex="-1" from the focus manager ([167b11a](https://github.com/liferay/clay/commit/167b11a))

## [3.2.2](https://github.com/liferay/clay/compare/@clayui/shared@3.2.1...@clayui/shared@3.2.2) (2020-08-26)

### Bug Fixes

-   **@clayui/shared:** fixes side effect of focusing on the first element when the active element does not exist in the scope ([4a136da](https://github.com/liferay/clay/commit/4a136da))

## [3.2.1](https://github.com/liferay/clay/compare/@clayui/shared@3.2.0...@clayui/shared@3.2.1) (2020-07-28)

**Note:** Version bump only for package @clayui/shared

## [3.1.3](https://github.com/liferay/clay/compare/@clayui/shared@3.1.2...@clayui/shared@3.1.3) (2020-07-07)

### Bug Fixes

-   **@clayui/link:** pass onClick to ClayLink ([1018420](https://github.com/liferay/clay/commit/1018420))

## [3.1.2](https://github.com/liferay/clay/compare/@clayui/shared@3.1.1...@clayui/shared@3.1.2) (2020-06-18)

### Bug Fixes

-   **@clayui/shared:** only preventDefault if next/previous node exists in the focusManager ([6317e69](https://github.com/liferay/clay/commit/6317e69))

## [3.1.1](https://github.com/liferay/clay/compare/@clayui/shared@3.1.0...@clayui/shared@3.1.1) (2020-04-24)

**Note:** Version bump only for package @clayui/shared

# 3.1.0 (2020-02-28)

### Bug Fixes

-   **@clayui/shared:** add focus control by left and right arrow keys ([e314419](https://github.com/liferay/clay/commit/e314419))
-   **@clayui/shared:** add reference to children ref ([38896b6](https://github.com/liferay/clay/commit/38896b6))
-   **@clayui/shared:** collects focusable elements within a focusable element ([3ce4e8e](https://github.com/liferay/clay/commit/3ce4e8e))
-   **@clayui/shared:** get the Fiber from the ref ([9980545](https://github.com/liferay/clay/commit/9980545))
-   **@clayui/shared:** use another method to create a new array from an HTMLCollection ([6d98c43](https://github.com/liferay/clay/commit/6d98c43))
-   **panel:** collapsing doesn't work well when there is more than one child element ([f16fd86](https://github.com/liferay/clay/commit/f16fd86))
-   **portal:** automatically nest portals if they are inside one another ([dee9d69](https://github.com/liferay/clay/commit/dee9d69))
-   **shared:** Remove weird initialization on `getEllipsisItems` ([bd7c621](https://github.com/liferay/clay/commit/bd7c621))
-   **shared:** When having one item, should only render one item ([e3645a2](https://github.com/liferay/clay/commit/e3645a2))
-   **useDebounce:** stop update the value every time when the object loses reference ([e840edc](https://github.com/liferay/clay/commit/e840edc))
-   **useFocusManagement:** check elements in focusManager list before controlling out-of-scope elements ([1236be3](https://github.com/liferay/clay/commit/1236be3))
-   normalize names of components ([3a0abea](https://github.com/liferay/clay/commit/3a0abea))
-   ref callbacks are first calling with null. https://reactjs.org/docs/refs-and-the-dom.html#caveats-with-callback-refs ([fec52cb](https://github.com/liferay/clay/commit/fec52cb))
-   update components to include 'types' and 'ts:main' package keys ([9e24b59](https://github.com/liferay/clay/commit/9e24b59))
-   **useFocusManagement:** fixes last position for cases when it was not reset ([3f48cb7](https://github.com/liferay/clay/commit/3f48cb7))
-   **useFocusManagement:** remove reset from last position when any list item is deleted ([bfb78f5](https://github.com/liferay/clay/commit/bfb78f5))
-   **useFocusManagement:** sets the last position when one does not exist, with the active element index if it exists in the list ([29e1494](https://github.com/liferay/clay/commit/29e1494))

### Features

-   Move useDebounce to clay-shared ([fcf1ceb](https://github.com/liferay/clay/commit/fcf1ceb))
-   **@clayui/shared:** add experimental useFocusManagement hook ([6e7190b](https://github.com/liferay/clay/commit/6e7190b))
-   **@clayui/shared:** add forwardRef to LinkOrButton component ([92317ef](https://github.com/liferay/clay/commit/92317ef))
-   **@clayui/shared:** add LinkOrButton component for use internal ([63371b0](https://github.com/liferay/clay/commit/63371b0))
-   **@clayui/shared:** create FocusScope component ([9772e5c](https://github.com/liferay/clay/commit/9772e5c))
-   **clay-form:** create high-level InputWithAutocomplete component ([692610a](https://github.com/liferay/clay/commit/692610a))
-   **clay-shared:** add keyboard hooks for lists and add demo under autocomplete ([3622453](https://github.com/liferay/clay/commit/3622453))

## [3.0.7](https://github.com/liferay/clay/tree/master/packages/clay-shared/compare/@clayui/shared@3.0.4...@clayui/shared@3.0.7) (2020-01-31)

**Note:** Version bump only for package @clayui/shared

## [3.0.6](https://github.com/liferay/clay/tree/master/packages/clay-shared/compare/@clayui/shared@3.0.4...@clayui/shared@3.0.6) (2020-01-20)

**Note:** Version bump only for package @clayui/shared

## [3.0.5](https://github.com/liferay/clay/tree/master/packages/clay-shared/compare/@clayui/shared@3.0.4...@clayui/shared@3.0.5) (2019-12-05)

**Note:** Version bump only for package @clayui/shared

## [3.0.4](https://github.com/liferay/clay/tree/master/packages/clay-shared/compare/@clayui/shared@3.0.3...@clayui/shared@3.0.4) (2019-11-07)

**Note:** Version bump only for package @clayui/shared

## [3.0.3](https://github.com/liferay/clay/tree/master/packages/clay-shared/compare/@clayui/shared@3.0.2...@clayui/shared@3.0.3) (2019-11-01)

### Bug Fixes

-   **@clayui/shared:** collects focusable elements within a focusable element ([3ce4e8e](https://github.com/liferay/clay/commit/3ce4e8e))

## [3.0.2](https://github.com/liferay/clay/tree/master/packages/clay-shared/compare/@clayui/shared@3.0.1...@clayui/shared@3.0.2) (2019-10-28)

### Bug Fixes

-   ref callbacks are first calling with null. https://reactjs.org/docs/refs-and-the-dom.html#caveats-with-callback-refs ([fec52cb](https://github.com/liferay/clay/commit/fec52cb))
-   **@clayui/shared:** use another method to create a new array from an HTMLCollection ([6d98c43](https://github.com/liferay/clay/commit/6d98c43))
