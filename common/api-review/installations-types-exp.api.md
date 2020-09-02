## API Report File for "@firebase/installations-types-exp"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public (undocumented)
export interface FirebaseInstallations {}

// Warning: (ae-internal-missing-underscore) The name "FirebaseInstallationsInternal" should be prefixed with an underscore because the declaration is marked as @internal
//
// @internal
export interface FirebaseInstallationsInternal {
  getId(): Promise<string>;

  getToken(forceRefresh?: boolean): Promise<string>;
}


// (No @packageDocumentation comment for this package)

```