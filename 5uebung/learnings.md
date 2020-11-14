## Learnings

- package tikz can be used for binary trees
- unbalanced trees can be achieved like this:
```
\begin{tikzpicture}
\node[circle,draw](z){$30$}
  child[missing]{}
  child{
    node[circle,draw]{40} child{node[circle,draw] {20}} child[missing] };
\end{tikzpicture}
```
- when you have a node with childs and you want to have a left text then the description need to be at the end after all childs
- tables can be achieve like this while c defines the amount of columns:
```
\begin{tabular}{ c c c }
 cell1 & cell2 & cell3 \\ 
 cell4 & cell5 & cell6 \\  
 cell7 & cell8 & cell9    
\end{tabular}
```
- curly brackets can be escaped into text like this:
```
\texttt{\{texthere\}}
```