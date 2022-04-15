# CoCLSA
Corpus of Chinese Linguistic Semantic Acceptability
## Dataset
We use the web crawler to obtain Chinese multiple-choice questions related to incorrect semantic sentences from the high school examination online resources in the past ten years. Then we organize these data into a dataset with a total of 24,228 sentences with two labels. One of the labels is correct sentences, and the other is incorrect semantic sentences. We choose 45,248 sentences as the train dataset, 2,160 sentences as the validation dataset, and 2,000 as the test dataset. Since most of the multiple-choice questions we crawl are sentences with semantic errors, there are more semantic incorrect sentences in CoCLSA. To ensure reasonableness, we divide the validation and test sets with the same number of correct and incorrect semantic sentences. Therefore, the proportion of incorrect semantic sentences is higher in the training set.
| Dataset| #Line | Avg.Length | Error Ratio |
| :---: | :---: | :---: | :---: |
| Train |  45,248 | 50.4 | 74.6% |
| Dev |  2,160 | 52.6 | 50.0% |
| Test |  2,000 | 54.5 | 50.0% |
