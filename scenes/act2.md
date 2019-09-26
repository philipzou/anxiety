# act2

`SceneSetup.act2();`

{{if _.badnews && !_.factcheck}}
(#act2-preamble-news1)
{{/if}}

{{if _.badnews && _.factcheck}}
(#act2-preamble-news2)
{{/if}}

{{if _.catmilk}}
(#act2-preamble-cat)
{{/if}}

(#act2-preamble-tinder)


# act2-preamble-news1

```
publish("act2",["dee",3]);
```

s: But did you *see* that "news story" about that horrible thing happening somewhere?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: h-hi...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: God I hate the news. It's all sensationalism and clickbait.

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: n... nice party...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: True, but they're just following incentives. The *real* problem is people who click the clickbait.

```
publish("act2",["dee",3]);
```

s: Who would retweet a terrible news story, and make all their friends feel bad?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, I know right?

(#act2-preamble-end)


# act2-preamble-news2

```
publish("act2",["dee",3]);
```

s: But did you *see* that "news story" going viral?

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: h-hi...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",3]);
```

a: Yeah, totally fake. Who would fall for that and retweet it?

```
publish("act2",["dum",2]);
publish("act2",["party_hong","next"]);
```

h2: n... nice party...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Seriously dude. Like, hello, open up Google and factcheck first?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, I know right?

(#act2-preamble-end)


# act2-preamble-cat

```
publish("act2",["dee",3]);
```

s: Like I was saying, the Meme Industrial Complex exploits cats.

```
publish("act2",["dee",2]);
publish("act2",["party_hong","next"]);
```

h2: h-hi...

```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: Elaborate on this thesis.

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: n... nice party...

```
publish("act2",["party_hong","next"]);
publish("act2",["party_hunter",0]);
publish("act2",["dee",1]);
```

s: Well, I saw someone retweet a GIF of a cat drinking milk yesterday.

```
publish("act2",["dee",3]);
```

s: They can't digest that ^crap^! Who would retweet *animal abuse* like that?

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, I know right?

(#act2-preamble-end)


# act2-preamble-tinder

```
publish("act2",["dee",1]);
```

s: 没错对方一直没回我！

```
publish("act2",["dee",0]);
publish("act2",["party_hong","next"]);
```

h2: 那…那个…
```
publish("act2",["party_hunter",1]);
publish("act2",["party_hong","next"]);
publish("act2",["dum",1]);
```

a: 在app上配对成功了都不回？

```
publish("act2",["dum",0]);
publish("act2",["party_hong","next"]);
```

h2: 额…你们好啊…

```
publish("act2",["party_hong","next"]);
```

{{if _.serialkiller}}
(#act2-preamble-serialkiller)
{{/if}}

{{if _.hookuphole}}
(#act2-preamble-hookuphole)
{{/if}}

{{if _.pokemon}}
(#act2-preamble-pokemon)
{{/if}}

# act2-preamble-serialkiller

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Yeah I dunno! What, did they think I was a *serial killer* or something? So paranoid.

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Ugh, I know right?

(#act2-preamble-end)


# act2-preamble-hookuphole

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: 就是啊！完全搞不懂，难不成还指望我填补它心灵上空白吗？

s: 那么矜持干什么？*开放*一点好不好！

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: 额，可不是嘛。

(#act2-preamble-end)


# act2-preamble-pokemon

```
publish("act2",["party_hunter",0]);
publish("act2",["dee",3]);
```

s: Yeah I dunno! They weren't that hot, but they would have been a nice catch!

```
publish("act2",["party_hunter",1]);
publish("act2",["dee",2]);
publish("act2",["dum",3]);
```

a: Gotta Catch 'Em All!™

(#act2-preamble-end)


# act2-preamble-end

```
Game.clearText();
publish("act2-out-1");
music(null, {fade:1});
```

(...3000)

```
music('battle', {volume:0.5});
publish("hp_show");
bb({body:"normal", mouth:"normal", eyes:"normal"});
```

n: 第二轮 : *FIGHT!*

[他们全都讨厌我们！](#act2a_social)

[你刚才一直盯着红头发的来着？](#act2a_perv)

[要不，我们来探讨人生吧。](#act2a_meaning)

# act2a_social

`bb({eyes:"sad"})`

b: We're bringing down the mood of this party by being such a sad lump!

`bb({eyes:"shock", body:"two_up"})`

b: We're killing the good vibes! We're committing first-degree vibe-murder!

`bb({eyes:"normal", body:"normal"})`

b: Human, we have to leave *now* before--

```
_.a2_first_danger = 'social';
_.a2_attack_1 = "alone";
```

(#act2b)

# act2a_perv

`bb({eyes:"suspect"})`

b: They're more attractive than us, which means if we even *look* at them, then--

`bb({eyes:"shock", body:"two_up"})`

b: WE'RE CREEPS

`bb({body:"normal"})`

b: We're creepy, evil, bad bad bad terrible terrible perv--

```
_.a2_first_danger = 'perv';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2a_meaning

`bb({body:"one_up", eyes:"normal_r"})`

b: 归根到底，我们到底能做点什么有价值的事呢？

`bb({body:"normal", eyes:"sad"})`

b: 对人类社会作贡献吗？可是不管完成什么伟业总免不了尽归尘土。爱情？再伟大的爱情也难逃生死两隔。

`bb({eyes:"sad_r"})`

b: 死亡真的是无处不在。*我们*会死，*我们的亲人*也会死。

`bb({eyes:"shock", body:"two_up"})`

b: 哦对了！热力学第二定律证明了就算是我们的*宇宙*也终将消亡！

`bb({eyes:"suspect", body:"normal"})`

b: 哦, “死亡才使得生命有价值”？这就好比说奴隶制是有价值的因为它体现出了自由的价值！

`bb({body:"one_up"})`

b: 哦,“你需要追寻自己人生的价值”？这是邪教和搞阴谋论的那群人玩的那一套！

`bb({eyes:"shock", body:"two_up"})`

b: 生命没有意义，死亡没有意义，甚至*意义*本身也没有意义！凡人的灵魂就应该-

```
_.a2_first_danger = 'meaning';
_.a2_attack_1 = "bad";
```

(#act2b)

# act2b

`bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true})`

b: …

`bb({eyes:"suspect"})`

b: emmm……你还听得到吗？

`bb({eyes:"normal", MOUTH_LOCK:true})`

b: …

`bb({eyes:"shock", mouth:"small_talk", body:"chest", MOUTH_LOCK:true})`

b: *大吸一口气*

`bb({mouth:"small_talk"})`

b: **我必须警告你…**

[类似的危险*还有很多*！](#act2b_louder)

{{if _.a2_first_danger=="social"}}
[*另一种不同的*社交危险](#act2b_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[*另一种不同的*道德危险](#act2b_different_moral)
{{/if}}

[你正在无视危险！这本身就是危险！](#act2b_ignore)

# act2b_louder

`_.a2_first_choice = "louder"`

{{if _.a2_first_danger=="social"}}
(#act2b_louder_social)
{{/if}}

{{if _.a2_first_danger=="perv"}}
(#act2b_louder_perv)
{{/if}}

{{if _.a2_first_danger=="meaning"}}
(#act2b_louder_meaning)
{{/if}}

# act2b_louder_social

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: EMOTIONS ARE CONTAGIOUS! SO IF YOU DON'T LEAVE YOU'LL INFECT EVERYONE WITH YOUR MENTAL ILLNESS! 

b: You'll create a deadly outbreak of SAD LUMP SYNDROME

`bb({eyes:"suspect", body:"normal", mouth:"normal"})`

b: We need to get out of here and quarantine ourselves forever in a small room with Netflix and food delivery!

```
_.a2_second_danger = 'netflix';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "a quarantine";
```

(#act2c)

# act2b_louder_perv

`bb({eyes:"suspect", body:"two_up", mouth:"normal"})`

b: DON'T BE A CREEP. IT'S AGAINST THE LAW!

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: Creep Law, Section 74.5: (1) Any Person who checks out (a) those muscular shoulders (b) that bubble booty (2) shall be hereby known as

`bb({eyes:"shock", body:"two_up", mouth:"normal"})`

b: "A BIG DISGUSTING TRASH PERVERT"

```
_.a2_second_danger = 'law';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "the law";
```

(#act2c)

# act2b_louder_meaning

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: Actually, even if you find a noble purpose in life, you can *still* mess everything up!

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: Alfred Nobel wanted world peace and for cultures to understand each other. So he decided to make travel easier.

`bb({eyes:"normal_r"})`

b: So he needed a way to cheaply create train tunnels. So he invented a new material called "dynamite"...

`bb({body:"one_up", eyes:"normal"})`

b: which was used in World War I to KILL MILLIONS OF PEOPLE

`bb({body:"two_up", eyes:"shock"})`

b: IT'S THE BUTTERFLY EFFECT, HUMAN! HOW MANY PEOPLE ARE YOU ACCIDENTALLY KILLING RIGHT NOW

```
_.a2_second_danger = 'butterfly';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "World War I";
```

(#act2c)

# act2b_different_social

`_.a2_first_choice = "different"`

`bb({eyes:"normal_r", body:"point", mouth:"normal"})`

b: Actually, you know what's worse than no-one liking you? *Everyone* liking you.

`bb({body:"one_up", eyes:"suspect", mouth:"normal"})`

b: That is, becoming one of *these* pleasure-chasing party animals.

`bb({body:"normal", mouth:"small"})`

b: A shallow life with shallow friends who only know the shallow you!

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: Human, we need to run away from these pleasure-zombies before they turn us into one of them!

```
_.a2_second_danger = 'zombies';
_.a2_attack_2 = "alone";
_.a2_hoodie_callback = "zombies";
```

(#act2c)

# act2b_different_moral

`_.a2_first_choice = "different"`

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: People are dying in famines and genocides *right now* and we're just partying!

`bb({body:"point", eyes:"closed", mouth:"small"})`

b: A wise person once said, "the only thing necessary for the triumph of evil is for good folks to do nothing."

`bb({body:"two_up", eyes:"shock", mouth:"normal"})`

b: WE'RE DOING NOTHING.

`bb({mouth:"small"})`

b: BY PARTYING, WE'RE HELPING *HITLER*.

```
_.a2_second_danger = 'hitler';
_.a2_attack_2 = "bad";
_.a2_hoodie_callback = "Hitler";
```

(#act2c)

# act2b_ignore

`_.a2_first_choice = "ignore"`

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: 你觉得你把一氧化碳警报器的电池拆了就安全了吗？

`bb({eyes:"suspect_r"})`

b: 不会！你连异常的气味都闻不到！你只会觉得犯困然后你就会--

`bb({body:"scream_c_1"})`

b: **死！！！！！！**

```
_.a2_second_danger = 'ignore';
_.a2_attack_2 = "harm";
_.a2_hoodie_callback = "carbon monoxide";
```

(#act2c)

# act2c

```
hong({body:"ignore_sweat"});
bb({eyes:"normal", mouth:"normal", body:"normal", MOUTH_LOCK:true});
```

b: …

`bb({eyes:"happy", mouth:"smile", body:"chest"})`

b: 哦谢天谢地，你应该是能听见我了。

`bb({eyes:"closed", body:"point"})`

b: **接下来我会提醒你注意……**

{{if _.a2_first_choice=="louder"}}
[*还有更多*类似的危机！](#act2c_louder)
{{/if}}

{{if _.a2_first_choice!="louder"}}
[类似的危险*还有很多*！](#act2c_louder)
{{/if}}

{{if _.a2_first_danger=="social"}}
[*另一种不同的*社交危险](#act2c_different_social)
{{/if}}

{{if _.a2_first_danger=="perv" || _.a2_first_danger=="meaning"}}
[*另一种不同的*道德危险](#act2c_different_moral)
{{/if}}

[你喝那杯东西之前检查过了吗？](#act2c_punch)

#act2c_louder

{{if _.a2_second_danger=="netflix"}}
(#act2c_louder_netflix)
{{/if}}

{{if _.a2_second_danger=="law"}}
(#act2c_louder_law)
{{/if}}

{{if _.a2_second_danger=="butterfly"}}
(#act2c_louder_butterfly)
{{/if}}

{{if _.a2_second_danger=="zombies"}}
(#act2c_louder_zombies)
{{/if}}

{{if _.a2_second_danger=="hitler"}}
(#act2c_louder_hitler)
{{/if}}

{{if _.a2_second_danger=="ignore"}}
(#act2c_louder_ignore)
{{/if}}

# act2c_louder_netflix

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: Actually, Netflix & food delivery isn't quarantined enough! We'd still infect the delivery person!

`bb({body:"one_up", mouth:"small"})`

b: We need to move to the Canadian Yukon territories, and have our food delivered by drone!

`bb({body:"two_up", mouth:"normal"})`

b: And then they'd have to sterilize the drone to rid it of our SAD LUMP GERMS

`_.a2_attack_3 = "alone";`

`_.a2_hoodie_callback = "a quarantine";`

(#act2d)

# act2c_louder_law

`bb({eyes:"judge", body:"judge_1", mouth:"normal"})`

(...201)

```
bb({body:"judge_2"}, 0);
sfx("gravel");
```

(...168)

`bb({body:"judge_1"}, 0)`

(...168)

`bb({body:"judge_2"}, 0)`

(...168)

`bb({body:"judge_1"}, 0)`

(...501)

b: The BIG DISGUSTING TRASH PERVERT shall be sentenced to 72 hours in one of those medieval public-humiliation devices

b: unless they're secretly *into* that sort of thing

`bb({body:"scream_a_1"})`

b: because they're a BIG DISGUSTING TRASH PERVERT

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "the law";`

(#act2d)

# act2c_louder_butterfly

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: BUTTERFLY EFFECT! You're using a non-biodegradable plastic cup?

`bb({body:"two_up", mouth:"normal", eyes:"shock"})`

b: BAM, A LANDFILL LEAKS POISON AND KILLS A KID

`bb({body:"normal", mouth:"small", eyes:"suspect"})`

b: You're sweating and your heart's pounding?

`bb({body:"scream_a_1"})`

b: BAM, YOU BANKRUPT OUR HEALTHCARE SYSTEM AND MILLIONS DIE

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "the butterfly effect";`

(#act2d)

# act2c_louder_zombies

`bb({body:"normal", mouth:"small", eyes:"angry"})`

b: These pleasure-zombies will stumble towards you mumbling,

`bb({body:"normal", mouth:"normal", eyes:"shock"})`

b: LIIIIIKES. LIIIIIIIIIIKES.

`bb({body:"scream_a_1"})`

b: Then they'll BITE YOU and turn you into a BRAINLESS BRO and/or THOUGHTLESS THOT!

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "zombies";`

(#act2d)

# act2c_louder_hitler

`bb({body:"scream_a_1"})`

b: THE NAZIS ARE GOOSE-STEPPING BACK ON THE STREETS RIGHT NOW

`bb({body:"one_up", mouth:"smile", eyes:"happy"})`

b: Saying, *good thing those 'good folks' slacked off with stuff like 'relaxing' and 'self-care'!*

`bb({body:"point", mouth:"smile", eyes:"happy_r"})`

b: *Now our plans can go fourth, reich on schedule!*

`_.a2_attack_3 = "bad";`

`_.a2_hoodie_callback = "Hitler";`

(#act2d)

# act2c_louder_ignore

`bb({body:"normal", mouth:"normal", eyes:"normal_r"})`

b: 就好比说，我们现在所在的这个地方*到底有没有*一氧化碳报警器？

`bb({body:"two_up", mouth:"small", eyes:"normal"})`

b: 万一我们***现在就在***呼吸毒气怎么办？

`bb({body:"scream_a_1"})`

b: **我们甚至都没法遇见死亡将至！我们马上就会永远离开我们的世界！永远永远永--**

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "carbon monoxide";`

(#act2d)

# act2c_different_social

`bb({body:"normal", mouth:"normal", eyes:"sad"})`

b: What if we're just *fundamentally incapable* of ever being loved, or loving another?

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: What if something irreversibly broke inside of us a long time ago? Or never existed in us in the first place?

`bb({body:"scream_a_1"})`

b: AHH WE'RE BROKEN! SO BROKEN SO BROKEN SO BROKE--

`_.a2_attack_3 = "alone";`

(#act2d)

# act2c_different_moral

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: What if we're just *fundamentally rotten?*

`bb({body:"one_up", eyes:"sad"})`

b: Others have an inner drive to do goodness, but we only do "good" out of guilt or shame, if at all.

`bb({body:"normal", mouth:"small", eyes:"sad_r"})`

b: What if it's in our nature to hurt others? What if we can't be anything *other* than a burden to those close to us?

`bb({body:"scream_a_1"})`

b: AHH WE'RE BROKEN! SO BROKEN SO BROKEN SO BROKE--

`_.a2_attack_3 = "bad";`

(#act2d)

# act2c_punch

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: I'm not being irrational. People *do* drug punch bowls. That is an actual thing that actually happens.

`bb({eyes:"suspect"})`

b: Human, does your head hurt? Are your limbs limp? I think we're dying.

`bb({body:"scream_a_1"})`

b: AHHH WE'RE DYING! WE'RE DYING WE'RE DYING WE'RE DYI--

`_.a2_attack_3 = "harm";`

`_.a2_hoodie_callback = "punch bowls";`

(#act2d)

# act2d

```
bb({body:"normal", mouth:"normal", eyes:"normal"});
hong({body:"attacked"});
attack("20p", _.a2_attack_1);
```

(...401)

```
hong({body:"attacked_2"});
attack("20p", _.a2_attack_2);
```

(...401)

```
hong({body:"attacked_3"});
attack("20p", _.a2_attack_3);
```

(...1001)

h: 我^操^!

h: F^ACK^ING F^ACK^-F^AKK^ITY *F^AAAAACK^*

`bb({body:"two_up", mouth:"smile", eyes:"happy"});`

b: 好诶！你终于听到我说什么了！

`bb({body:"normal", mouth:"small", eyes:"sad"})`

b: 所以你为什么之前无视我

`hong({body:"facepalm"})`

h: 你个 ^傻逼^, 傻到家了.

`hong({body:"facepalm_2"})`

h: 你知道美国土著有个说法吗？

h: “你的心里有两只狼，一只是希望，一只是绝望，哪只狼获胜呢？自然是你一直喂的那只狼。”

```
hong({body:"facepalm_3"});
bb({eyes:"normal"});
```

h: 所以我是在*饿死*你，你个^混蛋^！

`hong({body:"smile", mouth:"smile"})`

h: 不管了，我要开始自我暗示鼓励自己了。

h: *我有人爱。我是个好人。我很聪明。我很好看。我是有价值的。*

`bb({eyes:"suspect"});`

[你太自恋了我的宝贝](#act2d_narcissist)

[*没有证据*表明自我暗示有用](#act2d_disproven)

[得了吧你喝个心灵鸡汤还得找个土著厨子](#act2d_racist)

# act2d_disproven

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: In fact, they actually *backfire* for people with low self-esteem! 

`bb({body:"one_up", mouth:"small", eyes:"normal"})`

b: It was a well-designed study – randomized controlled trial, experimenter was blinded as to who was in which group.

`bb({body:"two_up", mouth:"small", eyes:"normal_r"})`

b: Results: if you already had low self-esteem, being asked to repeat affirmations makes you feel *worse* than if you'd said nothing at all!

`bb({body:"point", mouth:"normal", eyes:"closed"})`

b: Wood 2009, Psychological Science. Look it up on Google Scholar, human,

`bb({body:"scream_b_1"})`

b: THEN STOP SPREADING UNSCIENTIFIC FAKE NEWS

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_narcissist

`bb({body:"normal", mouth:"normal", eyes:"normal"})`

b: You *need* to humbly see your own flaws in order to grow as a person!

`bb({body:"two_up", eyes:"suspect"})`

b: You can't spray air freshener over a moldy room! Covering up your flaws makes you worse in the long run.

`bb({body:"chest", mouth:"smile", eyes:"closed"})`

b: Thankfully, I, as your loyal guard-wolf, can alert you to your flaws. And right now, it's-

`bb({body:"scream_b_1"})`

b: EVERYTHING. EVERYTHING IS WRONG

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2d_racist

`bb({body:"normal", mouth:"normal", eyes:"suspect"})`

b: 美国土著是*实际存在*的人，不是让你化妆品广告更*高大上*的什么*国际友人*。

`bb({eyes:"suspect_r"})`

b: 你正在把独立的个体和复杂的文化符号化为鸡汤的作料！这是友善的种族歧视！

`bb({body:"scream_b_1"})`

b: **别把外国人看扁了你这斜眼看人的家伙！**

```
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2e)

# act2e

h: ^*你个傻逼*^.

`hong({body:"yell", mouth:"yell"})`

h: 跟你讲，你真是*毫不讲理*。

h: 人们都知道情绪是不可理喻的！尤其是恐惧！

`hong({body:"facepalm_2"})`

h: 你就是进化不完全的遗留，就好比我的阑尾或是智齿！

`hong({body:"yell", mouth:"yell"})`

h: ^操^,其实狼的那个比喻整个都很蠢！你其实就是我脑子里的一堆化学物质！

`hong({body:"cross", mouth:"cross"})`

h: 我何必要听你这种毫无价值不可理喻甚至说根本不存在的^狗逼^在这一直^叨叨^。

`bb({eyes:"sad", MOUTH_LOCK:true})`

b: …

[诶，人类，你这话很伤人啊](#act2e_hurtful)

[我是一种感受，感受是客观存在的。](#act2e_valid)

[人类，其实*你也是*一堆化学物质](#act2e_rational)

# act2e_hurtful

`bb({body:"chest"})`

b: I'm *part* of you, you know. When you say that, you're hurting *yourself*.

`bb({body:"scream_a_1"})`

b: Why are you hitting yourself, human? STOP HITTING YOURSELF.

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2e_rational

`bb({body:"normal", mouth:"normal", eyes:"normal_r"});`

b: 你最底层的动力是多巴胺，最欢喜的愉悦是血清素。

`bb({body:"one_up"});`

b: 你的记忆是神经的突出，你的理智是会出错的电信号。

`bb({eyes:"normal", body:"normal"});`

b: 所以如果我*是一堆化合物*就意味着我*不可理喻*…那么这就是说*你自己*就不可理喻！

`bb({body:"two_up", eyes:"shock"});`

b: 那么如果我们两个*都*不可理喻，那去讨论如何实现满足快乐完全就是*无稽之谈*。

`bb({body:"scream_a_1"})`

b: 啊啊啊我们整个都坏掉了！坏的透透-

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "bad");
```

(...2500)

(#act2f)

# act2e_valid

`bb({body:"normal", mouth:"normal", eyes:"suspect"});`

b: Hang on... "they" say that feelings are valid, that you should always accept your emotions.

`bb({eyes:"suspect_r"});`

b: But "they" also say emotions are irrational, that emotions are not to be trusted.

`bb({eyes:"angry"});`

b: Oh my gosh, "they" have been lying to us this whole time!

`bb({body:"scream_a_1"})`

b: "THEY" FEED US CONTRADICTIONS TO MAKE US DEPENDENT ON THE SELF-HELP INDUSTRIAL COMPLEX

```
music(null);
hong({body:"attacked"});
bb({body:"normal", mouth:"normal", eyes:"normal"});
attack("10p", "harm");
```

(...2500)

(#act2f)

# act2f

`hong({body:"defeated", MOUTH_LOCK:true});`

h: ……

h: 我讨厌这个，我真的非常*讨厌*这个。

h: 我不能安抚你，我不能忽略你，我还没法打你。

`bb({eyes:"suspect"});`

h: 不管我做什么，我似乎都无法摆脱—

`bb({body:"cry_1"});`

b: 应该是你本来就*不应该*摆脱我！

`bb({body:"cry_2"});`

b: 你知道*我*是怎么想的吗？人类？

`bb({body:"cry_4", mouth:"cry", eyes:"cry"})`

b: 我正在尽我最大的努力成为你的警犬，但是你一直把我看作是“大灰狼”！

b: 所以我才*努力*为你警示危险！*各种*危险！*各样*的危险！

`bb({eyes:"cry_2"})`

b: 但是我不管多么努力去保护你，你*始终*把我当成你的敌人。

`bb({body:"cry_5"});`

b: 我到底做错了什么？！

`bb({body:"cry_2"});`

b: 我*知道*我做的不好，但是*确实*在试着做了！人类！

`bb({body:"cry_3"});`

b: …我真的*努力*了。

`bb({body:"cry_6", mouth:"right", eyes:"cry_r_1"});`

b: 你可以不听我的警告，也可以不同意我的观点，甚至都不必*友善*以待。

`bb({eyes:"cry_r_2"});`

b: 我只是……我只想要你能对我有点耐心。

`bb({eyes:"cry_r_3"});`

b: 我只是想要你能坐下来陪我一会，而不是扭头就—

```
bb({eyes:"cry_r_4"});
hong({body:"listen"});
```

r: 嘿。

```
hong({body:"look"});
Game.clearText();
publish("act2-in-2");
publish("hp_hide");
music('party1', {volume:0.4, fade:2});
```

(...2000)

```
publish("act2",["party_hunter",2]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: 你好像是在和自己吵架？小家伙？

```
publish("act2",["party_hunter",3]);
publish("act2",["party_hong",13]);
```

h2: 有那么明显吗？

```
publish("act2",["party_hunter",4]);
publish("act2",["party_hong",14]);
```

r: 你刚刚…呃…好像在对着你的帽子抱怨{{_.a2_hoodie_callback}}什么的来着。

```
publish("act2",["party_hunter",13]);
publish("act2",["party_hong",15]);
sfx("rustle", {volume:0.6});
setTimeout(function(){
	publish("act2",["party_hong",16]);
	sfx("concrete_step3", {volume:0.6});
},401);
setTimeout(function(){
	publish("act2",["party_hong",17]);
	sfx("concrete_step4", {volume:0.6});
},801);
```

h2: 啊天我现在有点乱。

```
publish("act2",["party_hunter",7]);
publish("act2",["party_hong",18]);
sfx("squeak");
```

r: 没事，你这情况很常见的，焦虑现在到处都是。

```
publish("act2",["party_hunter",5]);
publish("act2",["party_hong",19]);
```

{{if _.act1_ending=="fight"}}
r: 靠，就在昨天，我听说有个人在学校奔溃了，还砸了手机！
{{/if}}

{{if _.act1_ending=="flight"}}
r: 靠，就在昨天，我听说有个人在外面一边哭一边还怂的像个刺猬一样，缩成了球！
{{/if}}

```
publish("act2",["party_hunter",2]);
```

r: 听着，我知道把负能量囤在脑子里是什么感觉。

```
publish("act2",["party_hunter",8]);
```

r: 我们都知道，所以我们才每周都搞这么一次聚会，这样就可以忘记那些不愉快，忘记负能量。

```
publish("act2",["party_hunter",9]);
publish("act2",["party_hong",20]);
```

h2: 但是我的焦虑…

```
publish("act2",["party_hunter",2]);
publish("act2",["party_hong",21]);
```

r: 不用担心，我之前跟你一样，但是后来我发现了一个方法可以让那些不好的声音闭嘴。

```
publish("act2",["party_hunter",3]);
Game.clearText();
music(null, {fade:1});
```

(...2001)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",22]);
sfx("rustle");
```

(...2501)

```
publish("act2",["party_hunter",10]);
publish("act2",["party_hong",23]);
sfx("rustle2");
```

(...1001)

```
publish("act2",["party_hunter",11]);
```

r: 这是我独门秘方，劲道应该……比市面上的货色足得多。

```
publish("act2",["party_hunter",12]);
publish("act2",["party_hong",24]);
```

r: 记得喝光哦, ^小 婊 砸^!

```
hong({body:"hold"});
bb({body:"normal", mouth:"small", eyes:"wat"});
Game.clearText();
Game.WORDS_HEIGHT_BOTTOM = -1;
publish("act2-out-3");
publish("hp_show");
```

(...3500)

[我的天](#act2g_1) `Game.OVERRIDE_CHOICE_LINE=true`

[这不是个好的解决办法](#act2g_2) `Game.OVERRIDE_CHOICE_LINE=true`

[别喝陌生人的饮料](#act2g_3) `Game.OVERRIDE_CHOICE_LINE=true`

# act2g_1

b: 我—

(#act2g)

# act2g_2

b: 这—

(#act2g)

# act2g_3

b: 别—

(#act2g)

# act2g

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"forward", mouth:"forward"});
bb({body:"frazzled", mouth:"frazzled", eyes:"frazzled"});
```

h: 嗯，这个调味层次很足。

h: 丰满的“心如止水”的口味结合“放空心绪”的余韵！

b: 这不是个好东西，人类，*绝对*不是。

[这*就是*上瘾的第一步](#act2h_opt1) `Game.OVERRIDE_CHOICE_LINE=true`

[我*就*知道这里乱七八糟的](#act2h_opt3) `Game.OVERRIDE_CHOICE_LINE=true`

[而且，他们可能在里面下药了](#act2h_opt2) `Game.OVERRIDE_CHOICE_LINE=true`


# act2h_opt1

b: 这*就是*—

(#act2h)

# act2h_opt2

b: 而且，他们可—

(#act2h)

# act2h_opt3

b: 我*就*知道这—

(#act2h)

# act2h

```
hong({body:"drink"});
bb({body:"attacked"});
attackBB("40p", "harm");
```

(...2000)

```
hong({body:"back", mouth:"back"});
bb({body:"panicked", mouth:"panicked", eyes:"panicked"});
```

h: 好喝的很，*而且*比治疗便宜多了！

b: **求求你停一停**

h: 呵呵呵！

h: 可是*你*又能拿我怎样？^混蛋^！

b: 我很抱歉，人类

b: 这种情况下我不得不使用我的**特别攻击**了

```
bb({body:"special_a"});
music('battle', {volume:0.5});
```

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_harm"`

[](#act2h_attack) `_.SPECIAL_ATTACK="harm"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_alone"`

[](#act2h_attack) `_.SPECIAL_ATTACK="alone"; Game.OVERRIDE_CHOICE_LINE=true`

`Game.OVERRIDE_CHOICE_SPEAKER = "fear_bad"`

[](#act2h_attack) `_.SPECIAL_ATTACK="bad"; Game.OVERRIDE_CHOICE_LINE=true`

# act2h_attack

```
bb({body:"special_b_1"});
hong({body:"forward", mouth:"forward"});
sfx("charging");
```

h: 这^你妈^是什么？

h: 是不是又要开始无尽的垃圾话—

```
bb({body:"special_c"});
sfx("hadouken");
```

(...901)

(#act2i)

# act2i

```
publish("hide_tabs");
publish("show_special_attack");
Game.FORCE_CANT_SKIP = true;
music(null);
stopAllSounds();
```

(...5000)

```
publish("show_tabs");
hong({ body:"final", mouth:"final" });
bb({ body:"normal", mouth:"normal", eyes:"sad" });
attack("100p", _.SPECIAL_ATTACK);
Game.FORCE_CANT_SKIP = false;
setTimeout(function(){
	publish("remove_special_attack");
},30);
```

(...2500)

h: **^我勒个操^那是什么鬼!**

b: 对不起。我需要告诉你后果。

{{if _.SPECIAL_ATTACK=="harm"}}
h: 我都*看*见我的尸体了！我都*感觉到*死去是什么感受了！
{{/if}}

{{if _.SPECIAL_ATTACK=="alone"}}
h: I COULD *SEE* EVERYONE'S LOOK OF DISGUST. I COULD *HEAR* ALL THE THINGS THEY SAID.
{{/if}}

{{if _.SPECIAL_ATTACK=="bad"}}
h: I COULD *HEAR* THE CRUNCHING OF RIBS. I COULD *TASTE* THE BLOOD IN THE AIR.
{{/if}}

b: 对不起，人类。

n: *FINISH THEM*

[{使用攻击:一拳入魂}](#act2j_fight) `Game.OVERRIDE_CHOICE_LINE=true`

[{使用攻击:走为上计}](#act2j_flight) `Game.OVERRIDE_CHOICE_LINE=true`

# act2j_fight

`bb({ eyes:"angry" });`

b: 那个精神病正在利用你

b: 他们在败坏你，让你和他们一样乱！

`bb({ body:"yell_angry_1" });`

b: 给那个家伙来一拳！打到他眼冒金星！

`bb({ body:"final_1" });`

b: 揍他揍他揍他揍他揍他揍他揍他揍--

`_.a2_ending = "fight";`

(#act2k)

# act2j_flight

b: I *knew* all these partygoers were deeply messed up. They all dull their pain with horrible things!

`bb({ body:"yell_1" });`

b: And they're tricking you into doing the same thing! They're corrupting you! We need to get out!

`bb({ body:"final_1" });`

b: GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OUT GET OU--

`_.a2_ending = "flight";`

(#act2k)

# act2k

```
Game.clearText();
publish("act2-in-4");
publish("hp_hide");
music('party1', {volume:0.6, fade:1.5});
```

(...2001)

```
publish("act2",["party_hong",26]);
sfx("slide");
```

(...1001)

```
publish("act2",["party_hunter",14]);
Game.WORDS_HEIGHT_BOTTOM = 230;
```

r: 你没事吧？

`publish("act2",["party_hunter",13]);`

{{if _.a2_ending=="fight"}}
(#act2k_fight)
{{/if}}

{{if _.a2_ending=="flight"}}
(#act2k_flight)
{{/if}}

# act2k_fight

```
Game.clearText();
publish("act2",["party_hunter",21]);
publish("act2",["party_hong",33]);
music(null);
sfx("hit");
```

(...1000)

```
sfx("record_scratch");
publish("act2",["party_hunter",22]);
publish("act2",["party_hong",34]);
publish("act2",["dee",6]);
publish("act2",["dum",6]);
```

r: 你…你………


```
publish("act2",["party_hunter",23]);
publish("act2",["party_hong",35]);
publish("act2",["dee",5]);
publish("act2",["dum",5]);
music('party1', {volume:0.6, fade:6});
```

r: 有够*骚*的

r: 你这样我喜欢，下周聚会还要来啊，小可爱。

```
publish("act2",["party_hunter",19]);
publish("act2",["party_hong",36]);
```

h2: 再见, ciao, adios, au revoir

r: 你今天可能负能量暂时赢了，不过记得下次再来，我会给你准备更猛的哦！

h2: sayōnara, auf wiedersehen,bye,shalom

r: 我们俩一起，可能能让负能量知道谁才是管事的！

(#act2k_end)

# act2k_flight

`publish("act2",["party_hong",36]);`

h2: ok sorry i have to run

`publish("act2",["party_hunter",16]);`

r: ^Damn^ it. The animal won today, huh?

`publish("act2",["party_hunter",15]);`

h2: no no, just, uh, gotta run a marathon. gotta go fast.

`publish("act2",["party_hunter",19]);`

r: Come to my party next weekend, cutie. I'll mix something even stronger for you.

h2: ok thanks gonna run run run run run

r: You and me, kid, we'll show that beast who's boss!

(#act2k_end)

# act2k_end

```
Game.clearText();
publish("act2-out-5");
publish("act2-outro", ["end1"]);
music("hum", {fade:2, volume:0.6});
Game.WORDS_HEIGHT_BOTTOM = -1;
```

(...2500)

```
publish("act2", ["act2_end",2]);
sfx("whoosh");
```

(...1000)

b: 人类！你还好吗！

```
publish("act2", ["act2_end","next"]);
```

b: （吸气）刚刚好*险*，我们本来可以—

```
Game.clearText();
publish("act2", ["act2_end","next"]);
music(null);
sfx("squeak");
```

(...1500)

```
publish("act2", ["act2_end","next"]);
sfx("hit");
```

(...1000)

h: 下周我还时会去聚会。

h: 下次我们再见面，就不是谁打败谁了…

h: 我^他妈的^要杀了你。

```
Game.clearText();
publish("act2", ["act2_end","next"]);
sfx("concrete_step1");
````

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step2", {volume:0.8});
```

(...901)

```
publish("act2", ["act2_end","next"]);
sfx("concrete_step3", {volume:0.5});
```

(...901)

`sfx("concrete_step4", {volume:0.25});`

(...3000)

`_.INTERMISSION_STAGE = 2;`

(#intermission)