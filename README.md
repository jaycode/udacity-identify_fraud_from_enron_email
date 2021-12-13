# Jaycode's Identify Fraud from Enron Email

## Recommended project structure

I recommend placing `poi_id.py` relative to the `tester.py`/`tester3.py` as shown in the following file structure:

```
- project
  | - place your poi_id.py here
- tools
  | - feature_format3.py
- tester3.py
```

## Updating the poi_id.py script

Assuming `poi_id.py` is located in the `project` directory, for python 2, use the following in `poi_id.py`:

```
sys.path.append("../tools/"); sys.path.append("../")
from feature_format ...
from tester ...
```

For python 2, use the following in `poi_id.py`:

```
sys.path.append("../tools/"); sys.path.append("../")
from feature_format3 ...
from tester3 ...
```

You may then `cd` to the `project` dir and run `python poi_id.py` script to generate pkl files.

## Generating result from pkl files

Assuming the pkl files are in `project` dir:

```
tester.py project
```

or

```
tester3.py project_dir
```
