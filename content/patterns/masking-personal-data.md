---
title: Masking personal data

category: Getting access to data

weight: 2

archived: false

archive_reason:

future_pattern: false

future_pattern_reason:

images:
 - url: /images/anonymising-users-using-codes.svg
alt: Anonymising users using codes

advantages:
 - Data can be processed without revealing who it relates to
 - If it gets lost it can’t be traced back to the individual


limitations:
 - Large collections of pseudo-anonymous data can be de-anonymised, making it possible to identify people. In some cases differential privacy is recommended.


examples:
 - title: SH:24 lab sample labels
   url: https://sh24.org.uk
   description: Labels that include a unique code without name or address of the person who submitted the sample
 - title: Verifiable Electronic Voting
   url: https://evoting.bismark.se/verifiable-electronic-voting/
 - title: Mixpanel analytics allow the use of random identifiers to refer to individual users
   url: https://help.mixpanel.com/hc/en-us/articles/360000679006-Managing-Personal-Information#use-randomly-generated-identifiers

---
Personal data is masked using a code to make it harder to trace it back to the individual, without the correct authorisation reveal the data. For example, a blood sample is labelled with a code, and only the doctor can work out who the blood came from by checking the code against a database.
