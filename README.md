# Zipfslaw-thirukural
Zipf's law states that The frequency of any word in a text is inversely proportional to its rank in the frequency table. It simply means that the most common word appears approximately twice as often as the second most common word, three times as often as the third most common word, and so on. This relationship follows a power-law distribution.
Objective : 
To check application of zipf's law on classic Tamil language text consisting Thirukural which of 1,330 short couplets, seven words each. 3 units /adikarams
Data : 
https://www.kaggle.com/datasets/rahulvks/thirukkural?resource=download
Results :
![download (1)](https://github.com/Saptharishee/Zipfslaw-thirukural/assets/82307484/e2d33957-7722-43de-a05f-5917f33b68f2)

However, the image does not fully follow Zipf’s law, because the red line, which represents the actual frequency of the words, deviates from the blue line, which represents the Zipf distribution. The red line has a steeper slope than the blue line, which means that the frequency of the words drops faster than expected by Zipf’s law. This indicates that there is more variation in the word usage in Thirukural than in a typical natural language text.

One possible reason for this deviation is that Thirukural is a highly structured and poetic text, which follows strict rules of rhyme, meter, and meaning. Therefore, some words may be more or less frequent than usual due to these constraints. Another possible reason is that Thirukural is a very old text, dating back to at least the 3rd century BCE1, and may reflect a different linguistic pattern than modern Tamil or other languages.

The deflection in the graph occurs when the rank is around 10^3. This means that there is a sudden change in the frequency of the words at this point. One possible explanation for this deflection is that there are many words that have very low frequency (less than 10 occurrences) in Thirukural, and these words may not follow Zipf’s law at all. These words may be rare or archaic terms that are specific to Thirukural or its context.

