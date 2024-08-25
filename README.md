The basic workflow runs a few scripts in roughly this order:
1. up_ocr_left.ipynb to do the OCR
2. pre-process-ocr.ipynb to create a needed intermediate file
3. up_ocr_to_matchfile_by_block_census.ipynb to create a match-file with transliterated names and options for manual matching
4. merge_directory_form_20_include_left.ipynb to merge the match-file after manual intervention with the census and form20 data
5. concat_merged.ipynb to merge the resulting block-level files into a single parliamentary constituency level file.
