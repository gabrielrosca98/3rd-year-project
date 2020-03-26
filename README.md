# Cloud computing environments to support data science teaching in health
## Description
Data science is a rapidly growing discipline with applications in many areas of science and society. One area in which it is growing rapidly is in health - particularly working with the data being captured in hospitals and doctors surgeries. As a result we need to develop the capacity to train large numbers of professional health workers (doctors, nurses, administrators) in basic data science. To support this we need to explore the ways in which data science environments can be made available to a wide range of learners who may not be based at the university. This project will explore the use of Jupyter notebooks and cloud infrastructures to create learning resources for health data science.


## Prerequisites

Jupyter Notebook must be installed in order to run the notebooks.

The following libraries must be installed in order to run the notebooks.

* For LondonOpenData_ETL
```
import os
from os import path
import shutil
import tqdm
from tqdm import trange, tqdm_notebook
from tqdm import tqdm_notebook as tqdm
import pandas as pd
import re
import csv
import urllib3
from urllib3 import PoolManager
import requests
import urllib.request
import numpy as np
import time
from bs4 import BeautifulSoup
from IPython.display import Markdown, display
import urllib3
import boto3
import s3fs
import ipywidgets as widgets
from ipywidgets import TwoByTwoLayout
from ipywidgets import interact, interactive, fixed, interact_manual
from ipywidgets import VBox, HBox, Label, Box
from ipywidgets import Button, Layout
```
* For Meta_Local_Data
```
import os
import pandas as pd
import numpy as np
import time 
import pwd
import re
import io
import nltk
import sys
import string
import plotly.graph_objects as go
import plotly.express as px
import seaborn as sns
import math
import plotly.graph_objects as go
import plotly.express as px
import warnings
import boto3
import s3fs
import ipywidgets as widgets
from tqdm import tqdm_notebook as tqdm
from IPython.display import Markdown, display
from ipywidgets import FileUpload
from ipywidgets import TwoByTwoLayout
from ipywidgets import interact, interactive, fixed, interact_manual
from ipywidgets import VBox, HBox, Label, Box
from ipywidgets import Button, Layout
from nltk.corpus import stopwords
from nltk.corpus import wordnet
from scipy import stats
from scipy.stats import shapiro
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.feature_extraction.text import TfidfVectorizer
```
* For OpenPrescribing
```
import numpy as np
import pandas as pd
import plotly.graph_objects as go
import plotly.express as px
import re
import seaborn as sns
import random
import time
import io
import ipywidgets as widgets
import ipywidgets as widgets
from ipywidgets import FileUpload
from IPython.display import Markdown, display
from ipywidgets import TwoByTwoLayout
from ipywidgets import interact, interactive, fixed, interact_manual
from ipywidgets import VBox, HBox, Label, Box
from ipywidgets import Button, Layout
```

* For Statistical analysis
```
import os
import pandas as pd
import numpy as np
import time 
import pwd
import re
import io
import nltk
import seaborn as sns
import pandas as pd
import ipywidgets as widgets
import sys
import string
import math
import plotly.graph_objects as go
import plotly.express as px
import warnings
import boto3
import s3fs
import math
import matplotlib.pyplot as plt
import seaborn as sns
from IPython.display import Markdown, display
from ipywidgets import TwoByTwoLayout
from ipywidgets import interact, interactive, fixed, interact_manual
from ipywidgets import VBox, HBox, Label, Box
from ipywidgets import Button, Layout
from scipy import stats
from ipywidgets import FileUpload
from nltk.corpus import stopwords
from nltk.corpus import wordnet
from scipy import stats
from scipy.stats import shapiro
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.feature_extraction.text import TfidfVectorizer
```
