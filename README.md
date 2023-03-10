# vcdm2-test-suite
Test Suite for Verifiable Credentials Data Model (VCDM) 2.0

## Table of Contents

- [Background](#background)
- [Install](#install)
- [Usage](#usage)
- [Implementation](#implementation)


## Background

Provides interoperability tests for verifable credential processors (issuers/verifiers) that support [vc-data-model-2.0](https://www.w3.org/TR/vc-data-model-2.0/).

## Install

```js
npm i
```

## Usage

```
npm test
```


## Implementation

### VC-API
To add your implementation to this test suite see the [README here](https://github.com/w3c-ccg/vc-api-test-suite-implementations).
Add the tag `vc-api` to the issuers and verifiers you want tested. To run the tests, some implementations require client secrets
that can be passed as env variables to the test script. To see which ones require client secrets, you can check the [vc-api-test-suite-implementations](https://github.com/w3c-ccg/vc-api-test-suite-implementations) library.

### Non-VC-API
TODO

## License

Copyright © 2023 [World Wide Web Consortium](http://www.w3.org/), ([MIT](http://www.csail.mit.edu/), [ERCIM](http://www.ercim.org/), [Keio](http://www.keio.ac.jp/), [Beihang](http://ev.buaa.edu.cn/)) and others. All Rights Reserved. <http://www.w3.org/Consortium/Legal/2008/04-testsuite-copyright.html>

Distributed under both the [W3C Test Suite License](https://www.w3.org/Consortium/Legal/2008/04-testsuite-license) (SPDX: [LicenseRef-scancode-w3c-test-suite](https://scancode-licensedb.aboutcode.org/w3c-test-suite.html)) and the [W3C 3-clause BSD License](https://www.w3.org/Consortium/Legal/2008/03-bsd-license). To contribute to a W3C Test Suite, see the [policies and contribution forms](https://www.w3.org/2004/10/27-testcases).

UNDER BOTH MUTUALLY EXCLUSIVE LICENSES, THIS DOCUMENT AND ALL DOCUMENTS, TESTS AND SOFTWARE THAT LINK THIS STATEMENT ARE PROVIDED "AS IS," AND COPYRIGHT HOLDERS MAKE NO REPRESENTATIONS OR WARRANTIES, EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, OR TITLE; THAT THE CONTENTS OF THE DOCUMENT ARE SUITABLE FOR ANY PURPOSE; NOR THAT THE IMPLEMENTATION OF SUCH CONTENTS WILL NOT INFRINGE ANY THIRD PARTY PATENTS, COPYRIGHTS, TRADEMARKS OR OTHER RIGHTS.

COPYRIGHT HOLDERS WILL NOT BE LIABLE FOR ANY DIRECT, INDIRECT, SPECIAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF ANY USE OF THE DOCUMENT OR THE PERFORMANCE OR IMPLEMENTATION OF THE CONTENTS THEREOF.
