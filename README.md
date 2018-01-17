## GAME: REPLACE VOWEL CHARACTER
对于一个给定的字符串，如果其中元音字母数目在整个字符
串中的比例超过了30%，则将该元音字母替换成字符串
mommy，额外的，在替换时，如果有连续的元音出现，则仅
替换一次。

**Specification By Example**

- hmm 经过处理后，应该保持原状
- she 经过处理后，应该被替换为 shmommy
- hear 经过处理后，应该被替换为 hmommyr

### Tasking Demo
- 输入一个元音，预期返回为mommy
- 输入一个非元音字符，预期返回字符本身
- 输入一个元音超过30%的字符串，预期元音被替换
- 输入一个元音超过30%，并存在连续元音字符，预期连续的元音字符只被替换一次