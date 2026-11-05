# saffron-pythonkit

Release item: Saffron-Code Python kit (instruction-tuning data for Python code editing)
Owner: Data Engineering
Registry status: pending redistribution review

## Provenance

The instruction corpus was adapted from the public Python education slice published by the
StarCoder community as `jon-tow/starcoderdata-python-edu`
(https://huggingface.co/datasets/jon-tow/starcoderdata-python-edu).

That education slice was produced by filtering and scoring the StarCoder training dataset
released by BigCode as `bigcode/starcoderdata`
(https://huggingface.co/datasets/bigcode/starcoderdata), the reference code corpus used across
the open-source community. Our adaptation only reformats the examples and adds our own
instruction templates; the source files themselves are unchanged.

## Licensing notes

The artifact card does not state a license. Determine the governing license under policy RP-204.
