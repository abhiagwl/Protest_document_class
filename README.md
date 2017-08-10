Contains the code written for classifying protest news stories from non protest ones during the Summer 2017 internship at Univeristy of Texas at Dallas.
The models tried were :
>* CNN 
>* Bi-directional LSTM
>* Hierarchical Attention Networks
The future work will include incorporating the output of SEMAFOR as an input to a classifier which should ideally perform better than the current methods. Intution being that data is highly imbalanced and hence there is a limitation to what a model can learn from its raw form. SEMAFOR gives 
features which extend beyond the ones obtained from raw text. Frames and there elements, along with relations among the frames, makes it an interesting experiment.  
