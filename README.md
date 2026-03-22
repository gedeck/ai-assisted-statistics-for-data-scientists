[![](https://img.shields.io/badge/python-3.8--3.12-blue.svg)](https://www.python.org/downloads/)
![Python](https://github.com/gedeck/dmba/actions/workflows/build.yml/badge.svg)

# AI-Assisted Statistics for Data Scientists
Code repository for O'Reilly book



# Code repository
<table width='100%'>
 <tr>
  <td><img src='images/OReilly-english.jpg' width=300></td>
  <td>
   <p><b>Practical Statistics for Data Scientists:</b></p>

   <p>50+ Essential Concepts Using R and Python<br>
by Peter Bruce, Andrew Bruce, and <a href="https://www.amazon.com/Peter-Gedeck/e/B082BJZJKX/?&_encoding=UTF8&tag=petergedeck-20&linkCode=ur2&linkId=089cd2d466348aa1e598aab0a42aa207&camp=1789&creative=9325">Peter Gedeck</a></p>

   <ul>
    <li>Publisher: <a href="https://oreil.ly/practicalStats_dataSci_2e">O'Reilly Media</a>; 2nd edition (June 9, 2020)</li>
   <li>ISBN-13: 978-1492072942</li>
    <li>Buy on 
     <a href="https://www.amazon.com/Practical-Statistics-Data-Scientists-Essential/dp/149207294X?&_encoding=UTF8&tag=petergedeck-20&linkCode=ur2&linkId=71ac36e6b2d734c5dc9d7d432a1a860c&camp=1789&creative=9325">Amazon</a></li>
   <li>Errata: <a href="http://oreilly.com/catalog/errata.csp?isbn=9781492072942">http://oreilly.com/catalog/errata.csp?isbn=9781492072942</a></li>
   </ul>
    </td>
  </tr>
</table>


## Online
View the notebooks online:
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/gedeck/practical-statistics-for-data-scientists/tree/master/)

Excecute the notebooks in Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/gedeck/practical-statistics-for-data-scientists/HEAD)

 This can take some time if the binder environment needs to be rebuilt.

## Other language versions
<table>
  <tr>
    <td><img src='images/OReilly-english.jpg' width=200></td>
    <td><b>English:</b><br>
     Practical Statistics for Data Scientists: 50+ Essential Concepts Using R and Python<br>
     2020: ISBN 149207294X<br>
     <a href='https://www.google.com/books/edition/Practical_Statistics_for_Data_Scientists/F2bcDwAAQBAJ?hl=en'>Google books</a>,
     <a href="https://www.amazon.com/Practical-Statistics-Data-Scientists-Essential/dp/149207294X?&_encoding=UTF8&tag=petergedeck-20&linkCode=ur2&linkId=01266bb457a44268bc7efdb80d6c7312&camp=1789&creative=9325">Amazon</a>
    </td>
  </tr>
</table>


## See also
Code repositories for first and second edition:
- First edition: <a href="https://github.com/andrewgbruce/statistics-for-data-scientists">https://github.com/andrewgbruce/statistics-for-data-scientists</a>
- Second edition: <a href="https://github.com/gedeck/practical-statistics-for-data-scientists">https://github.com/gedeck/practical-statistics-for-data-scientists</a>


# Setup of R and Python environments

We recommend using a conda environment to run the Python and R code.

```
conda create -n asda # Create the conda environment named asda.
conda activate asda # Activate the environment we created.
conda env update -n asda -f environment.yml # Update the R environment from the environment.yml file
pip install -r requirements.txt  # Installs all required Python dependencies
```

The full list of Python and R dependencies from the [environment.yml](environment.yml) file:
