the johnny decimal system[^1] is meant as an approach to store [[information]] based on the [[dewey decimal classification system|dewey decimal system]] using decimalized numbering.

the idea is to force a shallow file structure by having your entire set of files, $S$ in maximally ten super-groups with ten subjects in each super-group, which is then finally subdivided into ten subgroups[^2]. conceptually, i think it makes the most sense to look at as a [[tensor]]: 

$$
S 
= 
\begin{Bmatrix}
\text{admin super-group 00-09: \quad} 
\begin{bmatrix}
\text{admin group 00:}\quad\begin{pmatrix}
\text{admin-admin subject 00.00} \\
\text{admin subject 00.01} \\
\vdots \\
\text{admin subject 00.09}\\
\end{pmatrix}  \\ \\
\text{group 01:}
\quad\begin{pmatrix}
\text{admin subject 01.00} \\
\text{subject 01.01} \\
\vdots \\
\text{subject 01.09}\\
\end{pmatrix} \\ \\ \vdots \\ \\
 
\text{group 09}\quad\begin{pmatrix}
\text{admin subject 09.00} \\
\text{subject 09.01} \\
\vdots \\ 
\text{subject 09.09}\\
\end{pmatrix} \\
\end{bmatrix} \\  
\\
\text{super-group 10-19: \quad}
\begin{bmatrix}
\text{admin group 10:}\quad\begin{pmatrix}
\text{admin-admin subject 10.00} \\
\text{admin subject 10.01} \\
\vdots \\
\text{admin subject 10.09}\\
\end{pmatrix}  \\ \\
\text{group 11:}
\quad\begin{pmatrix}
\text{admin subject 11.00} \\
\text{subject 11.01} \\
\vdots \\
\text{subject 11.09}\\
\end{pmatrix} \\ \\ \vdots \\ \\
 
\text{group 19}\quad\begin{pmatrix}
\text{admin subject 19.00} \\
\text{subject 19.01} \\
\vdots \\ 
\text{subject 19.09}\\
\end{pmatrix} \\
\end{bmatrix} \\  
\\ \\
\vdots \\
\\
\text{super-group 90-99: \quad}
\begin{bmatrix}
\text{admin group 90:}\quad\begin{pmatrix}
\text{admin-admin subject 90.00} \\
\text{admin subject 90.01} \\
\vdots \\
\text{admin subject 90.09}\\
\end{pmatrix}  \\ \\
\text{group 91:}
\quad\begin{pmatrix}
\text{admin subject 91.00} \\
\text{subject 91.01} \\
\vdots \\
\text{subject 91.09}\\
\end{pmatrix} \\ \\ \vdots \\ \\

\text{group 99}\quad\begin{pmatrix}
\text{admin subject 99.00} \\
\text{subject 99.01} \\
\vdots \\ 
\text{subject 99.09}\\
\end{pmatrix} \\
\end{bmatrix} \\  
\end{Bmatrix}
$$


the idea is of course that the folder count can be changed as needed, but that you are forced to secure a shallow [[file tree]]. nothing stops you from using for other systems.

the main disadvantage of using such a system (outside of initial time cost of making your index) is the lack of ability to store multi-category items. we, as humans, have a bad tendency to put things in boxes that defy such an inherent act of violence. so how do you solve that? as always, [[public voit]] has the answer: [[tagging]].

[^1]: the "Johnny.Decimal system" is licensed  under Attribution-NonCommercial-ShareAlike 4.0 International [on their  website's license page](https://johnnydecimal.com/00-09-site-administration/01-about/01.02-licence/)
[^2]: the numbers 00-09 are reserved for managing the system itself 
