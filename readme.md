# Cook County Medical Examiner Database with Applied Improvements in Data Integrity

This project is a hobby of the owner of this GitHub.  I take it seriously, but additionally, I am human.

Notes herein are made to make the "database" more accessible to laypeople and other individuals interested in learning more about the data available to the public that is generated from the Cook County Medical Examiner's office.

What is available in this project?
- My rendition of the Cook County Medical Examiner's Medical Examiner Case Archive which is also publicly available in its native format from the Cook County Open Data Portal. (https://datacatalog.cookcountyil.gov/Public-Safety/Medical-Examiner-Case-Archive/cjeq-bs86)

- A "demise crosswalk" so that if you're looking for the long-form death certificate "cause of death," you can find it there.  The cause of death on my own rendition has been tailored for easier bucketing.  I don't update the demise crosswalk everyday, so no guarantees on that.

What am I working on currently?
- Zip code correction.  It's bad folks, really, it is.

- Daily updates.  Cross-reference for new cases and manner of death dispositions against pending cases are made daily when the Medical Examiner's native copy provides updates.

Known Issues and Self-Initiated Adjustments:
- The aforementioned zip codes - most keyed into the native edition are incorrect.  I have updated the vast majority of Chicago city zips already.

- Span.  If given a rational Date of Incident and a rational Date of Death, I subtract the two and provide a "span" calculation.  This is simply the number of days or partial days between incident and pronouncement.

- Names.  Victim names have been xref'd from media and victim tracking websites.  Homicide victims are the easiest to find along with homicide/suicide incidents.  Other cases are newsworthy, and so a name may accompany - car accidents, drownings, etc.  Names are also xref'd from the Cook County ME's office Unclaimed Bodies index (https://www.cookcountyil.gov/service/unclaimed-persons) and Indigent Cremation index (https://www.cookcountyil.gov/service/virtual-cemetery).

I also have regular XLSX files with lots of pretty colors if anyone cares :)

14 August 2019 Updates:
Broke the overall data into files by year, according to the Medical Examiner case numbers (i.e. ME201x).

Thanks, Kari
