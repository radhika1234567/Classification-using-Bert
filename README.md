# Classification-using-Bert
I used 'The 20 Newsgroups dataset’.
(a)	Since Bert cannot take a sequence length greater than 512, truncate your tokens (including special tokens = 512) . 
Both <CLS> and <SEP> should be included. If you get GPU memory issues , use a smaller batch size. 
(b)	Truncate sequence length to 128 tokens.
(c)	Truncate sequence length to 140 tokens.
(d)	Repeat (a), (b) and (c) but truncate the head (keep <CLS>  and <SEP>) i.e. we will now discard tokens from beginning of sentence rather than the end.
(e)	Repeat (a), (b) and (c) – discard middle tokens. For example, for (a) keep <CLS> , 125 after <CLS>, <SEP> and 125 before <SEP> (total of 512 Tokens). 
So, in this part we are discarding middle tokens
