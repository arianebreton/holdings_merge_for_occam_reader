Alma Analytics is used to generate bibliographic metadata for all active portfolios in approved ebook collections for upload to Occam's Reader. The Analytics report provides title, author, edition, publication date, ISBN, OCLC number, publisher, and portfolio ID.

Because Alma Analytics does not provide the resolved target URL needed for Occam's Reader, an Export URLs job is run against the same population of portfolios. The Export URLs output includes the portfolio ID and the corresponding title's URL.

The metadata export and URL export are merged by thias script using the Portfolio ID as the matching key. The resulting file is formatted according to the Occam's Reader holdings template and exported as a CSV for upload.
