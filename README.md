missel-clercs
=============

Missel à l'usage des clercs de la liturgie catholique romaine avec rubrique


====
Rapide introduction à LaTex 

## Structure du document :
\section*{Gros Titre}

\subsection*{Moyen Titre}

\subsection*{Petit Titre}

## Formatage
Pour mettre en gras : 
{\bf Reponse}

Rubrique des clercs :
\rub{Thuriféraire}{Ensence trois fois la foule}

Rubrique du célébrant :
\cel{Le prêtre invite les fidèles à la pénitence, en disant~:}


Pour mettre en italique :
\emph{texte en italique}

Pour faire une note de bas de page : 
un texte super bien\footnote{ceci est en fait un texte mega bien}


## Formatage avancé : 
Pour passer en mode aligné à droite :
\begin{verse}
Gloria in excelsis Deo\\
Et in terra pax hominibus bonae voluntatis.\\
Laudamus te. Benedicimus te. Adoramus te.\\
Glorificamus te. Gratias agimus tibi\\
\end{verse}

les \\ sont des retours contraints à la ligne 


Pour passer sur deux colonnes:
\begin{minipage}[t]{0.5\textwidth}
texte colonne 1
\end{minipage}\begin{minipage}[t]{0.5\textwidth}
texte colonne 2
\end{minipage}
