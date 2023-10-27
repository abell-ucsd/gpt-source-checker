# gpt-source-checker
A script that uses chatGPT to check if a source text supports a claim. This program can handle massive source texts such as books.

Just copy the text and citation you want to validate, and run the script.
![image](https://github.com/abell-ucsd/gpt-source-checker/assets/78572930/f5179728-e722-4a53-b0d4-b8cf91544675)
Output:
```
Passage being validated:
He currently holds the title of Associate Adjunct Professor in Neurosciences at the University of California San Diego.


Answer: 
Quotes from the ## Source relevant to determining the validity of the ## passage:
- "Nathan Shaner...Title(s)Associate Adjunct Professor, Neurosciences"
- "SchoolVc-health Sciences-schools"

Based on these quotes from the ## Source, it can be concluded that the claims made in the ## Passage are supported by the text in the ## Source. The ## Source states that Nathan Shaner holds the title of Associate Adjunct Professor in Neurosciences at the University of California San Diego.
```

Set the `manual_paste_in` variable to `True` to manually paste in the passage and supporting text. this is sometimes neccesary as not all source texts can be easily accessed via a url (e.g. full books, some journals)



This script can handle massive source texts despite GPT-3.5-turbo's limiting 4k context length. 
