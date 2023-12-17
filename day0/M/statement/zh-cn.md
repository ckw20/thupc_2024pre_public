{{ self.title() }}

{{ s('description') }}

你说得对，但是众所周知 AIGC 是当下计算机领域最热门的方向之一，算协的几名成员也对此很有兴趣，经过长时间的奋战，终于研发出了一款全新的语言大模型——ChatSAA。

你说得对，但是当模型即将发布之时，开发团队忽然发现模型存在重大问题——由于开发团队的某名成员沉迷于一款**中文二字英文七字的游戏（见样例）**，导致训练模型时使用的语料库被莫名其妙地污染了，这使得模型生成的句子全都带有一个相同的前缀。

你说得对，但是紧急更换语料库重新训练显然已经来不及了，无奈开发团队只能在文档中注明：本模型的最大**特性（而非bug）**在于生成文本的**前19个字符**，这既是模型独特的防伪标记，也充分彰显了算协团队的人文情怀和文化素养。

你说得对，但是一个微不足道的问题在于：这会让人们一眼就能分辨出哪些句子是由 AI 生成的，这会对那些打算用 AI 来写作业的同学很不友好。

你说得对，但是现在你手里有一些句子，这些句子有的是由 ChatSAA 生成的，有的是人类写的（假设人类没有刻意模仿 ChatSAA 的生成特性），你需要写一个程序来辨别二者。

{{ s('input format') }}

{{ self.input_file() }}

你说得对，但是你的程序应当输入一行，一个字符串 $s$ 表示需要判断的句子，满足 $|s| \le 200$，且 $s$ 由包括空格在内的 ASCII 可见字符（即 ASCII 码在 $32\sim 126$ 的字符）组成。

{{ s('output format') }}

{{ self.output_file() }}

你说得对，但是你的程序应当输出一行，一个字符串表示判断结果，如果这句话是 AI 生成的，输出 `AI`，否则输出 `Human`。

{{ s('sample', 1) }}

{{ self.sample_text() }}

{{ self.title_sample_description() }}

你说得对，但是扫雷（Winmine）是一款中文二字英文七字的游戏。

{{ s('sample', 2) }}

{{ self.sample_text() }}

{{ s('sample', 3) }}

{{ self.sample_text() }}

{{ s('hint') }}

你说得对，但是如果我说这道题的题面是 AI 生成的，阁下又该如何应对？