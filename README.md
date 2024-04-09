# astral-test-hash

Test Python package indexes with various hash schemes.

## valid-hash

`uv pip install --extra-index-url https://astral-test.github.io/astral-test-hash/valid-hash/simple-html/ example-a-961b4c22`

Has valid sha256 file hashes.

Generated from [packse@47e87ac](https://github.com/astral-sh/packse/commit/47e87ac4e545ab139a3cb455597be75b9c42c9e3)

## invalid-hash

`uv pip install --extra-index-url https://astral-test.github.io/astral-test-hash/invalid-hash/simple-html/ example-a-961b4c22`

Has invalid, random sha256 file hashes.

Generated from [packse@a9fea06](https://github.com/astral-sh/packse/commit/a9fea0680393d481b455c30c5d7eb877c4d6b99c).

## no-hash

`uv pip install --extra-index-url https://astral-test.github.io/astral-test-hash/invalid-hash/simple-html/ example-a-961b4c22`

Has no hash metadata for files.

Generated from [packse@5643a19](https://github.com/astral-sh/packse/commit/5643a19b6666e9d0513dc9ec0154e94dd071158e)
