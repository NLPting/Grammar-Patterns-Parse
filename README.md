# Grammar-Patterns-Parse
### Find patterns from http://arts-ccr-002.bham.ac.uk/ccr/patgram/

#### 目的 （一）
依Ching-Yu學姊要求所做的group解釋

說明 :
pg.notes.txt 主要是做group的說明(Note)
(1)因為文本中有other pattern的存在所以會有四種階層(hd1、hd2、hd3、hd4)
(2)不過文本大多數的情況只有三層group階層(h1、hd2、hd3) (h1、hd3、hd5)

舉例 (一)

在html代表的標籤(hd1、hd2、hd3)
Ex: 主要 group - V 
      次要 group - Other related patterns
      次次要group - V the fact that  
      
Ex: pg.notes.txt 呈現則是:

      主要 01	[10]	10 V that

      次要 01	[10][10]	Other related patterns	Note:	Verbs concerned with feeling or thinking which do not have the pattern V that can be followed by the fact and a that-clause, to form a structure which has a similar function to that of V that.

      次次要 01	[10][10][10]	V the fact that	Note:	Verbs concerned with feeling or thinking which do not have the pattern V that can be followed by the fact and a that-clause, to form a structure which has a similar function to that of V that.

舉例 (二）

在html代表標籤(hd1、hd3、hd5)
Ex: 主要 group - V to-inf 
      次要 group - Structure I: Verbs in phase
      次次要group - I.1 The `begin' group

Ex: pg.notes.txt 呈現則是:
      主要 01	[8]	8 V to-inf
      次要 01	[8][8][8]	Structure I: Verbs in phase	Note:	Verbs with this structure belong to the following meaning groups:
      次次要 01	[8][8][8][8]	I.1 The `begin' group	Note:	These verbs are concerned with starting, stopping, or continuing an action.


頗析pg.notes.txt格式 :
Ex: 01	[8][8][8][8]	I.1 The `begin' group	Note:	These verbs are concerned with starting, stopping, or continuing an action.
01: 章節
[8][8][8][8] : 8代表章節一的第8個group開頭，四個[8]則是次次要group)


額外補充：
pg.notes.txt內，階層沒有統一化，意思是有些例子是沒有三層的架構((h1、hd2、hd3)、(h1、hd3、hd5))，而是兩層((hd1、hd3)、(h1、hd2)......等)



#### 目的 （二）

目的 : 
依Ching-Yu學姊要求所做的，新增group中的子group呈現

說明 :
pg.verbs.txt是額外加上子類

舉例:

原本的資料是：
01-19	[2 V n]<Obj>	<II.1 kill/eat/fix>	Ex	Wobbly teeth in unsound gums are as much of a problem in adults as tooth decay. Toxins that <i>attack</i> the connective tissue and bone which support the teeth are to blame.

新增後 : 

01-19	[2 V n]<Obj>	<II.1 kill/eat/fix::kill>	Ex	Wobbly teeth in unsound gums are as much of a problem in adults as tooth decay. Toxins that <i>attack</i> the connective tissue and bone which support the teeth are to blame.

多了::kill的子類





