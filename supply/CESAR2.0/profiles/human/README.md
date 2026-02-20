# Description
These are the default CESAR2.0 profiles used by the distributed TOGA2 version as well as in the companion dataset production. The profiles were derived from the extended human (hg38) genome annotation, with certain profiles further modified for better handling edge cases in hg38-mm10 benchmarking tests.

> [!WARNING]
> This section (CESAR2 profile section preparation) is to be expanded

The profiles were generated using TOGA2's `prepare-input` mode with default settings and IntronIC v1.5.3 . Since for production purposes we found equiprobable profile to perform better than the programmatically produced non-canonical U12 acceptor profile, starting from version `v2.0.8`, `equiprobable_acceptor.tsv` was renamed into `nonCanon_U12_acceptor.tsv` to comply with the `--cesar_profile_dir` argument. The programmatically defined profile can be found under the name of `_nonCanon_U12_acceptor.tsv`.

For demonstrative purposes, this directory is copied without changes to `test_input/hg38/TOGA2/currentAnnotation/CESAR2.0_profiles`.