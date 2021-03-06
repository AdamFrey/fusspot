# Changelog

## 0.8.0

- Add `v.finite` primitive validator.

## 0.7.2

- Reverts `0.7.1` 

## 0.7.1

- Fix `v.strictShape` when dealing with empty objects.

## 0.7.0

- Add `v.objectOf` higher-order validator.

## 0.6.0

- Add `v.date` primitive validator.
- Add `v.instanceOf` meta validator.

## 0.5.0

- Add `v.nonEmptyString` primitive validator.
- Rename `options.apiName` to `options.description`. (`options.apiName` still works but is deprecated.)
- Allow the second argument to `v.assert` to be a string, which is interpreted as `options.description`.

## 0.4.0

- **Breaking:** Remove `v.coordinates` primitive validator. The equivalent be accomplished by using the new `v.tuple` validator with `v.range` items.
- Add `v.tuple` higher-order validator.
- Improve error message whitespaces and indefinite articles.

## 0.3.0

- Remove `v.date` primitive validator, which wasn't generic enough default inclusion.
- Clean up the formatting of lists in error messages.

## 0.2.1

- Fix error message formatting for `v.strictShape`.

## 0.2.0

- Add `v.any` primitive validator.
- Add `v.func` primitive validator.
- Add `v.strictShape` higher-order validator.

## 0.1.0

- Start this log.
