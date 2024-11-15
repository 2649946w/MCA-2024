# Week 9
# Song 1 - Maozur
Wave -
![bmmaozurwave](https://github.com/user-attachments/assets/a87d34a1-3bcb-4f07-9dfe-b869cf4802dd)
Spectogram - 
![bmmaozurspecto](https://github.com/user-attachments/assets/072897e8-03ee-4ffe-a8f4-f10a36304737)
Mel Frequency Cepstral Coefficient -
![bmmaozurmelfreq](https://github.com/user-attachments/assets/e9b46124-3841-435e-a3f8-740e5aba44bc)
 Chromagram -
![bmmaozurchromo](https://github.com/user-attachments/assets/d67f7eb8-9738-4a7f-88f8-f7a7b3e45b83)

# Song 2 - Adon Olam
Wave -
![adonolamwave](https://github.com/user-attachments/assets/d4d0a1af-2eaf-43e1-a684-cd28208a5cd4)
Spectogram - 
![adonolamspecto](https://github.com/user-attachments/assets/05d583c4-1bfb-4e73-a33b-29d47fd5cab8)
Mel Frequency Cepstral Coefficient -
![adonolammelfrq](https://github.com/user-attachments/assets/46df43ed-30ea-449d-8154-86d4fd87e53f)
Chromagram - 
![adonolamchroma](https://github.com/user-attachments/assets/8da71e43-c858-4238-9b99-eb463583376c)

# Song 3 - Hava Nagila
Wave -
![havanagilawave](https://github.com/user-attachments/assets/a0b27a60-6200-427b-9a5a-fe8d60aff5b8)

Spectogram -
![havanagilaspecto](https://github.com/user-attachments/assets/3f26bbc7-2bfa-43be-81d6-cef03a0affb4)

Mel Frequency Cepstral Coefficient -
![havanagilamelfreq](https://github.com/user-attachments/assets/aaec42b9-ada2-4ba7-925d-11152b5f2459)

Chromagram - 
![havanagilachroma](https://github.com/user-attachments/assets/a0f768d0-fcec-46e5-8d97-7413599da82f)

## Jupyter Notebook Files
### Maozur
[Maozur Spectogram](maozurspecto.ipynb)

[Maozur Chromagram](maozurchroma.ipynb)

[Maozur Mel Frequency Cepstral Coefficient](maozurmelfreq.ipynb)
### Adonolam
[Adonolam Spectogram](adonolamspecto.ipynb)

[Adonolam Chromagram](adonolamchroma.ipynb)

[Adonolam Mel Frequency Cepstral Coefficient](adonolammelfreq.ipynb)
### Hava Nagila
[Hava Nagila Spectogram](havanagilaspecto.ipynb)

[Hava Nagila Chromagram](havanagilachroma.ipynb)

[Hava Nagila Mel Frequency Cepstral Coefficient](havanagilamelfreq.ipynb)

## Analysis
Using the code provided in the example notebook, I created histograms for each individual CSV file. I did this in order to compare the minute changes between songs and waveform analysis type. I ran into a slight promblem that I was unable to fix in the creation of the individual histograms. An error was appearing stating - IndexError: index 3 is out of bounds for axis 1 with size 3. This was something that I was unable to fix. However, the program was still able to output histograms that contained variation from one another so it did not ruin the data analysis entirely.

Looking specifically at the Mel Frequency Cepstral Coefficient, the differences between the songs is minor. The initial heat map style graph displays very minor alterations, if any, between the different songs. The line graph displays almost identical trends, aside from the the values on the axis changing  for the different songs. The histogram also show essentially identical trends, with the axis values changing between songs. The final graphs have the most difference to one another, the x axis values change aswell as the individual graphs displaying different values. However whilst the position on the y axis may adjust, all three graphs maintain the same shapes as one another. There is minor alterations but the shape of the graph is maintained.

When conducting the Histogram analysis, I expected to see a great deal of difference between the songs. They have varying instrument numbers, volume levels, and all have peaks in deficits in different frequency bands. Furthermore, when vieweing the generated Spectogram, Chromagram and Mel Frequency Cepstral Coefficient waveform analyses, the difference between the songs are visually very clear. I initially expected that due to the clear visual differences aswell as indivdual sounds found in each song that the histogram analysis would reflect this. There are a few reasons as to why these could be so similar:
-

[← Back: Week 8](page8.md) | [Next: ReadMe →](README.md)
