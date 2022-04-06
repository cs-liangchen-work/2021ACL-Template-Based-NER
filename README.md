# 2021ACL-Template-Based-NER
这是一篇对Template-Based Named Entity Recognition Using BART的复现。

原文地址：https://arxiv.org/abs/2106.01760

原github地址：https://github.com/Nealcly/templateNER

inference.py 中：

output = model(input_ids=input_ids.to(device), decoder_input_ids=output_ids[:, :output_ids.shape[1] - 2].to(device))[0]

encoder和decoder理解的没问题。
