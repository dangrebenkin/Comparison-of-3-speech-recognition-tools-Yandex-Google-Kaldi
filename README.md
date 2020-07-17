There is a work comparison of Kaldi(kaldi-ru 0.6), Yandex Speech Kit and Google Speech API, I used a validation subset of open_stt (https://github.com/snakers4/open_stt/) - Russian speech dataset and WER, CER metrics.

During the recognition I noticed that Google and Yandex tools wrote some numbers as numbers, not as the words (like "1" instead of "один"), so I fixed it.

Finally, Yandex had the best values, especially it was good at recognition of short files; Kaldi spend the most amount of time to recognize 28111 files - it was about 12 hours. But I think Kaldi is still good to use because you can tune it whatever you want in comparison with Google and Yandex tools, which servers are far from you.

Post on habr.com: https://habr.com/ru/post/470696/
