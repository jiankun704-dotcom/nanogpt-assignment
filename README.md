# nanogpt-assignment
基于 nanoGPT 的个人语言模型项目
项目简介
这是一个使用 nanoGPT 框架，从零开始训练一个小型语言模型的项目。该模型在一个自定义文本数据集上进行了训练，并能够根据学习到的模式生成新的文本。

本项目的目的是展示一个端到端（end-to-end）的语言模型训练流程，包括数据集准备、模型训练、文本生成以及最终的项目打包与分享。

项目运行环境
本项目在以下环境中成功运行：

操作系统: Windows

Python 版本: 3.9

依赖库: PyTorch, Transformers, Datasets, Tiktoken

硬件: 本项目在 CPU 环境下完成了训练和推理，无需专用 GPU。

数据集
本项目使用了一个名为 my_dataset.txt 的自定义数据集进行训练。这个数据集包含了 [在这里描述你的数据集内容，例如：“一系列诗歌”、“小说片段”或“对话文本”]。

训练过程
模型使用 config/train_my_model.py 配置文件进行训练。
训练过程在本地 CPU 上执行，总共运行了 5000 次迭代。训练好的模型检查点保存在 out-my-model/ckpt.pt 文件中。

推理结果
模型成功生成了符合数据集风格的新文本，满足了“十个以上连续的句子”的要求。以下是生成的文本样本：

number of parameters: 29.94M
No meta.pkl found, assuming GPT-2 encodings...

AUTOLYCUS:
As I have been nobly, I will not all your
and know no more known to know not.

First Servingman:
I shall come you, to be there
king-place.


Third Servingman:
Nor shall have, what we are in the mouse.

First Servingman:
To be so.


Third Servingman:
Mis, my master, go; he will.



MENENIUS:
The gods knows not be like it,
If he hath done 'tis taken; for
Why, that he was a word.


Third Servingman:
Hold, that's it is so
And shall be a warrant?

CORIOLANUS:
Not so; what is it.

First Servingman:
I would have it:
Thou wast never
The Servingman:
You must be so, to go
Will prove him, yet.

Second Servingman:
He's-day;
Should he cannot be.

CORIOLANUS:
So that's the world?

AUTOLANUS:
The Servingman:
Think you do't please you?

CORIOLANUS:
What's well obey me?

AUFIDIOLANUS:
There's the people.

CORIOLANUS:
I' the people.

Second Servingman:
I cannot do not pass'd; it isle.

CORIOLANUS:
Your dangerous Menenius:
That did see your tribunes.

MENENIUS:
Hear me, the people,
To be the people.

MENENIUS:
Let him hear the tribunes;
I shall seem'd you,
And I'll speak.

MENENIUS:
He must serve their
And,
Whereinius, that shall know the city.

First Servingius:
You cannot hear another, and will blush,
' the people will be consul.

Third Servingman:
Take a good Comin, I have fought
To help to lose his countrymen.

MENENIUS:
IUS:
Your voices must go;
For I pray your voices.

MEN
---------------


Provost:
LUCIO:
Could this, have seen in a love,
And my voice is my fault,
In noble doth attend on it with the hollow in
That set in me.

CLAUDIO:
Go, as I'll go with him be.

LUCIO:
The dost, you, look on:
Be call the state i' the duke.


CLAUDIO:
That, and, and as a word.

LUCIO:
That's mine, Isabel,
So will be a little while?

JULIET:
So shall my lord.

LUCIO:
As if you shall have said, stand in mine own.

LUCIO:
Sir, good love him to the day.

LUCIO:
You, and your honourable and amiss.

LUCIO:
My lord, fie your honourable amongst the mind.

LUCIO:

Hark! I'll not; him; for 'Charge!

LUCIO:
Come, peace, you, my lords, good?

LUCIO:
DUKE VINCENTIO:
Do you will you to not our pern.

LUCIO:
LUCIO:
My words will not.

MARIANA:
It boots not this is my lord.

LUCIO:
Tend eyes are come.

ISABELLA:
LUCIO:
I will be you; and undertake to do't.

LUCIO:
The duke will have return: it be gone,
And in your honourable.

LUCIO:
Well, my lord.

LUCIO:

ISABELLA:
Signior Claudio! it so!

LUCIO:
LUCIO:
How late, my dear! it?

ISABELLA:
How, to your honourable:
So no sin?

LUCIO:
Would have been what you answer?

CLAUDIO:
Why no other's the law?

ANGELO:
To hear me.

ISABELLA:

ISABELLA:
It is
---------------

First Servingman:
Better it be that I had no
he Servingman:
In any woman's a man
That has been aired abroad; and tell thee, or
are been too old man; but that
vice in with twenty thought of the neck; but
and let him do, might have in the
his raising; and pite you
they have been in the report; for
disturgh; but but
are no more than
think you, and
and of the business.

First Servingman:
I'll serve to him:
You were rich thing.

Third Servingman:
Let him have enough; heigh!

Third Servingman:
I'll be of his part.

Third Servingman:
Whereinius?
Third Servingman:
The business is a man's a box.



Third Servingman:
The lack of the people?


First Servingman:
Why, there's a man
many of,
and i' the wars.

First Servingman:
How?


First Servingman:
All:
How is a business; the Capitol.


First Servingman:
He has always loved him.

AUFIDIUS:
He cannot swear it is worthiest,
pleased him.

First Servingman:
I'll never shall not.


First Servingman:
Have you will speak of your eyebrows.

First Servingman:
I'll go.

First Servingman:
In the business.

Second Servingman:
O:
What has a respected of him?

MENENIUS:
Ye see the noise of boasting.

First Servingman:
Evermore were with me,--

First Servingman:
Pray, sir; he's the herdsmen, and a
the Servingman: I will be gone.


Second Servingman:
Be not, man comes the worst.

Third Servingman:
Why, your prithee, you will come.

Clown:
As wit shall be a
onesrician: we'll swear it.


First Servingman:
Here's twenty, and
are a dozen of
of the business.

First Servingman:
I do not so
---------------


As if you have you of you,
For such a few are most inherent my lord;
For the like you were your highness,
With he, in you.

PAULINA:
Should you have said, Camillo,
Do you do you tell you do
The breath with your high,
Which have landed, you make you are you,
And answer you held her, my lord.


PAULINA:
Soft!

LEONTES:
It is something
May say, my lord,
O'Tis like o' oracle were so much,
As you have your good,
To-:
Mine honour'd, more than you less.

PAULINA:
Madam, good sir,
So I would you'll to,
Should it so, make your comfort;
As you do request you are come as you do not.

HERMIONE:
Let me do, 'tis time:
On your person,
May be no more instructions.

PAULINA:
How!

LEONTES:
Out; you, good husband.

PAULINA:
Sir, madam, by:
My lord.

PAULINA:
That's much together,
Meant:
Be not so far than a good at hand,
The testimony than you in, and more than you.

PAULINA:
Let me send you have loved me be old.

LEONTES:
That's your lady.

PAULINA:
Account me leave you,
O:
We have not, madam, my Perditaethinks,
But only side, as I cut away;
With his face grafted to do beheld,
But by each other. Go you do your precious princess,
With all your former princess your highness,
And give your tongue.

PAULINA:
I have show your father.

PAULINA:
I have:
O, my lord, your good lord.

PAULINA:
I'll give you have done:
More near my lord, you. Give me.


PAULINA:
Sir, remember you have done,
I'll prove a sweet wife.

PAULINA:
To take
---------------

As 'tis guilty of your ignorance,
To bury your humble
As in your hands,
At your honour and your chiefest your purpose,
And, did it in your highness.

HERMIONE:
I have spoke as you.


LEONTES:
I may forget your queen--


HERMIONE:
I shall inform'd,
And the innocent as you,
How can do we'll stay on; therefore
Which you have to say 't.

LEONTES:
How now,--
There is!
LEONTES:
You'll
Sir,
'ld have it were your eyes?

LEONTES:
My lord,
Make them out.

PAULINA:
And trust me, adieu,
This is like a jealousies'er the last,
Of your lords
The unreasonable sort and speed.

LEONTES:
I will not dismay'd for't: 's
You'll be tied.

LEONTES:
I shall be, you:
Never,
You'll no more more to make this,
Which you do so long to you do. Beseech you will be

LEONTES:
No,
Upon the best shall have it. Or I would have

LEONTES:
But you have not do not bear a bastard.

PAULINA:
Sir, with your counten,
Even to-night.

LEONTES:
Even so, like a past them.
What's your highness?

LEONTES:
You're bound, Fortune,
He shall make the best senses.

PAULINA:
When you will you too late!

PAULINA:
I am sorry, if you have you do it,
I pray you do; and each,
And shall have no law upon mine honourily.


PAULINA:
Madam, no less, I'll do; and I shall be seen,
When my daughter.

PERDITA:
So it is the business.

PAULINA:
No help the curtain.
Do you will:
I'll give this, be gone: we'll go back you;
And you, be you have no more fearful,
For
---------------

If you do, more.

LADY ANNE:
For how is thy unthou art thou hast thou art thou,
And thou hast thou wert poison'd thee,
Forst not for thyself; but this hand.

JULIET:
And, mad thou hast thou sleep'd, take thy daughter.

JULIET:
Thou, be, well thou hast thou mayst do thou run to my soul.

JULIET:
O me,
To stop thy curse nor tears, let him be ill.

FRIAR LAURENCE:
Now, Romeo, Romeo, tell thee to kill thy fair,
The man's peace in his hands,
And thou wilt be much,
But thou slew'st thou dost bait from death,
Thou canst thou wilt thou quake,
Thy husband in this,
Thy father, thou hast an enemy;
There'st thy mother, thou seest death,
For thou hast thou dream'st thou wilt,
That thou wouldst be in thy soul'st thou shamest,
Thou wilt amend thy lady'st and a breath,
To kill his wife, nor love,
And, thy soul, being no deed!

JULIET:
Thou wilt me, hear;
A grave, I mayst thou hast thou weep'st thou death,
O, no love'st thou hast thou my love to kill my own.

JULIET:
IET:
Why, and Romeo; wherefore my love to back,
Nor shall not stay upon thy places shall be gone.
O, what name, say? dost thou shalt have thee,
What is thy father?

ROMEO:
I will I can do no man.

JULIET:
Give me, my lord; and turn thy love;
And I'll have no more speech, if thou would have hadst thou love.
IET:
For I saw me my lord, for any hours will weep in wilt.

PARIS:
O, madam, I'll not be,
To give a bug that I am to do I must end.

JULIET:
Within my lord, madam,

---------------

To make your own.

LEONTES:
Not so:
No;
A most likely you out,
And so do this, and
CAMILLO:
I'll draw the unsha,
You are too late.

LEONTES:
I have much.


LEONTES:
Mark thee:
My lord,
As thou hast gods have said so
Which in so late
Or the bastard'st the queen in't.

PAULINA:
More criminal in authority,
When the or didst am sure upon your request
Of your daughter.
I am fondly,
I do remember me,
Thy queen as I am a bastard,
The which, no more accusation soul,
Than of commanded,
And making a sickness of such a weeping.

LEONTES:
Your parents,
No more.

FLORIZEL:
You shall be, good Camillo,
And to be violent of; but
The gods do change, to be ignorant,
He might have been for my lie condemn'd:
Worthyly gifts,
Which shall be so it is: nor I
To make't, my lord I
Yet I need not remember, nor rather have done, I feel,
So much to be long.

LEONTES:
Address yourself.POLIXENES:
O:
Your lord, Camillo,
The gods, Camillo, not something had rather have received,
To let me be out of me be.

LEONTES:
Will't please youreech you this,
From the time,
To your evil, if you have, never
What's own
HERMIONE:
Your very well,
You'll make some past love to the climate.

FLORIZEL:
That's not perceive you.
LEONTES:
Ye two unutes your eyebrows, you shall make them on.
I have heard your cranks your business,
To help you do this will leave to you,
To give your part them what you.

CAMILLO:
There is taken,
He shall have a piece the hostess the queen.

LEONTES:
And for to a party for man;
Which you not, as you, no
---------------

And so shall be so, if he shall be sin.

First Murderer:
Yea, my lord, my good!
Second Murderer:
Remember, which is:
In that part 'twas but it as being so.

First Murderer:
Take him of him?
First Murderer:
Here's a man.

Second Murderer:
It is my father: but a lord.

Second Murderer:
Marry, some!


Second Murderer:
No, fem!
Second Murderer:
There'st:
I can, to do't please you.

Third Murderer:
Ay, or thy father: he cannot hear it.

First Murderer:
What will not? would it; it will pray, he
deliver him.

Second Murderer:
Say yet?
Second Murderer:
Not it was a warrant, he's a warrant, he would not forgot the
but, it is a man: it was a man
the Murderer: and here's, theyptuous and he
he is a man.

Third Murderer:
I had forgot, if they.

Second Murderer:
Come, he's a dozen of him.

First Murderer:
My conscience made my knee.

Second Murderer:
Your eyes will be king: in my heart.

Second Murderer:
Who will have done: we could have seen,
For they could have; butchers have seen the king's neck,
Must he did I am in the people's.

Second Murderer:
The army;
I'll have been ta'enius, and my hate,
Our pleasure shall be done; and their office,
And from your voices and bring him.

Second Murderer:
I am not them.

Third Murderer:
Why, no further:
My lord, will have been cozener lies a little more I heard;
All army will not heard the crown!

Second Murderer:
My lord, did I say 'twas my business.

Second Murderer:
He shall have heard of Gloucester'st:
And as I may be and that hope.

First Murderer:
I would have done a busy day.
---------------



Third Servingman:
Here comes here's no?
All:
Here ye your honour.

Second Servingman:
Consider him; but he
Tis risen: he will.

Third Servingman:

He has in him: and that did he will.

First Servingman:
What's a dozen of that?

Second Servingman:
Why should you will chop him,
Have he dost.

First Servingman:
Not a man, it a
MENENIUS:
Why, that did not so?

Third Servingman:
Things to beheld
ithee.


First Servingman:
Come, prithee, master, or no wine:
What one thing
shearers, and the last in wild-pipes.

MENENIUS:
What's the good morrow.

MENENIUS:
At my peace! the news?

Second Servingman:
Now, nor news?

First Servingman:
You will be.

CORIOLANUS:
If I do good is not die?

MENENIUS:
Wherefore?

Second Servingman:
How!

First Servingman:
The Servingman:
One of the truth: the entertainment shall have:
Do't, sir.

CORIOLANUS:
Not it is the minst to be spoke of all,
and I'll take it up our country.

MENENIUS:
For I will not be?


MENENIUS:
Think you, what's no,
Will I'll, as you do it.

Citizens:
What shall have a herd of your soldier.

MENENIUS:
Do not be
Ye do you'll give me in your good
Whereinius,
AUFIDIUS:
Why?

AUFIDIUS:
That, we will have not; and clubs?

MENENIUS:
You'll never shall be your power,
With my place?


CORIOLANUS:
Go I'll do.

CORIOLANUS:
Well, tribunes for you mask'd you,
For blood, sir.' Pray,

MEN
---------------


ROMEO:
Then call her beauty is for Romeo's enm on a house.

ROMEO:
And Romeo;
The sun is the churchft of Tybalt's eyes of tears:
O Clifford's will night,
FRIAR LAURENCE:
O, I lie is the point writ, and Romeo
But Romeo, pale Tybalt,
The county; the mattock to-flies cried Romeo,
It will I;
Our same Capulet; Tybalt, Romeo,
And Romeo's death, an new,
Therefore, cords:
O wither straight; and Romeo's Mercutio.


ROMEO:
O, night, stop our Romeo's he light, with the thing.
All hither, Romeo!

ROMEO:
O, black shape, and Romeo!

FRIAR LAURENCE:
An Juliet, what is Tybalt, what,
Romeo? no Montagues!

ROMEO:
Thou woe's thy father:
Youeps for that breath.

JULIET:
You will chop the night:
I would have, you shall have I say,
And do; I'll not love myself;
Thou canst thou, as I see,
That is in a vault.

JULIET:
This is this, though it so bad!

ROMEO:
O, like a torch like a ghostly eagle's,
The damned dismal light words.

JULIET:
O, for that hand, be Romeo,
Had been? or Romeo?

JULIET:
What wilt thou lark! be a torch? Capulet;

For Tybalt, be not from night,
And Romeo's ground?
FRIAR LAURENCE:
I shall be her not swear so.


ROMEO:
O, Montague, to murder hath lak'd.

FRIAR LAURENCE:
O, my father, like a little days shall have to-night.

JULIET:
'Tis my lord, no shape, nor death,
But trust not live, nor wit but have bought the world,
And I should have someRIAR LAURENCE:
Now, that
---------------

如何运行
要复现本项目，请按照以下步骤操作：

克隆本仓库：

git clone [https://github.com/jiankun704-dotcom/nanogpt-assignment.git](https://github.com/jiankun704-dotcom/nanogpt-assignment.git)
cd nanogpt-assignment

安装所有依赖项：

pip install torch torchvision torchaudio
pip install transformers datasets tiktoken

运行数据准备脚本：

python data/shakespeare/prepare.py

运行训练脚本：

python train.py config/train_my_model.py

运行推理脚本以生成文本：

python sample.py --out_dir=out-my-model --max_new_tokens=500

致谢
感谢 Andrej Karpathy 提供的出色的 nanoGPT 项目。

感谢本项目所使用的所有开源库和工具。
