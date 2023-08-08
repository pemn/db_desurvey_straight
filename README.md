## 📌 Description
Create xyz coordinates from ASSAY intervals (from/to)
## 🧰 Tools
 - db_assay_runlegth.py: breaks assay intervals down to a maximum length. part of process for runlength compositing.
 - db_create_fromto.py: converter tables that only have `DEPTH` to `FROM➔TO`
 - db_desurvey_straight.py: convert header,survey,assay into midx,midy,midz samples. each assay interval will be a single sample.
## 📸 Screenshot
![screenshot1](./assets/db_desurvey_straight1.png)
## 📝 Parameters
Name|optional|description
---|---|------
||❎||
||☑️||
## 📓 Notes
While db_desurvey_straight only allows for straigth compositing, if the data is preprocessed with db_assay_runlength the result will be what in other softwares is called runlength compositing.
## 📚 Examples
## 💎 License
Apache 2.0
