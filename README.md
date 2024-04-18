# Test Mermaid rendering
The sole purpose of this project is to test/verify the rendering capability of mermaid diagrams from the README.md

```mermaid
%%{ init: { 'flowchart': { 'curve': 'stepBefore' } } }%%
graph LR
b1[Block One]-->b2[Block two]
style b1 fill:red,stroke:red,shadow:shadow,color:white
style b2 fill:blue,color:yellow
b1-->b3[Block three]
style b3 fill:green,color:white,stroke-width:5px
b3-->b4((block four))
style b4 stroke-width:3,stroke-dasharray:5 5
```
