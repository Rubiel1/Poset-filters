# Poset-filters
This reposity contains the code of the paper "Order theory in the context of machine learning: an application" https://arxiv.org/abs/.


## Contents


* **Project Titles**
  - Poset-filters are a family of convolutional filters.

* **Overview**
  - 

  ![standart](https://user-images.githubusercontent.com/18435221/112927159-8c8d2100-90e2-11eb-93a0-69e93edf529b.png)


  - We wrote a function  [name](Poset-filters/code.py).
    
 
* **Example Usage**: 
For chinampas in a line:
```python
from chinampas import chinampa as ch
activations = [[0,0],[1,0],[4,4],[5,4],[6,4],[7,5]]
chain = ch.Chain_Chinampa(activations)
print(f" Will vertex 7 at time 6 be activated?  {chain.will_vertex_be_activated(7,6)} ")
print(f"list of pyramids in the chinampa: {[(pyramid.lP,pyramid.rP,pyramid.time) for pyramid in chain.pyramids]}")
```
   

* **Getting Started**
  - installation
    Clone this repo:
 
    git clone https://github.com/mendozacortesgroup/?.git
    cd poset_filters
  - prerequisites
    python >=3.7

  - location of:
    - code: [poset_filters](somelink)
    - issue tracker
    - notes:



* **Developer info**
  - Limitations and known issues
    

* **Colophon**
  - Credits -- code and algorithm: Luke Van Popering, Eric Dolores Cuenca and Antonio Arciniega-Nevarez.
  - Copyright and License -- see [LICENSE](somefile) file.
  - How to contribute: .
  - This project has received funding from the National Research Foundation of Korea (NRF) grant funded by the Korea government (MSIT) (No. 2020R1C1C1A01008261).
  - References:  https://arxiv.org/abs/




THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

Copyright (c) 2024-Eric R.  Dolores Cuenca, Susana López Moreno, Aldo Guzmán Sáenz, Sangil Kim, Jose Mendoza-Cortés 
