FIGURE INSERTION GUIDE

1. Save every image file in this common figures folder.
2. In a chapter file, replace the sample placeholder with:

   \begin{figure}[htbp]
     \centering
     \includegraphics[width=0.8\textwidth]{your-figure-file.png}
     \caption{Write a clear, descriptive caption.}
     \label{fig:descriptive-name}
   \end{figure}

3. Refer to the figure in the thesis text with:

   Figure~\ref{fig:descriptive-name}

Do not create chapter-specific figure folders.
