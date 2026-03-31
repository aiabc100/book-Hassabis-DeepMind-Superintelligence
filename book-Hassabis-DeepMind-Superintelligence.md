Also by Sebastian Mallaby


			After Apartheid

			The World’s Banker

			More Money Than God

			The Man Who Knew

			The Power Law


ing to Demis and being 


		 			Penguin Press

			An imprint of Penguin Random House LLC

			1745 Broadway, New York, NY 10019

			penguinrandomhouse.com

			Copyright © 2026 by Sebastian Mallaby

			Penguin Random House values and supports copyright. Copyright fuels creativity, encourages diverse voices, promotes free speech, and creates a vibrant culture. Thank you for buying an authorized edition of this book and for complying with copyright laws by not reproducing, scanning, or distributing any part of it in any form without permission. You are supporting writers and allowing Penguin Random House to continue to publish books for every reader. Please note that no part of this book may be used or reproduced in any manner for the purpose of training artificial intelligence technologies or systems.

			PP colophon is a registered trademark of Penguin Random House LLC.

			Cover design: Chris Allen

			Cover photograph: Carlotta Cardana

			Designed by Nerylsa Dijol, adapted for ebook by Cora Wigen

			Library of Congress Catalog Control Number: 2025045167

			Hardcover ISBN 9780593831847

			Ebook ISBN 9780593831854

			International Edition ISBN 9798217062744

			The authorized representative in the EU for product safety and compliance is Penguin Random House Ireland, Morrison Chambers, 32 Nassau Street, Dublin D02 YH68, Ireland, https://eu-contact.penguin.ie.

			The mission of the Council on Foreign Relations is to inform U.S. engagement with the world. Founded in 1921, CFR is a nonpartisan, independent national membership organization, think tank, educator, and publisher, including of Foreign Affairs. It generates policy-relevant ideas and analysis, convenes experts and policymakers, and promotes informed public discussion—all to have impact on the most consequential issues facing the United States and the world.

			The Council on Foreign Relations takes no institutional positions on policy issues and has no affiliation with the U.S. government. All views expressed in its publications and on its website are the sole responsibility of the author or authors.

			prhid_prh_7.4a_155581268_c0_r0





Contents


			Dedication

			Epigraph

			Introduction: The Sweetness

			01 Destiny

			02 “Deep Philosophical Questions”

			03 The Jedi

			04 The Gang of Three

			05 Founding DeepMind

			06 Atari

			07 Thiel Trouble

			08 Get Google

			09 Intuition

			10 Out of Eden

			11 P0 Plus Plus

			12 The Agent and the Transformer

			13 On Language and Nature

			14 Project Mario

			15 Fermat for Biology

			16 The Power and the Glory

			17 RaceGPT

			18 “We’re Cooked”

			19 Step by Step

			20 Comeback, and Beyond

			Epilogue: Turing’s Champion


Acknowledgments

			Notes

			Index

			About the Author



	_155581268_





To Felix, Maya, Milo, and Molly.

			And especially to Zanny.

			Love you, all of you, always.





What we are creating now is a monster whose influence is going to change history, provided there is any history left, yet it would be impossible not to see it through, not only for military reasons, but it would also be unethical from the point of view of the scientists not to do what they know is feasible, no matter what terrible consequences it may have. And this is only the beginning! The energy source which is now being made available will make scientists the most hated and the most wanted citizens of any country.

			—John von Neumann, while working on the atom bomb, 1945





Introduction




				The Sweetness

			 			This book is about intelligence. On the one hand, it’s a portrait of a remarkable human, a chess prodigy, a Nobel laureate, a polymathic thinker. On the other hand, it tells the story of his quest to build remarkable machines: systems that are intuitive, creative, and even original. At some point in the not-so-distant future, artificial intelligence will beat human intelligence at almost every mental task, and to say this marks a watershed would be a parody of understatement. Artificial intelligence heralds a transformation more profound than anything since Homo sapiens acquired the capacity for abstract thought, some seventy thousand years ago.

			I first met Demis Hassabis, the remarkable human, in the mid-2010s: an elfin figure with dark hair falling forward toward angular eyebrows, his face framed by standard-issue spectacles. Already a star technologist and the possessor of a comfortable fortune, he seemed much younger than his thirty-eight years. Smooth-skinned, slight of build, he came across as a phenomenally articulate youth rather than a staid adult. He would appear onstage at conferences dressed in a boyish crewneck and loose slacks. “AI is the technology of making machines smart,” he began one typical performance in 2015, stating his premise in the plainest form possible.

			What he said next was what got your attention. Hassabis embarked on an explanation of his life’s purpose: the pursuit of machine superintelligence. Growing up in North London, he had decided that two fields of inquiry stood out: physics and neuroscience. Physics explains the external world, from the behavior of particles to the functioning of the universe. Neuroscience explains the internal world—the neurons and synapses and electrical pulses that constitute intelligence. Later, at some point in his twenties, Hassabis had concluded that neuroscience was the more important of the two: The internal trumped the external. Intelligence is fundamental; it is the root of all else. It is the mechanism through which humans perceive reality.

			Still speaking plainly, as though he were saying that he’d wash the dishes after lunch, Hassabis invoked the eighteenth-century philosopher Immanuel Kant.

			“The mind interprets the world,” Kant had declared.

			“It’s the mind that creates our reality around us,” Hassabis now said, by way of emphasis.

			The question was how to comprehend intelligence. Here Hassabis pivoted to a second intellectual giant, the Nobel laureate Richard Feynman. “What I cannot build, I do not understand,” Feynman famously remarked, and Hassabis clicked on a controller in his hand to display a slide of the great physicist. Following Feynman’s dictum, in order to grasp human intelligence, scientists would have to build an artificial analog: a machine that mimicked human thinking. AI’s practical or profit-making potential was a secondary concern. The youthful figure on the stage wanted “to understand our own minds better.”[1]

			Hassabis delivered this sort of talk repeatedly at tech gatherings in the 2010s, and the faces in the auditorium would seem both rapt and mystified. The boyish philosopher onstage was clearly not a stereotypical entrepreneur peddling a hot app that promised untold riches. He was offering a cocktail of computer science and neuroscience, with the grand prize being enlightenment. Later, I learned that when Hassabis had founded his company, DeepMind, back in 2010, fellow scientists had rolled their eyes, believing the construction of humanlike AI to be impossible. Almost every potential investor had turned Hassabis away, observing that enlightenment is not a business model. But Hassabis had nonetheless scraped together funding and persuaded gifted researchers to join him, all on the strength of his exhilarating vision. It didn’t feel quite adequate to describe that vision in conventional language. The term artificial intelligence was too bloodless. Hassabis wanted nothing less than to build an omniscient machine: a machine through which we could better understand ourselves; a machine that would unravel the infinite mysteries of physics; a machine that would occupy, effectively, that position in the cosmos that religious believers once ascribed to an all-powerful divinity.



* * *



			• • •

			I had long been fascinated by the predicament of scientists in society. In one sense, scientists are just seekers of truth, a seemingly uncontroversial mission. In another sense, they are the destroyers of all things: our jobs, our ways of thinking, potentially even our existence. Artificial intelligence stands accused of threatening humans in all these ways, and Hassabis understands the full spectrum of doom scenarios. Many leading creators of AI, including a few at DeepMind, fear that circuits-and-silicon intelligence may eradicate the flesh-and-blood variety: that the advent of AI could be the last event in human history, as the extreme pessimists put it. Even if these nightmares of annihilation are speculative, risks ranging from deep fakes to terrifying weapons are certain to materialize, as is economic, political, and philosophic turmoil. And so Hassabis has had to grapple with the central quandary of his life’s work. Given the evident dangers from AI, why would a scientist want to create such a technology?

			There are two familiar answers—one generous, one troubling. The generous theory holds that humanity will contain the risks inherent in AI while reaping vast benefits from its upside: breakthroughs in medicine and science, inventions to contain climate change, not to mention advances that counteract the very dangers stressed by AI pessimists. We may fear, for example, that future children will never learn to write—if AI chatbots generate text on demand, why bother? We may further fear that, if children cannot write, they will not be capable of thought—and if humans cannot think, what are they? But set against these reasonable anxieties, there is the rosier vision: that chatbots will excel as infinitely patient tutors, creating bespoke quizzes, grading students’ answers instantly.

			This optimistic vision of AI discovery has history in its corner. Past innovations from gunpowder to nuclear fission have made wars more terrifying and accidents more lethal. A few particular inventions—cigarettes, or social media that destroy attention spans—are probably net negative. But the general effect of technological change has been to amplify our experience and extend our lifespans, and the very act of creating new technologies is intrinsic to being human. As the techno-optimist Reid Hoffman puts it, it makes no sense that “we still tend to view technology as a dehumanizing force instead of the thing that makes us, us.”[2] To Descartes’s dictum, “I think, therefore I am,” perhaps we should add: I imagine, therefore I am; I hypothesize, therefore I am; I invent, therefore I am. The urge to invent lies deep within us.

			Such is the generous explanation of AI inventors’ motivations. The second, troubling interpretation is best captured by a story about Geoffrey Hinton, the delightful academic father of AI and the recipient of a Nobel Prize in 2024—the same year that Hassabis was honored. Ever since I came upon Hinton’s tale, it has haunted me.

			Hinton is well known for his prickly sense of principle. As a young professor he left the United States for Canada to avoid depending on research grants from the US military. In 2023, when AI systems began to exhibit human fluency, he quit a lucrative position at Google, partly to speak publicly about the dangers of powerful machine intelligence. But the haunting story I remember reveals another side of the great man. It illustrates the predicament of the inventor who sees an opportunity to usher something tremendous into the world. The thrill of discovery—the Icarus instinct—is simply overwhelming.

			One day in the spring of 2015, Hinton delivered a speech at the Royal Society in London. After the presentation, a journalist spotted him talking to the Oxford philosopher Nick Bostrom.[3] Hinton was telling Bostrom that he did not expect machines to be properly intelligent for a long time. But once the technology began to work, it would be impossible to prevent people from abusing it.

			“I am in the camp that is hopeless,” Hinton informed Bostrom.

			“In that you think it will not be a cause for good?” Bostrom inquired.

			“I think political systems will use it to terrorize people,” Hinton answered.

			“Then why are you doing the research?” Bostrom asked.

			“I could give you the usual arguments,” Hinton replied. “But the truth is that the prospect of discovery is too sweet.”[4]

			Hinton was echoing J. Robert Oppenheimer, the creator of the atom bomb. “When you see something that is technically sweet, you go ahead and do it,” Oppenheimer said. “You argue about what to do about it only after you have had your technical success.”

			Later, Hinton regretted his line. “It was very apt. That’s why I wish I hadn’t used it,” he told me.[5]

			Discovery is too sweet. Is this what drives scientists to pursue technology that threatens to upend society? Reid Hoffman may be correct that the act of invention is intrinsic to being human. But this raises the possibility that humans will carry on inventing until they eventually go too far. Must the rest of us resign ourselves to being hostages?



* * *



			• • •

			In the years since that conference talk in 2015, Hassabis and his company have racked up astonishing achievements. In 2016, DeepMind—a small British research group now owned by Google—solved a grand challenge in computer science, creating a system that surpassed the intuitive brilliance of the world’s best players of the ancient board game of Go. In 2020, DeepMind solved a second grand challenge, in biochemistry, stitching together thirty-two algorithms to divine the shape of nearly all the proteins in nature: This was the breakthrough for which Hassabis shared the Nobel Prize in Chemistry. In 2025, by now facing stiff competition from follower labs in Silicon Valley and China, DeepMind was among the front-runners in the race to build intelligent chatbots, and it led the field in AI technologies for video generation, drug discovery, and mathematics. Back when he had founded DeepMind, Hassabis had promised to build a Manhattan Project for AI, and that was exactly what he now delivered. It was as though the spirit of Los Alamos had been transported to a neighborhood of trendy restaurants and boutiques clustered around a nineteenth-century train station in London.

			In late 2022—coincidentally, right when DeepMind’s fiercest rival, OpenAI, set off an artificial intelligence frenzy by releasing its conversational companion, ChatGPT—I pitched Hassabis on the idea of a book about DeepMind. It would be a start-up adventure story, an exploration of AI, but also an investigation of the motivations and passions that drive him. Up to a point, Hassabis stands for a type: The missionary entrepreneur and out-of-the-box scientist who, through brilliance and extraordinary drive, emerges as the right person for a particular moment—in this case, the moment when hardware and software and data have aligned to make superhuman intelligence possible. But at a deeper level, Hassabis provides a window on life’s eternal enigmas. What drives people to act? What is their purpose?

			Believing that societies will never trust inventors of transformational technologies unless they understand what makes them tick, Hassabis agreed to the deep access I needed. Over the next three years, we talked for a total of about thirty hours, and I interviewed more than a hundred members of his entourage, inside and outside DeepMind. During this process, Hassabis revealed himself as an extraordinary consumer and teller of stories—his outlook is shaped by novels and movies, and his gifts as a leader are bound up with his genius for narrating his experiences. The many surprises that followed form the basis for this book. But one in particular has stuck with me.

			On a late summer day in 2023, I met Hassabis at a café in a North London park, close to the neighborhood where he had spent his childhood. We sat at a weather-beaten wooden table beside a yellowing brick wall, surrounded by humdrum lunchtime conversations. To my left and behind me, two middle-aged women chatted about a friend’s medical diagnosis; in front, a salesman with a file of papers discussed business on his smartphone. The weather was extraordinarily hot for London, and the sun beat down on Hassabis, who, now sporting fashion-forward glasses and a shaved scalp, had nothing to protect him. But he didn’t seem to mind. The heat, the moss-patterned bricks, the quotidian chatter at the neighboring tables: Both of us were soon oblivious. For there, seated on a paint-peeled chair, Hassabis was in full flow. Ideas and allusions poured out of him in a torrent. I thanked Steve Jobs for the device on the table that captured every word of it.

			The true reason to build artificial intelligence, Hassabis was now saying, went beyond Kant and Feynman. The goal was to draw closer to what might be called God—to the intelligence that may presumably have designed everything around us.

			“I am first and foremost a scientist,” Hassabis began. “My goal is to understand nature.

			“But doing science is, sort of, like reading the mind of God. Understanding the deep mystery of the universe is my religion, kind of.

			“We humans, we have these faculties. The world is understandable. But why should it be that way? I think there is a reason.

			“Computers are just bits of sand and copper,” Hassabis continued, now sounding more urgent. “Why should these combine to do anything? I mean, it’s absurd! The electrons move around and then that creates an AI system that can defeat a Go master? Why should that be possible?

			“This table, Sebastian!” Hassabis rapped his palm on it for emphasis. “Why should it be solid?

			“This is beyond evolutionary coincidence. We can build electron microscopes and interrogate reality down to the most minute level. We can build systems that detect black holes colliding more than a billion years ago. I mean, what is this? What the hell is going on here?”

			There was a pause, but Hassabis was not yet finished.

			“I sit at my desk at two a.m., and I feel like reality is staring at me, screaming at me.

			“Literally, screaming at me. Trying to tell me something if I could just listen hard enough.

			“That’s how I feel every day. So, you can see why I’m trying to build AI. I’ve felt that since I was very young: that there’s a deep, deep mystery about what’s going on here.

			“You can frame it how you want. You can call this God’s design, or you can say it’s just nature. I’m open-minded about the description, and I don’t know what the answers will turn out to be. But at the moment we don’t really know what time is, or gravity is, or any of these things. So there is a mystery waiting to be solved, and it encompasses just about everything.

			“I would like to understand before I croak. I would like to understand, and then I’m perfectly fine to shuffle off my mortal coil.”



* * *



			• • •

			As I finish this book, in 2026, a new kind of intelligence is being willed into the world by a remarkably small number of people. Each of them is driven by a particular mix of curiosity and hubris, vanity and avarice, idealism and craving, and the sobering reality is that, for better or worse, the quality of their characters will affect society. The good news is that Demis Hassabis, who blazed the trail followed by rivals, is decent and public-spirited and wants the best for humanity. He has ego, to be sure. He is fearsomely competitive; his sense of destiny, as the developer of AI, borders on the messianic. But his goal is scientific enlightenment, not money or power. The spiritual language in which he sometimes couches his mission underscores how seriously he takes it.

			Some readers, sick of the arrogance of tech overlords, may find this verdict difficult to swallow. In the years since the 2008 financial crisis, which humbled the lions of Wall Street, Silicon Valley has emerged as the new epicenter of commercial power, stoking the hubris and hypocrisy of some of its leaders. The overweening self-righteousness of the most voluble tycoons has discredited the idea that messianic innovators can possibly be well-intentioned. But there is no necessary connection between making a fortune in the Valley and egomania unbound, and nor is it fair to paint the technology sector as a bastion of anarcho-libertarianism. For every Donald Trump supporter in the tech industry, there are multiple progressives.[6] For every avaricious egotist, there is also a Bill Gates, who has dedicated much of his Microsoft fortune to improving the life expectancy of the world’s poorest. Moreover, Hassabis himself is a figure apart. Not by coincidence, he has chosen to remain in London, far from the Valley’s hype and commotion. In his dreamier moments, he talks of retiring to a university and spending time with his first loves—physics and neuroscience and philosophy.

			For now, Hassabis is not sheltering in an ivory tower—far from it. He is at the roiling epicenter of a capitalist fight over AI: a fight that is playing out at a time when global and national regulators seem unlikely to contain the fallout. Indeed, it is hard to imagine a more explosive coincidence of a transformative scientific shock, unstable geopolitical competition, and seething political chaos in the United States, the country ordinarily most likely to lead an effort to safeguard a Promethean technology. In these volatile circumstances, Hassabis’s struggle to stay true to his personal values is a defining story of our times. He wants to do good, but can he be good? He understands the dangers of AI, but what can he do to contain them? J. Robert Oppenheimer created the atom bomb, but he could not control its use. Perhaps this is the privilege and fate of all history’s great scientists.





Chapter 1




				Destiny

			 			Partway through his doctoral research in neuroscience—when he had already been a chess master, a video game designer, an amateur theoretical physicist, an entrepreneur, a computer scientist, and five-time world champion at the international Mind Sports Olympiad—Demis Hassabis discovered a work of science fiction that made sense of who he really was. The book, called Ender’s Game, by Orson Scott Card, tells the story of a diminutive boy genius who is taken from his family and sent off to a space station. There, at an intergalactic battle school, Ender is manipulated by adults, bullied by classmates, and put through extreme mental testing, all to discover whether he can shoulder responsibility for the survival of the human race. By dint of grit and talent, Ender rises to the challenge. At the climax of the novel, he outwits an army of alien invaders, destroying their armada and saving planet Earth, though the question of whether he committed genocide in the process hangs over the outcome.

			Hassabis was around thirty years old when he discovered Ender, and he was so taken with the story that he asked his wife to read it. She told him she felt sorry for the central character—a boy deprived of childhood and harnessed to a mission chosen for him by adults. But Hassabis identified powerfully with Ender. He, too, had been a diminutive boy genius, socially isolated by his own prodigious talent. He, too, had undergone extreme mental testing, and was consumed by a desire to make his mark on the universe; one of his ambitions was to surpass his scientific heroes, Newton and Einstein, and “understand the fabric of reality itself.” The fable of Ender—a gifted, bullied boy who saves all humanity—tapped into Hassabis’s deepest preoccupations, even if (especially if!) the savior had been required to pay an immense personal price.

			Some fifteen years later, now in his midforties, Hassabis sat across from me in a London restaurant, reflecting on the power of this tale. We had not stumbled on the subject by accident. Hassabis had suggested that I read the novel in advance of our first long conversation; this was a subject he wanted to tackle. If I was to get to know him, I would have to understand his science-fiction alter ego: to see the capacity for endurance, the ability to suffer and still soldier on. Like Ender, Hassabis had dedicated every fiber of his being to the accomplishment of a mission, which was why he worked night shifts from ten in the evening until around four in the morning in addition to his normal office hours. Like Ender, Hassabis felt a burden of responsibility. “If you are trying to solve humanity’s problems and understand the nature of reality, you don’t have any time to waste,” he said.

			I described this conversation to Shane Legg, one of the two cofounders who teamed up with Hassabis to form the company DeepMind. Back in 2010, when the pair of postdocs at University College London had begun fusing computer science and neuroscience, had Legg realized that he was hitching his career to someone so possessed?

			At first, Legg answered warily. “I don’t know if I was teaming up with a real-life Ender,” he began.

			But then he continued, weighing his words deliberately. “Demis has an extraordinary level of determination. Unlike pretty much anybody. Astonishing, incredible determination. That’s his most defining characteristic. Just unbelievable determination.”

			“What do you mean?”

			“He works, sleeps, eats, breathes the mission, twenty-four hours a day. To a degree that I just haven’t seen with other people.”

			“No hobbies?”

			“Football. Big fan of Liverpool. But other than that, it’s the mission.”

			“And that was evident even back when you met him, more than a decade ago?”

			“Always,” Legg answered.

			His face flickered, as though a memory had stirred somewhere just below the skin.

			“Demis tells a story about his father saying that whether you win or lose, the really important thing is that you try your best. And Demis says he took that very literally. As in, absolutely try the absolute, absolute, absolute best you can possibly do, pretty much to the point of breaking yourself.

			“That’s how he is, twenty-four seven.”

			I nodded, kept eye contact, and hoped Legg would continue.

			“I don’t think his father meant his comment in quite that literal sense,” Legg reflected. “Like, ‘try your best’ wasn’t supposed to mean ‘try literally to the point of destroying yourself, go absolutely, completely 100 percent.’ But that’s how Demis understood it.

			“There is no 50 percent mode in Demis. There is not even a 99 percent mode in Demis. There is only 100 percent.”[1]



* * *



			• • •

			Demis Hassabis was born in modest circumstances in Finchley, North London, in July 1976. He was the eldest child of a Chinese Singaporean mother and a Greek Cypriot father, which made him an exemplary product of one of the world’s great melting pots. His mother had grown up in poverty, spending part of her childhood as an orphan on the streets of Singapore, eventually finding shelter with a benevolent relative and moving to London to study nursing.[2] When Demis was small, she worked as a sales assistant at the John Lewis department store and took part-time jobs as a cleaner. Demis’s father had been the first from his family to attend university, but he was too much of a bohemian free spirit to abide office work. He was an aspiring singer-songwriter and sold toys out of the back of a beaten-up red Volkswagen van.

			In contrast with his family circumstances, the young Demis’s talents were not at all modest. When he was four, he climbed up on a chair to watch his father play chess against his uncle. Within a few weeks, he had mastered the game well enough to defeat adults. At five, he began competing in tournaments, sitting on a telephone book on top of two stacked chairs so that he could get his head above the table, and frequently beating older kids. A primary school teacher noted his unusual mix of levity and seriousness. Demis was “sparkling.” He was also relentlessly competitive.[3]

			When Demis was six, he qualified to compete in the British Under 14 championship, winning two of his matches before falling asleep at the table when a game stretched into the evening, way beyond his bedtime. After watching the two victories, Leonard Barden, the beloved patriarch of English chess, approached Demis’s father. Barden had played internationally during the 1950s and 1960s, later becoming a well-known chess columnist and television commentator. Now he sought out Demis’s father to deliver the kind of message that parents love and dread.

			“Your son is the best six-year-old I’ve ever seen,” Barden said.

			“What are you going to do when someone tells you that?” Hassabis reflected. “My parents were fairly normal people living fairly normal lives. And a renowned expert is telling you this.”

			Demis’s father responded to Barden’s message as though instruction had been handed down from God. For the next half dozen years, weekend after weekend, he bundled his young prodigy into the family’s red VW van and drove him off to tournaments in shabby, far-flung church halls, leaving his wife with the two younger children and her various jobs. Sometimes the father-son duo spent the night in sleeping bags laid out over the engine at the back of the VW; other times they found a cheap hostel and shared a bunk bed. If Demis won the tournament, the prize money would cover the hostel fees, but his mother still fretted about the cost of the travel. “She grew up in absolute poverty,” Hassabis said later. “I imagine my parents had a lot of arguments about money, because we didn’t have much.”

			Demis’s chess progress continued. At nine, he was the captain of England’s Under 11 team. At thirteen, he reached the rank of chess master and was the second-strongest competitor in his age group, worldwide.[4] But the pressures kept on mounting. Chess consumed every weekend and every day of school vacation, squeezing out the easy recreation of normal childhood. Long hours of training were punctuated by acute moments of match play, when everything came down to nerves and stamina and unplanned flashes of insight. The competition was vicious: There were wooden boards under the tables to prevent players from kicking each other.[5] Like Ender, Demis could barely imagine what “just living” might mean. He had never tried it out.

			Demis’s father was taking progressively more time away from his work and his music to keep driving him to tournaments, which only redoubled the pressure on his son. When the boy had a bad game, the father would erupt.

			“There was one time, I was a rook up and then lost horribly, and my dad went mental,” Hassabis remembered.[6]

			“He was screaming, ‘How could you have done this? This is unbelievable. How could you have just thrown this away?’

			“It was just awful. We were out in some hostel, and he was going on about this, screaming. And this used to be a fairly regular occurrence with my dad.

			“So I said to him, ‘This is ridiculous. I obviously tried my best. I’m not intentionally losing.’ And that was that. I wasn’t going to take it anymore. That was the last time I remember him screaming at me, whereas he used to all the time before.

			“I think I’m quite an empathetic person,” Hassabis continued. “I can take the other person’s position, and I know that this was done through love. If you met my dad now, you would be like, ‘This can’t be the same person,’ because he’s so laid-back and chilled out.

			“But this is just how he was around chess. It was probably to do with, I don’t know, my mum pressurizing him. Like, why doesn’t he have a normal job? And maybe I wouldn’t become a champion and this was all a waste of time.”

			During one of our long conversations, I asked about the story that Shane Legg had told me: the one about Demis’s father telling him that, win or lose, what mattered was to do his best.

			“I think my dad meant it in a comforting way,” Hassabis stipulated.

			“But then, he didn’t really mean it that way, or why would he have been so angry when I lost a match?

			“Anyway,” he continued, flashing a grin of rueful self-awareness, “the slightly warped way I took that was, how do you know you’ve done your best?

			“The only way I could know is basically if I pushed myself to the point just before death. Because that is literally when you have done your best. If you die—by die, I mean burn out or something—then you’ve slightly overdone it.

			“It’s like running a marathon. You have to basically fall over the line. And then ideally you should be hospitalized, but not dead. That’s when you can say you’ve done your best. But if you’ve got any energy left, you’re still standing, maybe you could have tried harder?

			“That’s how I took it. I must have been about nine or ten.”



* * *



			• • •

			One of Hassabis’s earliest childhood memories involves winning the London Under 8 chess championship and going up to get the trophy. In the film reel of his mind, he walks up to a figure holding a silver cup, eagerly receives the prize, and turns triumphantly to face the audience. Then his gaze fixes on the runner-up, a future grandmaster and close friend, who sobs uncontrollably as his father berates him.[7]

			The thin line between exultation and breakdown was a constant feature of the tournament circuit. “A lot of my chess friends got destroyed,” Hassabis recalled later. “They ended up drinking, or getting burned out.” At the age of twelve, Hassabis experienced his own moment of existential torment. Paradoxically, it freed him.

			Hassabis was doing battle at an international competition near Liechtenstein. The way he remembers the episode, he was pitted against an experienced German master, a man old enough to be his father. The German was a chain-smoker, and the match stretched on for almost ten hours, entering an unusual endgame. Hassabis still had his queen; the German had a rook, bishop, and knight. Time ticked by as the pieces circled the board, and the tournament hall gradually emptied as kings were cornered and toppled on the other tables around them. Then, eventually, the equilibrium broke. The German trapped Hassabis’s king. Checkmate looked inevitable.

			Shocked and physically exhausted, Hassabis capitulated.

			Immediately, his opponent leapt to his feet. “Why have you resigned?” Hassabis remembers him asking.

			With a flourish, the victor showed the boy the move he should have made. If Hassabis had sacrificed his queen, the match would have ended in a stalemate.

			The German’s friends crowded around and joined in the jeering. For the rest of the day, Hassabis felt sick to his stomach. But the next morning he experienced an epiphany. That tournament hall near Liechtenstein had been packed with brilliant brains, dueling over black and white squares until stamina was drained to nothing. Surely that immense collective mental effort should have been harnessed to some higher cause—science, say, or medicine? “I thought we were wasting our minds,” Hassabis said later.[8]

			For nearly all his conscious life, Hassabis had assumed he would grow up to be a chess professional. His father earnestly believed that, too: No less an oracle than Leonard Barden, the father of English chess, had foretold his son’s destiny. But now Hassabis resolved that there must be something more: a mission, a purpose.

			What followed were some happy years when Hassabis continued to play chess but refused to be possessed by it. He remained ferociously competitive, of course. Dharshan Kumaran, the friend who was in tears after losing the London Under 8 championship, remembers Demis as a teenager, gesturing at the stronger players seated at a tournament’s top boards, and declaring with determination, “We’re better than all those people!”[9] But to the surprise of many in the chess fraternity, Hassabis also began to compete in other mind games: bridge and backgammon, Diplomacy and draughts, as well as the Japanese chess variant shogi. His versatility was even more striking than his prowess at chess: After university, he went on to win a record string of gold medals at the five-game international Mind Sports Olympiad. “What Demis did with shogi was really impressive,” a chess veteran reflected. “Another complicated game and he got to the top of the English rankings,” said another.[10] But Hassabis could scarcely imagine why he wouldn’t sample other challenges. The world offered so many enthralling ways to test his mental acumen.

			The more Hassabis multiplied his hobbies and interests, the more he collected friends around him. In his younger years, he had cut a solitary figure: With Asian looks, a foreign name, and an outlandish intelligence, he had not exactly gelled with the other kids at the local government school that he attended—“I was like this alien,” he remembered. Around the age of ten, he had skipped classes entirely for a year to focus on chess, keeping up with the curriculum by reading textbooks in his bedroom. When he was fourteen, he dropped out again, teaching himself two years of the school syllabus at double speed so that he could take the national GCSE exams early. It seems likely that this social isolation contributed to his manic drive. Lacking the scaffolding of friendship, his route to affirmation was to achieve something extraordinary.[11]

			But as Hassabis matured in his teen years, he began to flourish socially. The switch flipped when he was fifteen and his school arranged a special class for a handful of elite math pupils. For the first time, Hassabis found himself surrounded by similarly curious, driven kids, and he befriended all of them. The students came from a variety of backgrounds: a Nigerian whose father was a diplomat; a boy of Indian descent; two Jewish kids; and one Cypriot-Singaporean-Bohemian chess prodigy. All were united in their enthusiasm for the class. Not only were they learning math, they were discovering that joyful, abstract mental play could be a way of bonding with your peers, not a route to isolation.



* * *



			• • •

			After his defeat in Liechtenstein, Hassabis spent more time on his greatest interest outside chess: computing. At eight, he had used his prize money from the junior circuit to buy his first machine, a ZX Spectrum 48K. “I loved it from the moment I unwrapped the box,” he said later.[12] At twelve, he bought a much more powerful device, a Commodore Amiga 500. His dad took him to Foyles, a labyrinthine bookshop in the heart of London that boasted thirty miles of weathered shelves, and Hassabis discovered a slim volume called The Chess Computer Handbook, by the Scottish international master David Levy. The marriage of computing and chess united Hassabis’s two worlds. He bought Levy’s handbook and read it in one sitting.

			Levy introduced Hassabis to the themes that would animate his lifelong quest to build artificial intelligence. To show how chess programming worked, Levy invoked the information theorist Claude Shannon, who would become another of Hassabis’s intellectual heroes. In 1950, Shannon had published a paper, “Programming a Computer for Playing Chess,” arguing that, while chess programs were of no practical importance, mastery of complex games might “act as a wedge in attacking other problems of a similar nature and of greater significance.” These similar but more significant problems might be as various as translation, military strategy, and the generation of music. Chess programming was merely the first step toward what Shannon termed “a modern general-purpose computer.”[13]

			When Shannon wrote those words, no such general-purpose computer was in sight. “I started writing a program for a machine that did not yet exist, using a set of computer instructions that I dreamed up,” he confessed cheerfully.[14] But, blessed with a rare gift for theorizing the future, Shannon proceeded to describe the difference between a “numerical computer” and a “general” one. A numerical computer was basically a calculator: It followed rigid programs and tackled questions that had clear right-or-wrong answers. In contrast, a general computer could make sense of subjects that demanded more than mere logic: It could assess a chess position, or grasp linguistic nuance. To grapple with this sort of material, the program would have to apply “general principles, something of the nature of judgment, and considerable trial and error, rather than a strict, unalterable computing process.” A general computer would not be merely deductive. It would consider examples, try things out, and make sense of the world around it.

			Levy’s book, written a third of a century later, surveyed the relationship between computers and chess as it stood in the early 1980s. By this point, chess programs were starting to exhibit the features that Shannon had imagined, and their strengths and weaknesses shed light on the nature of intelligence. Silicon transmits electric signals much faster than the human brain, so computers could rapidly calculate several moves ahead; alacrity enabled them to defeat top humans at speed chess.[15] However, computers had yet to develop anything resembling intuition, the flashes of brilliance that decided longer matches. Levy predicted that chess programs would never overcome this lack of flair, but that steadily expanding processing power would lead them to victory over human grandmasters by the end of the century. Sure enough, IBM’s Deep Blue chess system defeated the reigning human grandmaster, Garry Kasparov, in 1997.[16] But Deep Blue triumphed in a grinding, brute-force fashion, vindicating Levy’s view that machines would struggle to match human ingenuity.

			The young Hassabis stored up these ideas, and games later became the test bed for his own quest for AI, much as Shannon had envisaged. But what excited Hassabis about Levy’s handbook were its more practical sections: the chapters that took the reader through the components of a chess program, explaining three building blocks that would be central to Hassabis’s later achievements.

			The first challenge, Levy explained, was for the computer to “see” the chessboard. This required turning visual information—the shape, color, and position of the pieces—into a set of quantities. A number was duly assigned to each piece: 1 to a pawn, 2 to a knight, and so on. To distinguish white from black, white pieces were assigned positive numbers, black pieces negative ones. In this way, the spatial information on the board was made intelligible to a computer.

			Next, the machine had to be taught to evaluate board positions. Human players do this based on factors such as the value of the pieces they have left, the number of possible moves these pieces can make, and their ability to attack the board’s center. Consciously or otherwise, humans weight these various factors differently. A chess program, as Levy explained it, could do the same. For example, if the value of the remaining pieces was twice as important as their freedom of maneuver, the computer would double the score for material before adding it to the score for mobility.

			Once the program knew both the state of the board and the value of a position, it had to devise a strategy. It did this by working through all possible moves, then considering how its opponent might counter each one, and how it would counter the counter. The further this “tree search” extended, the more branches it would sprout. Pretty soon this exponential branching overwhelmed the computer’s processing power, Levy explained, so programmers had devised a way of narrowing the search. Just as humans save time by not analyzing moves that are obviously bad, so chess systems “pruned” branches that led to low-value positions.[17] Once the computer had gamed out the promising branches as far as its processing power allowed, it played whichever move led to the highest-value outcome.

			Firing up his Commodore Amiga, the twelve-year-old Hassabis set about applying Levy’s principles. Pretty soon, he found that his computer choked on the complexity of even a pruned tree, so he built a program to play a simpler game, Othello. This was no small task. Hassabis had to adapt Levy’s instructions to a new domain: The position representation, evaluation function, and the tree search all had to be designed differently. But Hassabis got the program working, and, drawing on a musical facility inherited from his father, he added in a soundtrack. Then he whipped up some graphics to make the game look cool. Changing the color of the Othello counters from black and white to red and blue, he christened his invention Fire and Water.

			The Fire and Water program proved intelligent enough to beat Demis’s little brother, George. Demis was delighted. Admittedly, George was all of five years old at the time, but Hassabis still chalked this up as a famous achievement. Thanks not least to Demis’s tutoring, George was pretty good at games. “It was amazing that I’d made something that could beat him,” Hassabis remarked, with satisfaction.



* * *



			• • •

			Three years later, when Hassabis was almost fifteen, he visited a local store to browse computer magazines. There were racks of publications, and Hassabis followed a practiced routine: He would read until the staff told him to buy something or get off the premises. On this occasion, Hassabis found an ad in a magazine published for fans of the Commodore Amiga; it was an invitation to compete for a job at the Bullfrog video game production studio. The contestants only had to do one thing: dream up the wackiest, most entertaining spin on the classic video game Space Invaders.[18]

			Hassabis knew Bullfrog as one of the top game studios in Europe. Its founder, Peter Molyneux, was a big-eared, big-talking, lanky creative who did not just design games; he invented entire new genres of games, notably the “god games” in which players controlled the fates of hordes of digital characters. Unbeknownst to Hassabis, Molyneux also had a wild side.[19] When kids came to his office to work as game testers, he would sometimes amuse himself by shooting at them with a BB gun.[20] When a Bullfrog designer complained about the disappointing size of his bonus, Molyneux responded by hurling a heavy object at him. The projectile missed, shattering the company fish tank, which was stocked with piranhas. The following Monday, a new Bullfrog recruit climbed the stairs to the company’s attic studio and found dead fish all over the floor, along with smashed glass and wet patches. Other than that, the place was empty. Molyneux and his team had jetted off to America, leaving the mess behind them.[21]

			Hassabis loved Molyneux’s god games, and he resolved to compete in Bullfrog’s contest. Fittingly, his variant on Space Invaders involved chess: The player’s avatar was positioned in the middle of a chess-like grid, and chess-piece enemies advanced on it from either side in chess-like formation. A few months later, another announcement in the Amiga magazine listed Chess Invaders as a runner-up.[22] It was not quite enough to win Hassabis a job. But he called up the company and landed an invitation to visit.

			Hassabis boarded a commuter train from London and set off for the exurban town of Guildford. By now Bullfrog had done well enough to vacate its dingy attic office, and the studio was housed in a shiny building in a research park. “They had nice carpet and people that cleaned the windows without being asked,” Molyneux’s cofounder recalled, though the Bullfroggers rendered the premises a bit less nice by skateboarding down the corridors and vomiting in the urinals.[23] To Hassabis, however, windows and carpets were beside the point: He was leaving the orbit of his parents and arriving in the promised land; the creative magic of a famous video game savant was about to be revealed to him. “Can you imagine how excited I was?” Hassabis exclaimed later. “I was literally skipping off the train, jumping on the bus to the research park. It was a beautiful sunny day and I was coming over the brow of a hill. I thought I had just gone to heaven.”

			Hassabis’s special brand of sparkling seriousness made for an excellent first impression. “He was a lovely kid and so phenomenally bright,” one Bullfrogger remembers thinking.[24] Hassabis was soon invited to stick around at the studio for a week, and was assigned a desk next to Molyneux. His quick intellect brought out the boss’s good side: The savant handed down instruction and the pupil soaked it up; the two got along famously. Hassabis was also fascinated by the other Bullfrog employees: technically talented, self-made young men, many of whom had dropped out of high school, being too idiosyncratically gifted or plain wild to sit meekly in a classroom. Several of the illustrators who worked on the games had learned their artistry by spraying trains with graffiti and dodging the cops on the way home. Hassabis was particularly taken by a brilliant self-taught coder named Sean. “He had an edge to him. He could have been in a gang. I mean, he probably was in a gang,” Hassabis remembered.

			The following winter, Hassabis won admission to the University of Cambridge, where he would study computer science. The college authorities ruled that although he was academically ready, at sixteen he was too young to enroll, so he should find something else to occupy himself for the next year or so. This suited Hassabis just fine: He would graduate from high school a year early and go back to Bullfrog until Cambridge was ready for him. Molyneux was embarking on a brand-new, genre-busting adventure, a game called Theme Park.

			Not everyone at Bullfrog felt confident about Theme Park’s prospects. The idea was that players would build virtual carnival rides and burger stands and ice cream stalls, managing digital entertainers, mechanics, and security guards. “I just didn’t get it,” one graphic artist recalled. “I left Bullfrog to make a decent game. What a dickhead!”[25] But Hassabis was happy to embrace Molyneux’s vision. Together with a handful of other young employees, he moved into Molyneux’s higgledy-piggledy country house, a mysterious old rectory with hidden doors and secret passages and plenty of gear for gaming.[26] There, the coding commune worked both day and night, gathering periodically in the kitchen for impromptu spaghetti and discussion. The line between working and philosophizing blurred, Hassabis recalled. “We were brainstorming these big ideas. There was this thrill of unbridled creation.”

			In the early 1990s, video games were built on software platforms known as “finite-state machines.” Characters toggled crudely between a limited number of states—a monster might run, attack, or eat, for example. But Molyneux insisted that the finite-state architecture should be pushed to the max, so that the digital figures in Theme Park would exhibit a far greater range of behaviors. They would crave food and drink, which might be salty or sweet. They would want fast rides and dizzying ones. They should experience nausea and nerves, happiness and sadness.

			Hassabis rose to Molyneux’s challenge, packing Theme Park full of imaginative details. If the player put extra salt on the French fries, the visitors would feel thirsty and soft-drink sales would rocket. If the player made the roller coasters too scary, the digital riders would vomit; not scary enough, and thrill-seeking customers would grow disappointed. Periodically, Molyneux would drive Hassabis from the old rectory over to the studio, where the precocious apprentice would demonstrate his latest wonders, the boss would issue instructions, and the two would disappear again. Naturally, this raised some hackles. “Peter has a new pet!” an older programmer muttered. “Who the fuck is this kid?” another grumbled.[27] But nobody could question the excellence of the kid’s output.



* * *



			• • •

			Sometime in this period, Molyneux gave Hassabis a copy of Gödel, Escher, Bach, a fire hose of a book that has inspired a remarkable number of future AI scientists.[28] This tome, which won the Pulitzer Prize, delivers a torrent of ideas on “fugues and canons, logic and truth, geometry, recursion, syntactic structures, the nature of meaning, colonies, concepts and mental representations, translation, computers and their languages, DNA, proteins, the genetic code, artificial intelligence, creativity, consciousness and free will,” as the author, Douglas R. Hofstadter, proclaimed, without evident modesty. Seventeen years old and voraciously curious, Hassabis was deeply fascinated by all of the above. But the passages that influenced him most were the ones on intelligence and consciousness.

			As a chess prodigy, Hassabis had long been curious about the workings of his own mind: How did his brain formulate moves? Why did it make mistakes? And what was behind this phenomenon called thinking? Hofstadter attacked these questions as a physicist, insisting that human intelligence and computer intelligence are virtually indistinguishable. The human brain, as he explained it, is a purely physical object. It is composed of biological material that obeys the laws that govern the rest of the universe, computers included. Moreover, human brains, like computer brains, work on trickles of electricity; when they form an opinion or conceive a plan, they are responding to the chemical equivalent of ones and zeroes. The idea that the gooey mass inside the skull contained some ineffable, unprogrammable something—consciousness? spirit?—was nothing more than biochauvinism.

			This proposition would upset many readers, Hofstadter conceded. Human beings are seized by a strange sensation: the feeling of possessing a unique “I-ness,” which in turn is at the root of something called “free will.” Readers needed to reckon with the reality that, notwithstanding such feelings, human intelligence and machine intelligence resembled one another closely. “Only if one keeps on bashing up against this disturbing fact can one slowly begin to develop a feel for the way out of the mystery of consciousness: that the key is not the stuff out of which brains are made, but the patterns that can come to exist inside the stuff of a brain,” Hofstadter wrote.[29] For a youth who was already fascinated by programming intelligence, this line of argument was thrilling. If the patterns were what mattered—those crackles of electricity, ultimately governed by genetic code—then similar patterns could be encoded into artificial brains. What the mind could do, computers should be able to do—one day.

			These propositions were all the more intoxicating given the setting. Hassabis was transforming his programming hobby into a well-remunerated art, proving his facility with the code whose potential Hofstadter was stressing. He was living away from his parents, surrounded by rebels who loved to dream about AI, under the watch of a mentor who encouraged these passions. “We were discussing AI all the time,” Hassabis recalled. “How it could help the games. What it would take to build it.”[30]

			Even as he plowed his way through Hofstadter’s dense work, Hassabis was inhaling science fiction. When he was younger, he had read Isaac Asimov’s Foundation series, and his imagination was fired by the main character, Hari Seldon, who prophesies the collapse of the Galactic Empire and plots to mitigate the fallout. “The only way for us to have that capability of predicting disasters, and then averting them, would be to have AI,” Hassabis said later. At Bullfrog, Hassabis ripped through the first books in Iain Banks’s Culture series, which described a post-scarcity, interstellar society dominated by intelligent artificial beings. In this world of Banks’s imagining, AI systems would generate economic abundance, and citizens would lack for nothing. Space travel would be as simple as hopping on a London bus, and people could choose among hundreds of planets to live on. What’s more, the intelligent machines that Banks envisaged would exist peacefully alongside humans; they would be too preoccupied with their own intrigues to pick a fight with mortals. It followed that artificial intelligence was not to be feared. To the contrary, it would enrich human experience.

			Halfway through the work on Theme Park, Hassabis accompanied Molyneux to an artificial intelligence conference in the United States. There they watched a professor from Carnegie Mellon University give a talk on lifelike computer agents. The professor showed a video with three bouncing blobs: The big one was labeled “Bear,” the medium-sized one was called “Dog,” and a small blob was “Mouse.” The blobs interacted in ways that, to state the matter generously, were only mildly intriguing. The bear defended the mouse. The dog chased the mouse. And so on. Such, apparently, was the state of the art in academic AI programming.

			After the lecture, Molyneux and Hassabis went up to the professor.

			“Do you want to see what we are working on?” they asked. They cracked open a laptop and produced a demo of Theme Park.

			“He fell off his chair,” Hassabis recalled.

			“He was like, ‘What is this? Who are you guys?’

			“And I showed him all the different properties that we were modeling, how happy the characters were feeling, how sad, how thirsty, how hungry, how much money did they have, who were their friends? All of that was simulated in this massively complicated theme-park world. And he couldn’t believe it.”[31]

			Taken together, Hassabis’s experiences at Bullfrog answered his big post-Liechtenstein question: His mission and purpose would be to build artificial intelligence. Molyneux and Gödel, Escher, Bach had planted the idea: Computers would soon do whatever the brain could do. Iain Banks had supplied a utopian vision of what AI’s realization could mean: boundless human flourishing. And the Carnegie Mellon professor had inadvertently established that Hassabis possessed the requisite talent: If he could impress an eminent scientist before even attending university, there was no limit to what he might accomplish in the future.

			“I decided then that I was going to dedicate my career to working on AI,” Hassabis recalls. “I already had the kernel of the idea for what eventually became DeepMind.”[32]

			It would take one more epiphany to clinch his destiny.





Chapter 2




				“Deep Philosophical Questions”

			 			In the fall of 1994, Hassabis quit Bullfrog to embark on his studies at Cambridge. Molyneux did everything to persuade him not to go: He wrote out a check for £500,000 to get him to work on Bullfrog’s next game, Dungeon Keeper. It was an astonishing sum to dangle in front of an eighteen-year-old, equivalent to about $1.7 million in today’s money.[1] But Hassabis refused to cash the check.

			Hassabis’s determination to attend Cambridge owed much to a film, Life Story. The movie celebrates the scientists James Watson and Francis Crick. They meet at the university, enjoy sunny strolls along the River Cam, and hurry along rain-drenched cobbled streets to the shelter of the ill-lit Eagle pub, where they speculate exuberantly about DNA and conspire to become famous. Ultimately, with the help of an X-ray image created by their rival, Rosalind Franklin, Watson and Crick discover the double-helix structure of DNA, winning the Nobel Prize for their achievement.

			The importance of this film to Hassabis, like the influence of Iain Banks’s Culture series, says much about how he came by his worldview. Dropping out of school for periods, and operating beyond the understanding of his parents, Hassabis’s ambitions were shaped by a magpie collection of encounters. “I’m quite indiscriminate about knowledge,” he said. “I’ll have any knowledge. Chess game, book, philosophy, I’ll drink it all in.” But the Life Story movie points to something else as well. Multiple forces had driven Hassabis down the path toward AI. But perhaps the strongest driver was the thrill of science: the prospect of discovering the truth behind the other truths.

			“What’s fun?” Watson asks Crick, early on in Life Story.

			“Oh, the big questions,” Crick responds. “What is man? What is life? How did we come to be the way that we are?”

			For a while after that fateful game in Liechtenstein, Hassabis had thought seriously about a career in theoretical physics. Here was a field that seemed to grapple with the biggest possible questions—the nature of the universe, the building blocks of reality. For a youth with vast ambition, the prospect of understanding everything was profoundly alluring, and physics held out the hope that you could rise above the clutter of quotidian facts to a higher plane of abstraction. From that loftier vantage point, physicists could explain reality in terms of phenomena unseen—atoms, gravity, geometry, time—and perhaps even discover an all-encompassing, unifying insight that knitted everything together. Every so often in the history of science, one giant theory displaces another: Copernicus announced that Earth was not the center of the universe; Einstein replaced Newtonian physics with general relativity. Perhaps humanity had arrived at another watershed in the progress of ideas—a moment when siloed understandings could be fused into a single theory.

			Thrilling though this prospect seemed, Hassabis was also practical. When he signed up for a game, he liked to feel that he could win, and physics seemed like a long shot. The way he saw things, all physicists since Einstein had ultimately come up short. They had failed to hit on a theory that explained all of reality.

			“Even Richard Feynman couldn’t do it,” Hassabis said, matter-of-factly. “He died without understanding everything. I realized that however good I was going to be, I was unlikely to surpass him.”

			Following this line of thought, Hassabis hit upon a strategy. He resolved to go after the infinite mysteries of physics with the help of artificial intelligence. Science had always advanced courtesy of new tools: Telescopes had allowed humans to peer into space; X-ray machines had made it possible to see into humans without invasive surgery. AI would be the ultimate lever: an extension not merely of vision but of the capacity for understanding.

			Arriving at Cambridge, Hassabis was on the lookout for scientific challenges to crack once AI became available. He imagined himself sitting in the Eagle pub, conspiring in the murky light and hatching Nobel-level adventures. But for those who expect geniuses to be one-track obsessives, he was something of a disappointment. In his first year as an undergraduate, he developed a taste for electronic music: After nights of raving with friends, he would flop down on his bed at dawn and put on Music for the Jilted Generation by the electronica band The Prodigy. In his second year at Cambridge, he took buddies for joyrides in his new car—a Porsche 911 Turbo. In a flourish of nineteen-year-old chutzpah, Hassabis had persuaded Molyneux to lend him the Porsche, saying that he needed it for his commute to the Bullfrog studio, where he had agreed to contribute as a consultant.[2] Sometime in this period, Hassabis fell in love with an Italian undergraduate who would become an academic bioscientist. They would later marry.

			Hassabis was the subject of much gossip. Students swapped stories about his chess exploits. They marveled that an undergraduate had been the cocreator of Theme Park, a game that had sold millions of copies. They rolled their eyes about his car—and envied it. But despite the legends that grew up around him, what struck friends most about Hassabis was his affability. “My first impression of him was, he’s a nice kid,” another computer science student recalled.[3] He radiated a conviction that you were going to get along, and the conviction was self-fulfilling.

			One day I asked Hassabis about this friendly approachability.

			“I’ve always tried to live that,” Hassabis told me. “It’s a very deep, personal philosophy.”

			“Where did it come from?” I asked.

			“Probably my mom,” Hassabis said. “The religious upbringing she gave me.

			“She’s Christian, very religious. That got her out of the hard situation in her childhood, when she was basically an orphan. When I was growing up, she was always helping poor or lonely people through her church.

			“I used to go to Sunday school, played my flute in the church band, prayed before I went to bed, helped with the charity work. My mom’s religion certainly stuck with me.

			“But I also think it’s just my personality. I want to help people and I feel very strongly that it’s just really bad to manipulate or control people.”

			I thought of Ender and wondered whether there might be another explanation for this humble affability. Hassabis was small and appeared young for his age: “I am regularly told that I look ten years old,” he confessed when he was in his early twenties.[4] This gave him a good reason to shy away from confrontation, from explicit efforts to exert control; when the bullies came after Ender, he hit back with magic force, but Hassabis was not a cartoon ninja. Hassabis could choose to avoid confrontation, moreover, because he had an alternative way to earn people’s respect: He could beat everyone at games, from chess to backgammon and even table football. In this sense, his gentle affability and his ferocious competitiveness were two sides of the same coin. On the one hand, Hassabis loved to yank and spin the table-football figurines in the college bar: It was an everyman hobby, telegraphing his approachability. On the other, he became so fixated on the game that he organized a college team and vanquished adversaries all over campus.

			“I was the best table-football player at Cambridge, pretty much,” Hassabis remembered, without irony or self-deprecation. “I could shoot with my left hand from the midfield with a lot of control, so I had something quite special.

			“You know, there’s a professional scene in the US, and even they don’t shoot like that.”

			Hassabis also started to play the ancient Chinese board game of Go: Here was something else that he could win at. Once a week, he would bicycle out to the home of a professor and take afternoon lessons, peering down at the restful symmetry of the grid, pondering how to position each stone in a way that captured territory and denied it to the adversary. Hassabis was so good at this test of spatial intelligence that the professor noted down some of his games, later including them in a handbook for Go students.

			As he made the most of Cambridge life, Hassabis remained a magpie. Whatever his fellow students were excited by, he was eager to wrap his mind around, too—and his enthusiasm was contagious. One time, between bouts of table football, a biologist acquaintance told him about the mysteries of protein shapes that, if only they could be accurately plotted, would unlock extraordinary medical breakthroughs. It was a passing conversation, so fleeting that it failed to register in the memory of the biologist friend, but Hassabis filed it away in the back of his extraordinary mind as a potential double-helix-type challenge.[5] A quarter of a century later, DeepMind unraveled the mystery of proteins, winning a Nobel Prize for revolutionizing the field of structural biology.[6]



* * *



			• • •

			Hassabis formed his strongest intellectual bond with a student named David Silver. They both stood out for being sunny and friendly, and even before their paths crossed at Cambridge, each was curious about the other. Silver had a boyhood memory of an intense young Hassabis competing at chess tournaments in his hometown of Ipswich: The visiting Londoner would defeat all the locals and make off with the prize money. For his part, Hassabis was keenly aware that Silver had the highest exam results of any computer science undergraduate at Cambridge.[7] When the two eventually met, mutual respect and overlapping interests made for a quick melding of minds. “We shared the same passions,” Silver recalled. “The big debates about AI, the deep philosophical questions about computer science. It was just really fun talking to him.”[8]

			Silver’s “deep philosophical questions” hearkened back to the founding fathers of computing. In 1956, a group of artificial intelligence pioneers had convened a summer workshop at Dartmouth College in New Hampshire. “An attempt will be made to find how to make machines use language, form abstractions and concepts, [and] solve the kinds of problems now reserved for humans,” the organizers announced boldly. The premise for this project was that every “feature of intelligence can in principle be so precisely described that a machine can be made to simulate it.” It was a presumption that reflected the midcentury faith in logic and reason. The 1950s enshrined the rational agent at the heart of economics, the efficient-market hypothesis at the heart of finance, and “scientific” managers at the heart of corporations. In this hopeful era, it was only natural for the Dartmouth group to believe that human intelligence was rational and deductive—and thus describable and programmable.

			For the next half century or so, the standard approach to building intelligent machines was known as symbolic artificial intelligence. Programmers chose symbols to represent concepts from the real world: digits, words, physical objects. They supplied the computer with information about these symbols, then added instructions on logical rules—the definitions of “and,” “or,” “not and,” and so on. If the computer was told that the first symbol was green and the second one was blue, it could accurately deduce that they were not both the same color. If it was told that humans are mortal, and that Socrates was human, then it could deduce that Socrates was mortal. The idea was to transform all real-world phenomena into quasi-mathematical syllogisms. If a is b, and c is a, then c is b, also.

			Hassabis had encountered this approach before: David Levy’s handbook, which showed how to turn chess positions into numerical statements, had been an example of symbolic programming. In 1984, the year Levy’s book appeared, symbolic AI reached its apogee with a project called Cyc, which aimed to create a system equipped with the majority of human commonsense knowledge. Cyc was taught rules as detailed as “You can’t be in two places at the same time,” and “When drinking a cup of coffee, you hold the open end up.”[9] But the truth, as philosophers had long recognized, was that the subtleties of human reason could not be captured in this way. For every rule, there are myriad exceptions. Knowledge cannot be decomposed into discrete axioms, nor is understanding achieved exclusively through logical deduction.

			Consider a basic facet of intelligence: the ability to arrange things into categories. What is the rule that explains to a computer that a butter knife and a carving knife belong in the same category, despite their different sizes and appearances? Ah, you may point out: Both objects serve to cut; they are united by function. But then how do you simultaneously explain to the AI system that a golden retriever and a dachshund should be grouped together: Do they share a “function”? Of course, the answer is that the big dog and the small dog belong to the same species, meaning that they can mate together and produce fertile offspring. But how can an AI model be instructed to know which categories are defined by appearance, which by function, and which by reproductive potential? The pioneers of symbolic artificial intelligence had no answers to such questions.[10]

			At Cambridge in the mid-1990s, Hassabis and Silver encountered a culture still wedded to the midcentury assumptions. They were taught “first order logic,” a system of rigidly unambiguous statements that was used in deductive programming. (The statement “All birds can fly” would be written “∀x(Bird(x)→CanFly(x)),” for example.) To the two undergraduates, the limits to this methodology were clear. Silver, like Hassabis, had read Gödel, Escher, Bach: The first name in the book’s title belonged to the mathematician Kurt Gödel, who had proved that, contrary to the Dartmouth pioneers’ presumption, no system of logical deduction could encompass all possible true statements. To Hassabis and Silver, Gödel’s “incompleteness theorem” merely confirmed what was intuitively obvious. After all, humans engage in deductive logic only a small fraction of the time. Mostly, they take in jumbled images, words, smells, and sensations; then they extract meaning from the noise—a process that logicians call induction and lay people might call pattern recognition.

			“The idea of using first order logic to understand language—it was obvious to me this was nonsense,” Hassabis remarked later. “We don’t speak in first order logic and yet we can understand each other.” If intelligent humans could comprehend one another’s messy sentences, it followed that intelligent machines should be able to make sense of imprecise, unstructured data. They should digest examples and derive general truths. They should be inductive as well as deductive.

			“We speak ungrammatically all the time,” Hassabis went on. “It doesn’t collapse our brains. We can converse. So first order logic is clearly not the whole story.”

			To the computer science establishment, however, induction seemed daunting. Deduction yields unambiguous truths. Induction yields generalizations that are not provably correct, and that may have to be revised in light of fresh information. After studying the morning routines of ten New Yorkers, for example, an observer might induce that all humans drink coffee. But observation of millions of people across multiple cultures would require this conclusion to be modified.

			Because learning from examples requires many examples, an inductive machine can succeed only by taking in as much data as possible. But then it will hit the limits of its computational power, requiring a strategy for deciding which parts of its training data to focus on. This gets to the challenge that defines AI: the challenge of teaching a machine to navigate copious data. The human mind relies on mental shortcuts to pull off this trick; but at the time when Hassabis and Silver were at Cambridge, scientists had found no way to codify these human “heuristics” so that they could be fed into a computer. Ever since the Dartmouth workshop, artificial intelligence pioneers had wrestled with this conundrum, which philosophers termed the “problem of induction.” But however hard they tried, humans’ mental shortcuts could neither be defined nor written into a program. “AI has utterly failed, over a quarter century, to solve problems that philosophy has utterly failed to solve over two millennia,” the Harvard philosopher Hilary Putnam observed wryly.[11]

			Hassabis and Silver had no idea how to program induction, either. But at least they identified the right problem. Somehow, AI scientists would have to overcome their attachment to provably correct deductive logic. Until they did so, the effort to build intelligent systems would be stymied by a contradiction. The essence of intelligence is the ability to respond flexibly to complex situations. But symbolic programming involves feeding inflexible rules into inflexible machines; inflexibility piled on inflexibility would never conjure flexible intelligence. To rise above this contradiction, future scientists would have to invent a new kind of machine: a machine that discovered the patterns in a near infinity of data.



* * *



			• • •

			In their third year at Cambridge, as they imagined this futuristic infinity machine, Hassabis and Silver persuaded an unusual professor, John Daugman, to have them over to his office for a series of tutorials. This sort of small-group teaching was what made Cambridge special, and Daugman’s interests ranged far beyond symbolic programming. He taught courses on information theory and computer vision, becoming famous for inventing an algorithm for iris recognition. Hassabis recalls the tutorials with Daugman as “nirvana sessions,” and Daugman took an instant liking to the friendly pair. “You could actually talk to them,” the professor remarked. “I’m sorry to say this, but in general that’s not true about computer scientists.”[12]

			The sessions with Daugman led Hassabis to his next epiphany. He realized that a superhuman computer would be more than just a means to a scientific end, the end being progress in scientific understanding. Rather, the computer might itself be the end, because information, marshaled by computer science, was the basic unit of reality. The traditional contenders for the status of fundamental building block—energy, matter—were less compelling by far; only information provided the basis for explaining all facets of experience. The behavior of particles, the flow of energy, and even human consciousness could be seen as examples of information processing.

			Of course, Hassabis had already absorbed the germ of this idea from Hofstadter. Biology, Hofstadter had argued, was an information processing system; what defined life was not muscle or tissue but the signals that animated them.[13] But with Daugman, Hassabis went deeper, studying Claude Shannon’s theories on what information is: how it can be quantified, stored, and transmitted over time and space; how it is defined by a simple but profound insight—as the opposite of uncertainty. Seen in this light, any reduction in uncertainty would depend on information, intelligently processed. A theory of everything—that is, a theory that reduced uncertainty to something near zero—would in all probability take the form of a computer program.

			“That’s the way I still view the whole universe,” Hassabis said later. “I think information is the fundamental unit.”

			This was just the first part of the epiphany, however. If information was the fundamental unit of reality, what came on top of this foundation? To Shannon, the answer was computation: the processes for sifting information, moving it around, and generally deriving meaning from it. This insight led Shannon to theorize computers that did not yet exist: They needed to exist, and so they would exist. But what if, nearly half a century later, computing was at an impasse, as it appeared to Hassabis and Silver? Perhaps the answer was to move another level up: from information on level one, to human-designed computation on level two, to machines that figured out how to design their own computation on a third level. Such machines—artificial intelligence systems, or programs that designed programs—barely existed, but they would fill an obvious gap: If humans lacked the wisdom to teach machines induction, the infinity machines of the future would teach themselves to crack the problem. Like Shannon before them, Hassabis and Silver believed that such systems needed to exist, and so they would exist.

			Hassabis sometimes explained the need for an infinity machine by contrasting physics with biology. “A deductive system like mathematics may be the perfect description language for physics,” he said; Newton had managed to capture the nature of motion in a series of equations. “But AI may be the right description language for biology, because biology is so messy, emergent, dynamic, and complex.” It was impossible to imagine something as elegant as Newton’s laws to describe a cell. But if you fed an infinity of data about cells into an inductive computer, the machine might figure out a way of describing what was going on—it would see the unseen patterns, the hidden laws, that explained cellular behavior. “AI—the kind of information system we’re building—will probably be the right tool for this,” Hassabis suggested.[14]

			Over the ensuing years, Hassabis’s two-part epiphany stuck with him. First, information was the fundamental unit of reality. Second, a machine that learned for itself how to induce nature’s patterns was the most powerful imaginable tool with which to apprehend reality. And while artificial intelligence could push the frontiers of science, it could also do much else besides: discover medicines, extending the lifespan of humans; solve the obstacles to nuclear fusion, rendering energy clean and abundant. As Hassabis once put it to the Guardian, “What we’re working on is potentially a meta-solution to any problem.”[15] A machine that could navigate an infinity of data would be infinite in its reach.



* * *



			• • •

			Graduating from Cambridge in 1997, Hassabis flirted briefly with the idea of a year off in Japan, where he planned to study Go. But he chose instead to work on Black & White, Peter Molyneux’s latest game project.[16] The players of this “god sim” would be equipped with divine powers, and they would choose whether to be black or white, terrible or benign, perhaps discovering something of their own character in the process.[17] The god-player’s choice of personality would color the game’s simulated world: If the player opted to be evil, the landscape would darken; if the player was good, there would be angelic chirpings in the background. Whichever path the players chose, their challenge was to persuade the masses to believe in their powers. Reflecting his own life as a creative impresario, Molyneux was obsessed with the idea that a deity is nothing without followers.[18]

			Hassabis was drawn to Black & White by the opportunity to experiment with AI programming. Whereas the characters in Theme Park had been complex finite-state machines, obeying fixed rules governing their preferences, Black & White would be the first game in which the avatars’ internal rules changed based on feedback. If a digital creature hurled rocks at villagers and the player responded with a slap, the creature would learn not to repeat this transgression. If a creature ate excessively and the player reassured it with a pat, the creature would adjust its algorithmic preferences in favor of continued bingeing. This basic “reinforcement learning” system was a small step in the direction of AI: a program that adjusted its program—that was capable of learning. On a more practical level, the creature’s adaptability made every experience with the game feel fresh. When Black & White eventually appeared, it was another Molyneux blockbuster.

			Hassabis contributed to the early brainstorming for the game, but he did not stick around to implement the vision. He had matured since his first stint with Molyneux, and his reaction this time was different. Before going to Cambridge, Hassabis had been so excited to be at Bullfrog that he ignored Molyneux’s volatile side; now he noticed it. He could see that, despite his undisputed creativity, Molyneux was a fabulist, a teller of tall tales, often promising journalists that his next project would include some fantastical technical advance, never mind that his own coding team had assured him that it was impossible. In his conversations with Hassabis—his protégé but now, potentially, his rival—Molyneux would claim to have discovered a secret new path forward to AI, but he would never quite produce the evidence: He was by turns emphatic, vague, elusive, and menacing, yo-yoing between warmth and iciness, bravado and tears, stoking the anxiety of everyone around him. Years later, Hassabis compared Molyneux to the mysterious character in The Magus, a novel by John Fowles. The magus is manipulative, mendacious, a master of illusions and mind games. “That was pretty much how Peter approached me,” Hassabis said.[19]

			I thought back to what Hassabis had told me about his mother’s religion—about how bad he felt it was to dominate people. Perhaps, if life were a god game, Molyneux would be the black god, exercising power through manipulation and menace. Hassabis would be the white god, exercising power by dint of contagious enthusiasm and lucidity.

			“The worst thing you can do to somebody is to be controlling,” Hassabis said to me again. “I go to great lengths not to be like that.”

			Besides, Hassabis by now had larger ambitions. Toward the end of his time at Cambridge, he had confided to his friends that, to pursue his dream of building AI, he planned to found a company.[20] It was a shocking idea. Entrepreneurship was a foreign concept on the Cambridge campus; Britain had no equivalent to Silicon Valley. “If you had looked at the students and asked, ‘Who’s going to set up a company?’ the answer would’ve been nobody,” one of Hassabis’s contemporaries recalled. “It was like, who are you going to work for, or what PhD are you interested in? Of course you don’t set up a company!”[21] Perhaps thanks to his exposure to Molyneux, perhaps also to the influence of his free-spirited father, Hassabis was an exception. He saw no reason not to start a company—and so he did.





Chapter 3




				The Jedi

			 			One night in early 1998, Hassabis slouched back in a comfy chair at his parents’ home in North London and stared outside into the dark sky as he listened to the soundtrack of his favorite movie, the sci-fi classic Blade Runner. The ramifications of his recent decision were beginning to sink in. He had traded in his job with Peter Molyneux for a shot at starting his own firm, and entrepreneurship suddenly felt daunting. But he wasn’t going to sit around wondering what might have been.

			“You only get one life,” he told himself.

			Hassabis’s first call the next day was to his friend David Silver. When they were at Cambridge, Hassabis had talked about his plan to found a company, and Silver had been intrigued without ever quite believing him. After all, the celebrated Peter Molyneux pretty much worshipped the ground on which Hassabis walked. Why take the risk of starting a competitor?

			“That games company we talked about, do you want to do it?” Hassabis asked. The previous evening’s doubts had been erased. His conviction was infectious.

			Silver had taken a job at a cool software boutique, building special effects for movies. He didn’t miss a beat. “Absolutely. Let’s do it.”[1]

			Silver went over to the Hassabis home, and the two of them thrashed out a business plan. They named their fledgling studio Elixir, this being, according to a handy dictionary, “the quintessential part of any substance.” “Obviously I had no clue as to what this meant, but it sounded good,” Hassabis wrote in the Elixir Diaries, a series of dispatches that he published monthly in a gaming magazine.[2] Having grown up on stories and movies, frequently imagining himself in the shoes of the heroes, Hassabis was taking the logical next step. He was composing his own story.

			Armed with a name, a business plan, and one brilliant ally, Hassabis set out to recruit more talent. Top of his list was a game designer named Joe McDonagh. A couple of months earlier, McDonagh had tired of his big-company employer and applied for a job at Molyneux’s studio: His submission had consisted of a bottle containing a tea-stained message from a person shipwrecked on the island of “Korporate.” Impressed, Hassabis had taken charge of interviewing the applicant, noting that his CV mentioned a strange pair of hobbies: origami and boxing. The interview consisted of Hassabis challenging McDonagh to a series of games; he beat the candidate in a race to fold an origami bird, but decided not to test his left hook or his haymaker. Now Hassabis offered McDonagh a job, working for him rather than Molyneux.

			The next person on the list was a wizard named Tim Clarke, whom Hassabis had known at Cambridge. Clarke was into coding, theoretical physics, and weightlifting. When still at high school, he had written a program that simulated the sensation of flying over Mars. This was a hit among space nerds and got him a summer job at NASA.

			Hassabis quickly talked McDonagh and Clarke into joining. His powers of persuasion were uncanny: “Demis had what we called his Jedi mind trick,” Silver said later. “He would kind of be like, ‘You will believe the things I’m going to say,’ and then people did believe them.”[3] The stint with Molyneux had no doubt helped Hassabis to develop this presentational flair. Entrepreneurship flourishes in clusters such as Silicon Valley, where technologists learn how to project confidence by apprenticing to one another. Britain was, to a first approximation, a start-up desert. Hassabis was lucky to have spent time working for a master storyteller.

			Having assembled his three cofounders, Hassabis set off to raise money. Typically, game design studios sought backing from game publishers, which provided up-front capital in exchange for a large share of future revenues. But Hassabis reckoned he would get a better deal by following the Silicon Valley model and tapping venture capitalists. “The plan was simple,” Hassabis explained. “Blow them away with impressive stats on Theme Park, talk them through the detailed business plan, enthuse about the backgrounds and records of the core team.”

			In the late 1990s, however, London venture capitalists hardly deserved the title. In Silicon Valley, T-shirted start-up founders raised millions from seasoned investors. In London, Hassabis felt obliged to don a stuffy suit, and the investors were more pickled than seasoned. Arriving at his first pitch meeting in the financial district, Hassabis was greeted by two young associates who led him off to their preferred meeting place, a restaurant. There, according to the Diaries, they ordered three bottles of wine: A couple of hours and many glasses later, the associates announced that it was time to meet their boss, who, as it happened, was in a pub around the corner. Pints of lager were served up, and Hassabis felt hot and drunk and exhausted. Still, he launched into a stump speech about his chess exploits, and soon the impressed boss made him an offer. But it was not for Elixir. Hassabis should think bigger than that silly start-up, the boss declared; he should work for the boss’s firm as a currency trader. Such was the City of London’s commitment to British entrepreneurship.

			Several days later, Hassabis received a letter from his recent drinking buddies. They were willing to back Elixir after all, and would kick in £2 million; but in return they expected fully half of Elixir’s equity. To be fair to the investors, this was by some measures an unsurprising proposal: Back in the 1960s, Silicon Valley’s first venture capitalists kick-started the entrepreneurial ecosystem by offering terms that were roughly as brutal.[4] But there was no way that Hassabis was going to accept this sort of proposal. Surrendering half his equity would mean giving up control of Elixir, and if there was one thing that the Molyneux experience had taught, it was that he hated to be controlled by anyone. After fruitless negotiation and a dozen attempts with other so-called venture capital outfits, Hassabis gave up. “They liked us, but they wanted our soul in exchange for the money.”

			Hassabis had kept himself afloat with his savings from his time with Molyneux. Now his cash was running low, and he was getting desperate. He was still living at his parents’ house, and he rode the bus to work; for a while he drove his mother’s beat-up car, but then the clutch broke. Fortunately, it turned out that another part of Britain’s start-up ecosystem—rich individuals, so-called angel investors—was in healthier shape than the venture capital part of it. Over the next couple of months, an industrialist, a lawyer, and Peter Molyneux himself all ponied up a bit of cash.[5] Hassabis rented a small, windowless workspace near a motorway junction. On July 7, 1998, Elixir was founded.



* * *



			• • •

			When Hassabis had talked of starting a company during his last months at Cambridge, his ambition had been to build powerful AI, not just to design video games.[6] In founding Elixir, he was balancing his ambition against his practical side. A games studio would allow him to at least experiment with AI, and it would give him entrepreneurial experience. It might also make him rich—rich enough, perhaps, to launch his ultimate dream: a Manhattan Project for artificial intelligence.

			The Elixir crew got down to work, noodling ideas for the first game project. The roof was made of corrugated iron and there was no ventilation; the gamers sat on recycled school chairs and argued about whether eating scrambled eggs would have unacceptable consequences for the office’s air quality. Hours of intense silence would be followed by raucous discussion: Should Spock have been the captain of the Enterprise rather than Kirk? Which football stars had the worst haircuts? The team also played fantasy football and the video game StarCraft in an attempt to satisfy Hassabis’s “burning desire to play and win something, anything,” as Hassabis himself put it. A month after Elixir got started, Hassabis won the five-game Mind Sports Olympiad for the first time. He showed up at a hotel in West London and bested some two thousand rivals, sprinting between games in different rooms so that he could rack up multiple wins simultaneously.

			Hassabis did not do much of the coding at Elixir, but he provided most of the vision. One time at Cambridge, he had played an obscure board game based on a power struggle in a banana republic. This was early 1995, and the media was flooded with photos of Russia’s invasion of Chechnya. The combination of the game and the grim wartime imagery got Hassabis thinking. “I began to ask myself about the people who make history, the men who shape the courses of our lives. Who are they? How do they become what they are?”[7] Following this line of thought, Hassabis came up with a twist on Molyneux’s god formula. He imagined a dictator game: The player would assume the identity of a faction leader who had to oust the ruler by means of demagoguery, political intrigue, or brute force, with the fate of millions of lesser beings dependent on the outcome. The idea became Elixir’s first project: Republic: The Revolution.

			To put flesh on this concept, Joe McDonagh took himself off to the British Library to learn about Russia and its former Soviet satrapies. He also discovered a bizarre relic in a rough part of South London: the Society for Anglo-Soviet Cooperation. McDonagh installed himself in the society’s dilapidated reading room and glanced warily at the odd characters browsing the bookshelves. He presumed that they were spies, and he presumed that they presumed that he was a spy: A life lived through games can stimulate the imagination. After a couple of months of reading, McDonagh dreamed up the fictional but realistic country of Novistrana, featuring elements of Belarus, Ukraine, and Azerbaijan. Novistrana would have a dictator, ample corruption, and Eastern Orthodox churches.[8]

			Echoing Molyneux, Hassabis demanded heroic efforts from his coders. Novistrana was to be populated with legions of plausible people: husbands, students, housewives, and drunks, each living separate lives, each of them believable. Hassabis also wanted groundbreaking, high-definition graphics, so that the moss would be visible in the cracks in the buildings. By the end of 1998, Elixir had made enough progress to attract a funding package from a game publisher, Eidos. Having struck out with the venture investors, Hassabis fell back on the standard source of capital.

			Armed with the additional cash, the team moved into a larger office in the trendy neighborhood of Camden. There were curving metal beams under the roof, and McDonagh and Clarke, the boxer and the weightlifter, took turns swinging chimpanzee-style from one beam to the next one. Hassabis installed table football and announced to all and sundry that nobody would beat him, ever.

			His lieutenants trained maniacally to prove him wrong. At length, the evil day arrived. The champion’s reign ended.[9]

			Hassabis retreated from the table and sat in his chair mutely.

			“There was this dark cloud over his chair. He had this somber, cloudy face. And at a certain point he just couldn’t contain it anymore.

			“He stood up and said, ‘It’s like my soul is on fire!’ ” David Silver remembered.

			“Was there an element of self-mockery?” I asked Silver. “Or was it completely serious?”

			“It was both. It really was how he felt. But I think he also knew that it would get a laugh or something.”[10]

			Through 1999, the team slogged away on the details for Republic. Hassabis urged his art team to create imposing cities that reflected the premise of the game: that the man on the street is a mere ant. To stir the creative juices, he led viewings and discussions of film noir classics: Fritz Lang’s Metropolis, Batman, and his own favorite, Blade Runner. The artistic possibilities were expanded by Tim Clarke, the weightlifter, who coded a world-class graphics software that could render images in photorealistic detail, down to the screw threads on the bolts of Novistrana’s brutalist factory machinery.[11] Announcing Clarke’s achievement in the gaming press, Hassabis dubbed his system the “infinite polygon engine.” Jealous rivals mocked it as the “infinite monkey engine.”[12]

			Meanwhile David Silver pushed AI for games to the next level. The characters in Theme Park had differed little from one another, but Silver made it possible for Republic to feature proper individuals. There was Ludmilla Mironova, a sleazy town councilor and a walking advertisement for Soviet-era cosmetics. There was Eduard Satarov, an even sleazier journalist with a huge beer gut and a fantastic comb-over. Hassabis declared expansively that there would be fifteen hundred of these highly differentiated characters, plus “a million individual living, breathing people with their own daily routines and their own beliefs and loyalties.” Thanks to Silver’s algorithms, each character would develop as it interacted with the next, shaping the game’s development.

			At the end of 1999, Hassabis went public with his work in progress. He granted a long interview to the gaming magazine Edge, which ran a gushing cover story on Republic. Hassabis, the magazine suggested, might be inventing the future of gaming; Republic was “one of the most ambitious computer games ever.”[13] “Long term, I want to be the best games developer in the world,” Hassabis told another interviewer.[14] The echoes of Peter Molyneux’s ebullient storytelling were obvious.



* * *



			• • •

			Just over a year later, at the start of 2001, Elixir’s grand ambitions collided with a hard deadline. Republic was to be unveiled at the Electronic Entertainment Expo that May: Fifty-five thousand developers, publishers, retailers, and journalists would descend on Los Angeles. The reception that Republic garnered would determine its fate. “If the competition is working fifteen hours a day, I want us to be working sixteen hours a day,” Hassabis declared during the lead-up.

			With a real-life Ender in their midst, several members of the Elixir team worked even more than that. Tim Clarke was known for coding into the small hours, passing out on a sofa, then waking up, soaping his armpits, and sitting back down at his terminal. Republic’s wild complexity was causing trouble, and in the week before the expo David Silver was still hacking at the code, struggling to get the demo working. In desperation, he had resorted to a trick. The computer he used had to look normal from the outside, since the game would need to work on customers’ standard home PCs; but Silver and his colleagues surreptitiously stuffed the machine with eight times the normal quantity of memory. Even so, the combination of high-definition graphics and differentiated game characters was causing the system to choke. The day before he was due to fly with Hassabis to LA, Silver stayed up all night, trying desperately to get the demo working.

			When morning arrived, at the last possible moment, Silver saved his code and powered down, Hassabis scooped up the computer in his arms, and the two rushed out for the airport. As they went through security, their flight was closing, and Hassabis and Silver began running. The two men reached the gate with no time to spare. Proceeding to their seats, their faces pouring with sweat, they nearly injured a few passengers as they marched down the aisle with the computer. Somewhere toward the back of the aircraft, Silver stored the machine by the extra seat he had bought for it. As soon as the plane was in the sky, he resumed his fight to make the code work.

			Arriving at the cavernous Los Angeles Convention Center, the two comrades made their way to the private room where Hassabis would present Republic to executives and industry journalists the next morning. By now dizzy with sleeplessness, Silver set up the system. Elsewhere in the expo hall, five thousand other development teams fanned out over an area equivalent to eight soccer fields.

			Standing in front of the computer the next day, Hassabis launched into his first presentation. The boss of his publisher-financier and several other bigwigs had arrived to watch: This first session would be among the most important. But as soon as Hassabis began talking, Silver’s souped-up system crashed, forcing Hassabis to reboot it. Even more humiliatingly, as the computer rumbled back to life the screen displayed the system’s vital statistics, including the massively augmented memory. Something inside Silver snapped. With the opening music for the demo throbbing in his brain, he edged toward the doorway and bolted. To this day, he cannot stand to listen to that soundtrack.

			Silver found a sofa and passed out. There was no fight left in him anymore; he slept for a few hours without stirring. When he finally awoke, he set off to see Hassabis. He had tried everything, everything, he would tell his friend. Everything to make the demo work. Everything to save their company.

			When Silver eventually located Hassabis, it transpired that no apology was needed. Hassabis had proceeded with his presentation despite the hardware disaster, and everyone had loved it. The demo had been clunky—even when he got the PC working, it could only display the frames in slow motion—but the accompanying patter had been genius. Hassabis had waxed effusive about Republic’s imaginative scope. Players could order beatings of noted community members, plot the martyrdom of a revolutionary student, and experience the dynamics of rioting throngs—here Hassabis dazzled his audience by invoking the book Crowds and Power by the Nobel Prize winner Elias Canetti. Such was the curiosity and anticipation that Hassabis generated, Republic: The Revolution won an award at the expo for the best upcoming game, and a reviewer declared it the most exciting strategy concept since Civilization.[15] Standing on the precipice, teetering at the edge, Hassabis had pulled off his greatest Jedi mind trick ever.



* * *



			• • •

			Despite this improbable escape, Elixir was in trouble. The hardware crash reflected a hard truth: The computers of the time couldn’t handle Hassabis’s ambitions. Round-the-clock coding sessions were taking their toll: Silver’s sudden exit from the presentation room had been a warning of incipient burnout. Several other members of the team were in a similar condition. Hassabis’s mind tricks had helped him to recruit talent, raise money, and create spectacular buzz. But they had raised expectations to the point where delivery became almost impossible.

			Over the next couple of years, Republic’s release date was pushed back repeatedly.[16] To get the product out the door, the team diluted the game’s most innovative ideas, and morale inevitably suffered. As the keeper of the vision, Hassabis fought a rearguard action against compromise, and it took time for him to recognize the trap that his own charisma created. “Who would’ve thought that you can actually inspire people too much?” he reflected, years later. “Well, you can, because you can get to the point where you are deluding your team, and then they are deluding you also.

			“It’s like, I’m making the judgment this is possible because the engineers are telling me it’s possible; but they’re only telling me it’s possible because I’ve over-inspired them,” Hassabis said. “So, in fact, none of us is getting real feedback.”

			Republic eventually went on sale in August 2003. Relative to the hype, it was an anticlimax.[17] This disappointment was quickly followed by a more fundamental setback: David Silver quit Elixir. The circumstances of Silver’s departure raised a troubling question: Perhaps Hassabis was guilty of more than over-inspiring his troops; perhaps he might be harming them. Over the previous year or so, Elixir’s coders and designers had taken to pulling Silver aside: You tell Demis that this feature will not work, they’d plead. You’re the only one he’ll listen to. But the job of communicating reality to Hassabis was grueling. “You had to push the conversation to the point where he got more and more intense and defended his positions more and more strongly,” Silver said later. “The stronger he got, the closer you were. Then eventually he might go quiet. That’s when he had absorbed the message.”[18]

			After months of playing go-between, Silver decided that he had to go elsewhere. He moved to the south of France with his girlfriend and spent a year recuperating. Hassabis was left to contemplate the thin line between his charisma and his obstinacy, between his gift for storytelling and the risk that he might drink his own Kool-Aid, between his magical capacity to inspire people and the risk of inadvertently destroying them. Silver was the first to say that Hassabis’s intentions were good: When Demis talked about the influence of his mother and his horror of manipulating others, he meant it.[19] But it was one thing to abhor the idea of controlling colleagues. Given his Jedi-level charisma, it was quite another to avoid it.

			Of course, Hassabis was not alone in this dilemma. Many sensational entrepreneurs, from Steve Jobs to Elon Musk, have bent reality with their stories, shifting the boundary between the possible and the impossible, with consequences both exhilarating and harmful. Closer to Hassabis’s own experience, Peter Molyneux could be both inspiring and abusive. Relative to these other leaders, Hassabis may have been more self-aware, and more anxious to correct his own tendencies. “I am strong-willed and stubborn,” he told an interviewer during the early days of Elixir. “I try to be open-minded to my ideas not always being the best ones,” he added.[20] And to be fair to Hassabis, he seldom put more pressure on colleagues than he put on himself. By the time Elixir went out of business, in 2005, he, too, was burned out—“Demis is killing himself,” a friend remembers thinking.[21] But that, in a way, was exactly the point. A boss who approached everything with relentless Ender-style intensity was bound to be tough on whoever was around him.

			One day I discussed Hassabis’s double-edged mind powers with a psychologist. She caused me to rethink my Black & White analogy—the one where I had imagined Molyneux as the dark, manipulative god, and Hassabis as the friendly games-playing deity. Charismatic people cannot be just bad or good, the psychologist explained. If they are bad all the time, they will alienate everybody, and a charismatic person with no entourage is a contradiction. Likewise, charismatic leaders cannot be consistently benign. In the roar and crash of life, there are bound to be moments when interests and opinions collide. Somebody has to prevail over somebody else. Given their unusual gifts, charismatic personalities will end up on top, no matter how earnestly they aspire to avoid dominating others.

			There is a further point, the psychologist continued. It is not merely that charismatic personalities must inevitably swing between inspiring and controlling people. The oscillation itself is part of the charisma. Followers become addicted to a Jedi’s variable moods, just as gamblers become addicted to arcade machines that disappoint and disappoint and then spike their brains with jackpots. If slot machines spat out similar rewards turn after turn, there would be no juice in the game; if a parent is consistently loving, the child will feel no need to cling on anxiously. Oscillation stokes dependence; it sinks the hook into the mouth. This was precisely what Hassabis had experienced and then angrily rejected in his relationship with Molyneux.

			What of Hassabis himself, I wondered? His intentions were good, but could he remain good? If Hassabis set out to build an infinity machine, he would have to cut a path through tough terrain, and adversity would test his personality. The outcome of this struggle would have consequences for society writ large: Hassabis’s character—his temperament, his integrity, his choice of where to stand in moments of challenge—would matter. In Molyneux’s Black & White, the player-god’s moral compass determined the color of the world. It was a metaphor to ponder.



* * *



			• • •

			Elixir’s failure came with an unexpected benefit. It caused Silver and Hassabis to move on to the next chapter in their lives, picking up the threads of their studies at Cambridge.

			When he left Elixir for the south of France, Silver read a textbook by a University of Alberta computer scientist named Richard Sutton. Its premise matched the conviction that Silver had developed at Cambridge: that inflexible machines trained on inflexible logic could never achieve flexible intelligence. Rather, machines should learn by trial and error, as Shannon had said; they should interact with the world, receive feedback, and use that feedback to fine-tune their behavior. Sutton’s textbook laid out ideas for implementing this approach, which was known as reinforcement learning.

			The basic idea of reinforcement learning, often known as RL, was already familiar to the gaming fraternity. When he had worked for Molyneux, Hassabis had proposed that a simple form of reinforcement learning should be coded into Black & White: The slaps and strokes from the god-players would provide feedback to the digital creatures, which would adapt their behavior. At Elixir, Hassabis and his comrades had invited an RL professor to give a talk at the studio; Silver recalls being “gobsmacked” by the presentation.[22] But Richard Sutton’s textbook led Silver in deeper, describing the algorithms that a programmer might deploy to make RL a reality. If computers could be trained to understand the world by interacting with it directly, they could learn what to do in any given situation, effectively programming themselves. “That’s real AI,” Silver remembers thinking. Apologizing to his girlfriend, who preferred the climate in the south of France, Silver wrote to Sutton and proposed that he should do a PhD in snowy Canada.

			“AI is often vaguely defined,” Silver said later. “But Sutton’s book showed that we could really pin it down. AI is a system that learns for itself how to solve problems.

			“You are trying to build a system that can figure things out without human instruction. Rich Sutton was laying out a road that stretched all the way to the horizon. I wanted to reach that horizon. That was it for me.”[23]

			In 2004, Silver moved to Alberta.

			When Elixir closed the following year, it was Hassabis’s turn to choose a fresh direction. Like Silver, he needed to recuperate: “It was probably the hardest time in my life; I was in pieces,” he said later. Like Silver, he decided that the best way to rebuild himself was to go back to learning.

			As a precocious undergraduate, Hassabis had rejected symbolic programming because it failed a basic test: It was not how human intelligence operated. The way Hassabis saw things, this test was crucial, because powerful machine intelligence, when it eventually arrived, would emulate the human variety. After all, the human brain provided the only grounds for believing that a general, flexible intelligence was even possible: The brain was, as Hassabis said, the “existence proof” that underpinned AI endeavors. It followed that, to build artificial intelligence, one should understand human intelligence first. Following this logic to its daunting conclusion, Hassabis resolved to do a PhD in neuroscience.[24]

			Hassabis lacked the normal training for this. He was neither a doctor nor a biologist nor even a psychologist; he knew little of the chemistry of the brain and the nervous system. Undismayed by this considerable gap in his résumé, he brandished his credentials as a computer scientist, talked up his exotic entrepreneurial record, and won acceptance to the doctoral program at University College London. His supervisor, a rising academic star named Eleanor Maguire, feared that, after managing a company, Hassabis might find academia dull. But Hassabis assured her—truthfully, in that moment—that he just wanted to study: “I don’t need to be in charge of things, I’m fine to learn,” he insisted. Maguire responded by assigning her new student a pile of scientific papers to read before he showed up on campus.

			In the summer of 2005, Hassabis married his Cambridge girlfriend. The two headed off on honeymoon to an Italian beach, the groom lugging his neuroscience homework with him.



* * *



			• • •

			Hassabis’s beach reading that summer concerned the workings of the human memory. The scientific papers featured two schools of thought: One side believed that memories are like videos, waiting to be recalled from the data banks of the brain; the other side held that the brain retained only a bare essence of the past, so that memories were not so much recalled as reconstructed. The first camp asserted that memories are faithful to what really happened. The second camp regarded memories as unreliable, since the process of reconstruction left room to hallucinate fictitious narratives.

			“It was obvious to me that the reconstructive people were right, that it wasn’t a video,” Hassabis said later. He was particularly taken by studies of witness statements, which showed the power of suggestion. If witnesses were subtly prompted by a police questioner, they would give the evidence that the police officer wanted, proving that the brain could be tricked into reconstructing a memory of something that had never happened.

			Sitting on the beach, before even embarking on his PhD, Hassabis experienced a eureka moment. If memories were reconstructed, then perhaps they might use the same brain mechanisms as imagination. To be sure, the goals of memory and imagination were opposed: Memories supposedly involve real events, whereas imagination deliberately conjures novelty. But the process of creating vivid images, historical or hypothetical, seemed linked. And although memory is retrospective and imagination often visualizes the future, Hassabis recalled a line from Through the Looking-Glass. “It’s a poor sort of memory that only works backwards,” the White Queen tells Alice.

			“Maybe looking at this other capability, imagination, would be a creative way to resolve the memory debate,” Hassabis remembers thinking.

			On his first day as a PhD student, Hassabis arrived bubbling with research hypotheses. Not all of them were sensible. “He’d have these crazy ideas,” his friend and fellow PhD student Dharshan Kumaran recalled. “But he was very creative.”[25]

			Kumaran was Hassabis’s comrade from the junior chess circuit. He had gone on to study medicine and become a doctor before embarking on a neuroscience PhD; when it came to the physiology of the brain, he knew a lot more than Hassabis did. But Kumaran soon discovered that they made a productive pair. Hassabis was full of wacky conjectures. Kumaran supplied rigor.

			“I was always trying to pick the game-changing idea,” Hassabis recalled. “And then it’s like, ‘Oh, the details! Who knows, whatever.’ ”

			“We always used to have our discussions in the tiny kitchen in the neuroscience building,” Kumaran remembered. “Demis would explain some idea and I’d say, ‘No, that doesn’t seem right to me.’ Then he’d go back and think about it in a different way. And then we’d be back in that kitchen.”[26]

			After batting ideas back and forth, Hassabis and Kumaran eventually came up with a workable experimental strategy. They would test patients who had suffered damage to the hippocampus, a pocket of tissue located deep within the brain where the day’s memories are recorded. If Hassabis’s hypothesis was correct—if memory and imagination were linked—patients with memory loss would also struggle to imagine things.

			With Maguire’s help, the two friends identified a handful of rare patients who had damage to the hippocampus but were otherwise healthy. Sure enough, when Hassabis and Kumaran carried out their tests, they got the result that Hassabis had anticipated. Damage to the hippocampus harmed patients’ ability to visualize a three-dimensional scene, like a day at the beach or a shopping trip. A part of the brain associated with memory was indeed crucial to imagination.

			At the start of 2007, Hassabis, Kumaran, and Maguire published their research in the prestigious Proceedings of the National Academy of Sciences.[27] It was a remarkable achievement: Science listed it among the year’s top neuroscience breakthroughs, and the paper eventually collected over seventeen hundred citations.[28] But for Hassabis, the scientific accolades were only part of the thrill. He was more excited by the implications for the existential questions that preoccupied him. If memories were not records of some objective external reality, but rather simulations created by the brain, perhaps all of reality might be a mental fabrication.

			“The structure of the world is, basically, created by the mind,” Hassabis told me during one of our long talks. “I was trying to prove that with my neuroscience work: that reality might be a simulation.”

			I thought back to my first encounter with Hassabis, when he appeared on that conference stage, invoked Immanuel Kant, and explained that the ultimate goal was “to understand our own minds better.” Physics explained the external world. Neuroscience explained human beings’ internal world. But neuroscience was the nobler subject of study, because the mind creates reality.[29]

			“I like Kant’s idea that the world out there is basically a mental construct,” Hassabis reiterated to me now. The stuff that physicists studied—matter, energy, time—was ultimately less real than the bits of information pulsing between neurons.

			“I’ve always been fascinated by the Brain in a Jar thought experiment,” Hassabis continued, referring to a philosophical device for exploring the relationship between reality and consciousness. The experiment posits that a brain is removed from a body and kept alive in a jar of nutrients. It is hooked up to a computer that simulates sensory inputs: a view of the sea, the sound of the waves, the smell of salt and seaweed. The computer creates a virtual reality so convincing that the brain believes it is still living a normal life, taking in the outside world through eyes, ears, and nostrils. Of course the brain is really just experiencing a simulation—a series of ones and zeroes generated by a computer.

			I could see why Hassabis was taken with this thought experiment. It was the premise for The Matrix, another classic sci-fi film that he was fond of. The humans in the movie believe they are living real lives, but their minds are connected to a master computer and their bodies are harvested for energy.

			If the brain in the jar could be misled into believing that it was experiencing reality, how can the rest of us be sure that we are not also living in a simulation?

			If the brain in the jar can see and hear and smell things that have no presence in the real world, perhaps our consciousness may also be a product of ones and zeroes in the brain, utterly divorced from whatever physical reality exists around us?

			“Reality may be constructed by the mind,” Hassabis repeated. “That’s what I think Kant was getting at.”

			I marveled at how Hassabis’s experiences and ideas appeared to slot together. His curiosity about physics had spurred him to work on AI, the ultimate tool to unlock science. His curiosity about AI had led him to investigate the human brain, the existence proof for intelligence. His work on simulations in video games echoed his research on simulations in the mind. And influences as various as Immanuel Kant, Gödel, Escher, Bach, John Daugman’s tutorials, and neuroscience had pushed Hassabis toward the same bottom line: that information was the fundamental unit of reality.

			The God of the Bible, to Whom Hassabis had prayed as a young child, controlled the universe and all reality. The god of Black & White controlled a simulated universe, coded into a computer. But if information and simulations were as real as reality itself, the boundary began to blur. A computer that simulated a limited world could be seen as a limited god. A futuristic computer—a powerful AI—might be limitless, infinite.





Chapter 4




				The Gang of Three

			 			At the start of 2009, when Hassabis was finishing his PhD, Peter Molyneux popped into his life again. The two had been in contact as Hassabis, feeling the entrepreneurial itch return, had begun to noodle start-up ideas to pursue after academia. Seeing an opportunity, Molyneux dispatched an emissary to inquire whether Hassabis would like to join forces on his next game. When Hassabis demurred, the emissary asked why. “I want to be the person who solves AI,” Hassabis responded.[1]

			The question, as ever, was how to go about this. Hassabis toyed with start-up ideas that, like Elixir, would combine an opportunity to work on AI with a commercial payoff. He imagined an AI-powered recommendation algorithm, focused on matching consumers with the right TV shows. He considered a variation: a recommendation system for the bag of tricks in Apple’s new app store. But these stepping-stone projects failed to quicken Hassabis’s pulse. Now thirty-two, he was conscious of his biological clock. It was time to pursue his life’s ambition more directly.

			As a first step toward founding a company focused squarely on AI, Hassabis enrolled as a postdoctoral fellow at the Gatsby Computational Neuroscience Unit, a division of University College London. The Gatsby’s researchers worked at the intersection of human and machine intelligence, making it an obvious place to scout for kindred spirits. The unit’s director, Peter Dayan, had demonstrated how the reward signals in reinforcement learning, the branch of AI chosen by David Silver for his PhD, mimicked the dopamine signals that reward human learning. Before him, the Gatsby’s founding director, Geoffrey Hinton, had pioneered another area of AI: so-called neural networks, loosely analogous to the human brain, with layers of decision centers, or “neurons,” hooked up to one another. Later widely celebrated, but in 2009 still relatively obscure, Hinton’s approach to AI was known as deep learning.

			Despite the Gatsby Unit’s pedigree, Hassabis’s first weeks as a postdoc were not encouraging. Most of the faculty dismissed his AI ambitions as far-fetched. They were trying to get reinforcement learning or deep learning to work on a few simple problems; they did not dream of superhuman machine intelligence. Still determined to identify soul mates, Hassabis figured that perhaps his fellow postdocs might be more on his wavelength, so he scanned the bios on the Gatsby website. But out of the entire cohort of Gatsby fellows, only one single researcher confessed to an interest in building powerful AI. Hassabis made a mental note of the photo accompanying the bio, and tried to remember the researcher’s name: Shane Legg—it had a cowboy ring to it. Perhaps he would bump into this cowboy guy in the Gatsby cafeteria.

			A few weeks later, with no serendipitous encounter having taken place, Hassabis headed off to America, hoping that it might prove more AI-friendly. In typical Hassabis fashion, he had arranged to do two fellowships simultaneously, at MIT and Harvard.[2] His MIT supervisor, Tomaso Poggio, was a physicist turned computational neuroscientist who taught the university’s oldest machine-learning class: Hassabis got along with him immediately. Later, Poggio would say that, of the many Nobel Prize winners he had encountered, the majority were both brilliant and lucky—lucky in the sense that they had chosen a research problem that turned out to be both consequential and soluble. But a handful of Nobel laureates, Poggio said, were so exceptionally gifted that they were going to win the prize no matter what. In this category, Poggio placed the physicist Richard Feynman, the biologist Francis Crick, and his postdoctoral student Demis Hassabis.[3]

			While at MIT, Hassabis also had the opportunity to meet Geoff Hinton, the founding director of the Gatsby, who was visiting from his subsequent base at the University of Toronto. By now, Hinton had labored on his deep neural networks for a quarter of a century, exhibiting what Poggio called a “religious belief” in their potential. In 2006, the professor and two coauthors had shown how to train big neural networks, dubbed deep belief networks: The step-up in size brought a step-up in performance.[4] In 2009, around the time he met Hassabis, Hinton received another boost: the opportunity to turbocharge these networks with special chips—“graphics processing units” originally designed to render video game images.[5] But even though Hinton was riding high, he found to his astonishment that Hassabis was as cocky as he was. “Demis is the only person I’ve ever met who’s more competitive than me,” Hinton recalled of that encounter.[6]

			To Hassabis’s disappointment, most of the researchers at MIT and Harvard were no more AI-forward than the Gatsby crowd in London. Strangely, the denizens of MIT’s prestigious Computer Science and Artificial Intelligence Laboratory, housed in a wacky, multicolored funhouse designed by the architect Frank Gehry, were especially traditional. The elder statesman of the laboratory, the computer scientist Marvin Minsky, had attacked neural networks since the 1960s. Nearly half a century later, neither Minsky nor his younger disciples seemed inclined to update their perspective.

			One day during his stint with Poggio, Hassabis met the head of the Computer Science and AI Lab, a revered figure named Patrick Winston. Hassabis had prepared for this moment: If the opportunity presented itself, he wanted to test his vision for an AI start-up on a pillar of the MIT establishment. Following his script, Hassabis told Winston of his plans. “I explained to him I was going to do reinforcement learning and deep learning,” Hassabis recalled. “We had a long discussion. He said it was just nonsense.”

			Hassabis put a brave face on this rejection. “Well, this is kind of fantastic,” he remembers telling himself. If an establishment figure had embraced his vision, it would have signaled that it lacked originality—and that rival entrepreneurs with similar ideas would soon be circling. The fact that Winston had dismissed his arguments, while saying nothing that Hassabis hadn’t heard before, confirmed that an AI company would at least be contrarian. But however much he reassured himself, Hassabis was up against tough odds. He couldn’t launch a company unless somebody believed. A contrarian with no following is merely an oddball.

			Returning to London in the late summer of 2009, Hassabis wrote a business plan for his envisaged AI start-up, which he called Project Orion. The idea was to build a computer version of the human brain, which could handle the subtle functions that Hassabis had studied for his PhD, such as memory and imagination. But the document’s principal significance was to reveal how far he was from getting a project off the ground. The business plan listed Peter Molyneux among Orion’s likely backers, but the truth was that Molyneux was not going to invest in a science experiment. The plan named David Silver as part of the founding team, but Silver was a long way from being ready to go back into partnership with Hassabis. With no capital, no brilliant cofounder, and an establishment that viewed artificial intelligence as a lot crazier than video games, Hassabis was in a far weaker position than he had been with Elixir.

			At the start of October 2009, Hassabis boarded an elevator at the Gatsby Unit. A curly-haired man with the lithe figure of a dancer maneuvered himself and his suitcase into the small space beside him. Hassabis immediately recognized the stranger as the elusive Shane Legg, the sole postdoc in the building who shared his AI ambitions.

			Glancing at the suitcase, and realizing that Legg was about to disappear out of town, Hassabis struck up a conversation. “Where are you going?” he asked brightly.

			Legg answered in a pronounced New Zealand accent. He was on his way to New York to attend something called the Singularity Summit.

			Hassabis had never heard of this event. “What happens there?” he asked.

			Legg explained that the Singularity Summit was an annual gathering of AI believers. The “singularity” was the moment when machine intelligence would surpass human intelligence. At that point, machines would know how to improve themselves without human assistance, and their capability would explode upward.

			The elevator reached the ground floor. The doors opened; the singular New Zealander marched off; the conversation was over. Hassabis was left to ponder what had just happened. After years of preaching the AI gospel to others, he had just met somebody who might be more wired into that world than he was.



* * *



			• • •

			Shane Legg’s path to the Gatsby Unit had been as improbable as Hassabis’s. Born three years before Hassabis, in 1973, he had grown up in Rotorua, New Zealand, a tourist town known for its boisterously active geyser and bubbling mud pools. At school, Legg had struggled so much with his lessons that his teachers suspected him of subnormal intelligence. His worried mother took him off to have an IQ assessment.

			After administering the test, the assessor grew furious. “Why have you brought this child here?” he demanded.

			Legg’s mother was upset. “I’m just being a responsible parent,” she pleaded.

			“This boy is somewhere above what we’d call gifted,” the test official retorted.[7]

			Notwithstanding this news, Legg continued to perform miserably in class until his parents bought him a computer. Like other children who, defying stereotype, find that solitary immersion in digital technologies is terrific for their mental health, Legg can still recite the vital statistics of his first love: “a Dick Smith VZ200, eight kilobytes of RAM, a Z80A processor.” Soon, Legg became an avid coder, and as he incorporated mathematics into his programs his performance in his school math class went from mediocre to outstanding. But he was not especially gracious about this change in his fortunes. He blew off his homework, railed at his teachers, and came top in the exams anyway. As Legg reflected later, the lesson of his youth was, “Write my own rules, because there’s a lot of bullshit around. A lot of bullshit.”

			Legg moved on to the University of Waikato to study mathematics. Feeling unfit and very skinny, he joined a gym and started weightlifting. To his surprise, he found it fun, and so he added cardio to his training program. Waikato was, perhaps remarkably, a hot spot for aerobic dance, and Legg thought to himself, “Why not?” Pretty soon, he could do the splits, and then he moved on to jazz dance, which incorporated elements of ballet.

			“So then I thought, ‘Damn it. Why don’t I just do ballet?’ ” Legg recalled later.

			“That sounds crazy. I’ll try it.”

			In a country where the archetypal male played rugby, Legg’s newfound hobby caused his parents to jump to conclusions.

			“My father went into denial about me being gay,” Legg recalls. “Which was quite weird because I wasn’t gay.

			“And my mother was interestingly fine with me being gay. So that was nice to know. If I had been gay, she would’ve been accepting of that.”

			After Waikato, Legg did a master’s thesis in math at the University of Auckland. The obvious next step was to do a PhD, but Legg’s rebellious side intervened again. Deciding that a PhD in theoretical mathematics was “rather hard” and “kind of pointless,” he took a routine job as a database engineer: There was not much Ender about him. For the next eighteen months, he settled into debugging corporate IT systems. The more-than-gifted boy who had bubbled up from Rotorua’s mud pools was on track to contribute zilch to scientific progress.

			In late 1999, at the height of the bubble in internet stocks, Legg moved on to his next gig: a start-up called Intelligenesis. This shift, as random as the proverbial flapping of a butterfly’s wings, would affect the path of AI history. Intelligenesis turned out to be no ordinary company, and its founder, a Brazilian American prodigy named Ben Goertzel, was not remotely normal, either. Perpetually unkempt, his face framed by waves of curly hair that fell below his shoulders, Goertzel had earned a PhD in mathematics by the age of twenty-two; by thirty, he had published four textbooks and had held university appointments in math, psychology, and computer science. In the mid-1990s, Goertzel had decided that the rapidly expanding internet was not merely a revolutionary communications platform or an opportunity to rethink commerce. It was a new form of intelligence, a sort of worldwide mind: Each computer on the network resembled a neuron, each hyperlink a synapse, each human user a sense organ.[8] In 1997, Goertzel founded Intelligenesis to build upon his vision.

			Goertzel set his team to work coding a digital brain. In some ways, this was a precursor to Hassabis’s Project Orion, but coming a decade earlier, and with computing still much less advanced, it was even more of a long shot. The plan for how this brain would function was a lot wackier, too. Goertzel planned to build a “Baby WebMind,” then release it on the internet and watch it mature into adulthood. Pretty soon, Goertzel insisted, a worldwide, self-organizing machine consciousness would spring forth, ending humanity’s monopoly on intelligence.[9]

			Goertzel’s baby-brain project was a bubble-era flight of hubris. But Legg enjoyed this trippy stuff so much that, after working remotely from New Zealand, he picked up and moved to New York, where Intelligenesis had an office. The way Legg saw things, the WebMind’s viability was almost beside the point. What captivated him was the question of what it meant to build intelligence, which further led him to consider what intelligence was, or what it might be. To someone whose intelligence had been misclassified as a child, no subject could be more riveting.[10]

			Having learned in his school days to write his own rules, Legg was also drawn to Goertzel’s willingness to call bullshit. For example, Goertzel showered contempt on the classic definition of machine intelligence, proposed by the British mathematician Alan Turing, which states that a computer program can be deemed intelligent when it can pass itself off as human. Goertzel countered that a successful WebMind wouldn’t ever meet that standard: It would never sound humanoid on such topics as how sex feels, and there would be no point teaching it to appreciate a sunset. “But this doesn’t matter,” Goertzel continued. “I’d rather have a computer program that knows it’s a computer and discourses about its computer-ness intelligently, than one that can successfully pull off a pathological-liar act and fool us into thinking it’s human.”[11]

			In late 2001, Intelligenesis went bust, and Legg spent the next nine months backpacking around Africa and Europe. But he stayed in touch with his old boss, and in 2002 Goertzel asked him to comment on a book that he was working on. The manuscript was provisionally entitled Real AI, the premise being that most artificial intelligence projects were contemptibly timid. But Legg urged that dismissing the bulk of AI as not real—and therefore puny or phony—might be impolitic. To protect Goertzel’s standing in the research community, Legg persuaded him to go with an alternative title: Artificial General Intelligence.

			Around the time he coined that term, Legg read The Age of Spiritual Machines by the inventor and futurist Ray Kurzweil. The book’s central message was that the power of computers was about to surge dramatically. Since the 1960s, technologists had referred knowingly to Moore’s Law, and the very familiarity of this concept had caused people to stop thinking about it. But the prophecy that the power of semiconductors would double every two years was not something to be filed and forgotten in the back of the collective mind. To the contrary, the more time went on, the more mind-boggling its implications. A doubling every two years implied exponential progress—the curve would start off relatively flat and then later explode upward. As of the year 2000, human brains were fully one million times more powerful than the most advanced machines, a huge gap in capability. But at some point in the 2020s, Kurzweil calculated, computers would draw even. And once that happened, they would accelerate past their creators. The singularity was approaching.

			Rather like Goertzel, Kurzweil occupied a tenuous space between visionary and weirdo. Convinced that humans would soon reach a kind of computer-assisted immortality, he was determined to cling on to life until the bots took over the task of extending his existence. For a while he ingested 250 supplements per day, not to mention multiple cups of green tea and glasses of alkaline water, all the while anticipating the moment when people could transcend human limits and enjoy life without end, or what Kurzweil called “indefinite extensions to the existence of our mindfile.”[12] But whatever the merits of this transhumanist vision, Kurzweil’s exposition of Moore’s Law affected Legg deeply. Reading his book, Legg realized that not only was the power of computers set to explode, the amount of data that could be fed into the machines would also explode, thanks to the spread of the internet. With better hardware and more data, the third component of AI—algorithmic advance—would become insanely valuable.

			“I was thinking AI is going to be real. I buy the basic argument of Kurzweil. So, if that’s the case, I should go get a PhD,” Legg recalled later.

			“So, I thought to myself, ‘OK, what’s the biggest issue in AI as I see it?’

			“And I thought, ‘Well, the biggest problem is there isn’t a measure for intelligence.’

			“It’s very hard to build an intelligent machine if you can’t even measure it.”

			Having discussed these matters thoroughly with himself, Legg found his way to Marcus Hutter, a researcher with similar ideas at IDSIA, an AI institute in southern Switzerland. Under Hutter’s supervision, he embarked on a PhD, assembling multiple possible conceptions of intelligence, and applying his mathematical training to their measurement. Critics of AI would later accuse its creators of skipping over this challenge: of failing to grapple with the difference between intelligence and mere statistical facility.[13] But Legg confronted this conundrum head-on; and the definition of intelligence that he settled on combined Goertzel’s rejection of Turing with his own advice to Goertzel. AI should not be measured by its ability to impersonate humans, since imperfect human cognition amounted to an arbitrary benchmark. Rather, the true mark of intelligence was generality. Together with Hutter, Legg landed on a summarizing phrase: “Intelligence measures an agent’s ability to achieve goals in a wide range of environments.”

			Legg completed his PhD thesis in 2008, entitling it “Machine Super Intelligence.” As he was finishing, he spent a year at the Swiss Finance Institute, where he used reinforcement learning to try to predict the gyrations of the capital markets. He contemplated the idea of launching an AI start-up—an attempt to succeed where Goertzel had failed—but decided that computing was still too immature and that entrepreneurship was too precarious. He convened a weekly neuroscience reading group, curious about how the functioning of the human brain might expand his conception of intelligence. In April 2009, seeking to deepen his understanding of this human-machine frontier, he began a postdoctoral fellowship at the Gatsby Computational Neuroscience Unit.



* * *



			• • •

			The following autumn, a few weeks after that brief elevator encounter, Hassabis spotted a second opportunity to get talking with the mysterious New Zealander. Legg was due to deliver a talk on the future of AI on October 31. He had given his presentation a mock-scary title, “The Halloween Scenario.”

			On the appointed day, Hassabis showed up in a dimly lit classroom and took his seat in the audience. Legg stood by a large screen, a fit figure with laughing eyes and a patterned button-down shirt. For the next two hours or so, he ranged enthusiastically from definitions of intelligence to developments in machine learning to the exciting spillovers from neuroscience, culminating with a Kurzweil-inspired explanation of how computer power was exploding. But then he pivoted to a dark warning—the Halloween Scenario of his title. “If this all takes off, we’re going to have people with brain-like AI architectures plugging their systems into exaflop supercomputers, and we have no idea how to deal with the consequences,” he declared. His words signaled alarm. His tone was still excited.

			“These systems to start with, maybe they are not that dangerous,” he went on. “Maybe they are not going to take over the world, do anything crazy. But they are starting to converge on the types of algorithms that we really should be worried about.” Computers that became superintelligent, and that developed agendas of their own, might subjugate or annihilate humans, Legg was saying.

			“We don’t know what they are going to do!” he concluded.[14]

			Legg was channeling a common view from the Singularity Summits. Steeped in science fiction, fascinated by catastrophe narratives as moths are fascinated by fire, the Singularity crowd contemplated Armageddon without seeming upset by it. Ray Kurzweil, one of the conveners of the Singularity events, summed up the standard sequence of emotions at the prospect of superhuman AI: Wow!, Uh-Oh, and What Other Choice Do We Have but to Move Forward? The shock, the fear, and then the resignation resembled the predicament of medical patients confronted with terminal diagnoses: At first, they contemplate doing something radical with their remaining time alive; next, they revert to their routines as though nothing much has altered. Human beings lack a vocabulary with which to process existential threats; they cannot think the unthinkable. They are wired to act as though life will carry on, for otherwise they could not act, and life would become impossible.

			Legg’s London audience, far removed from the Singularity vibe, was confronting the risk of Armageddon for the first time. That protective human wiring had yet to kick in. The seated figures listening to Legg were still processing the Wow! and Uh-Oh parts of Kurzweil’s sequence.

			A man spoke up from near the front. Legg had raised the prospect of an existential threat. If he really thought the future of humanity was on the line, surely he wasn’t going to end his lecture there, without saying what should be done about it?

			Legg’s eyes twinkled, as though the question put him in mind of some familiar private joke. With a touch of theatrical swagger, he faced the room and asked rhetorically, “So, what do we do about this?!”

			He evidently had no answer to offer. All he could do was to repeat the listener’s question.

			Nervous giggles greeted him. The prospect of computers threatening humanity seemed absurd. The absurd is a close cousin of humor.



* * *



			• • •

			Seated at the back of the classroom, Hassabis was less fixated on the surreal threat than on what he had heard beforehand. His impression from that elevator encounter had been confirmed. Legg’s imagination was wide open to the possibility of superhuman AI, and he had the technical tools to help build it. Hassabis was not going to miss the opportunity to bond with the New Zealander this time. He went over and introduced himself.

			Years later, thinking back on the conversation that ensued, Hassabis became emotional.

			“It was amazing to find Shane because it’s like finding an oasis, right? Until then, as far as I knew, I was the only person thinking about these subjects.

			“I mean, there were other people interested in AI, like David Silver, but I’d got them interested. I’m good at galvanizing people, so I can’t take that as an independent measure of whether I’m really on to something.

			“So to find someone who’d had an independent path, who had come to the same conclusion…that was a very powerful corroboration.

			“I’m getting goosebumps thinking about it.”

			I thought about how different Hassabis’s experience might have been in California. In Silicon Valley, change-the-world dreamers were practically normal, and there was a network ready to support you. In London, out-of-the-box ambition was an isolating trait. You had to search to identify collaborators.

			“I’d never read any of Kurzweil,” Hassabis said. “For me, it was Gödel, Escher, Bach, Asimov, Iain Banks, my own practical work with Molyneux, Blade Runner. Those were my influences. I don’t think I even knew who Kurzweil was because I was sort of in my own parochial backwater, just dreaming dreams.

			“But Shane came with all these ideas. He’d studied with Marcus Hutter. He’d done this theoretical proof of intelligence. He was already going to the Singularity Summit. He had coined the term artificial general intelligence. He had all these contacts in the nascent AGI world that I didn’t even know existed.

			“Here was a guy who’d dedicated, independently from me, his entire life to this mission. And that’s why we had both ended up at the Gatsby. Because we were kind of looking for each other. Neither of us knew what the other one would be like. But we were looking.

			“Shane had left New Zealand, worked with Ben Goertzel, done academia. And eventually he came to the Gatsby for the same reason I was there: Because it was one of the only places in the world that was combining neuroscience and machine learning. And so we both must have thought that there had to be interesting, like-minded people there.

			“And it turned out there weren’t that many.

			“But there was one, and that was enough.”



* * *



			• • •

			In the weeks after the Halloween lecture, Hassabis and Legg met regularly for lunch at an Italian restaurant near the Gatsby. They talked about AI, where it was going, how best to pursue it. They agreed that this was an exciting moment. Thanks to Hinton’s deep belief networks, the application of GPU chips to his systems, Legg’s work on measuring intelligence, and Hassabis’s grasp of the AI intuitions that flowed from neuroscience, the field was approaching a watershed. But they differed on what to do about this. Legg still worried that it was too early to start a company: Who on earth would finance a venture with no prospect of delivering a product? Hassabis countered that academia was too slow: To build powerful AI, they would need a team, a sense of urgency, and freedom from academic bureaucracy. A mission-driven start-up—a Manhattan Project, as Hassabis liked to say—could surely be funded by the right sort of investor: a billionaire, or possibly a multibillionaire, with the stomach for the long horizon.

			Inevitably, Hassabis proved to be the more insistent of the two: It was a case of Ender versus not-Ender. On December 29, 2009, shortly before midnight, Legg emailed his new friend to say that he was ready to go forward with an AI start-up. The comrades named their future company DeepMind: It was a nod to deep learning, the school of artificial intelligence pioneered by Geoff Hinton; but also to Deep Blue, the computer that had beaten the world champion at chess; and also to Deep Thought, the supercomputer from The Hitchhiker’s Guide to the Galaxy.

			Having lined up a scientific cofounder, Hassabis still needed some more backup. For this he turned to an unusual figure: a brash and brilliant autodidact who was as driven and energetic as he was.

			If Hassabis and Legg had each had improbable journeys, Mustafa Suleyman’s was even more extraordinary. Born in August 1984, eight years after Hassabis, he, too, had grown up in the melting pot of North London with an immigrant parent and religion in the family. But there the resemblance with Hassabis stopped. Mustafa’s father was a devout Muslim from Syria who spoke broken English and drove a cab, putting in shifts from four in the morning until eight in the evening. His mother was a nurse who had grown up in England and converted to Islam; her work was as grueling as her husband’s. Whereas Hassabis’s bohemian upbringing combined the committed Christianity of his mother with the secular humanism of his father, Suleyman’s parents were united in their faith. There was no music in the home, and no books or newspapers, either.

			The young Mustafa embraced his parents’ religion, and he loved the comradeship that came with it. On Fridays he attended a North London mosque, standing toe-to-toe and shoulder-to-shoulder with polyglot believers: Pakistanis and Bangladeshis, Indonesians and Malaysians, Somalis and Sudanese, Turks and Arabs, “all worshipping together in unity and equality and alignment,” as Suleyman said later.[15] At around the age of twelve, he would go to his school playground to recruit kids with roots in these countries, then he would lead them in prayer. His message stressed the moral obligation to do good. To be raised as a London Muslim in the 1990s was to understand the value of community: Britain was welcoming only up to a point. If Muslims wanted society to be just, they would have to work to make it just. And they would have to work together.

			When Mustafa turned fifteen, the case for community took on a whole new meaning. His parents split up and his mother followed her new partner to New Zealand. His father returned to Syria to remarry, leaving Mustafa in London to fend for himself and his fourteen-year-old brother. The boys had no home to go to, so they found shelter with friends. His father sometimes sent them money, but it was never enough; luckily, Mustafa was resourceful. From the age of eleven, he had bulk-bought candy bars and sold them to schoolmates at a markup, eventually hiring older kids to market to their peers and renting out friends’ lockers to warehouse his inventory. When he turned fifteen and his parents left London, Mustafa moved into buying and selling cell phones. At eighteen he graduated to fixing and trading cars, freshening up classic BMWs and Mercs with the help of his younger brother.

			Hardship did not stop Suleyman from flourishing academically. Identified early on as an outstanding student, he had won a place at one of the best government high schools in Britain, Queen Elizabeth’s School in North London, founded in 1573 by the Protestant nationalist Queen Elizabeth I and dominated, four centuries later, by students of Asian origin. In this high-octane environment, he was among the top academic performers. A sympathetic teacher helped him to develop a passion for reading: She picked out novels, explained the difference between the conservative Telegraph newspaper and the liberal Guardian, and gave him a subscription to The Economist. At seventeen, Mustafa won a national enterprise award for a plan to make London’s tourist attractions accessible to disabled visitors. To document the barriers that a disabled person might face, he borrowed a hospital wheelchair and wheeled himself around the monuments and museums of the city.[16]

			Around this time, Suleyman began to hang out with a new friend—a guy named George Hassabis. He often stayed over at the Hassabis home, borrowing the empty room vacated by George’s older brother, Demis. Since Demis’s days on the chess circuit, the Hassabis parents had built some capital by fixing up houses, and to Mustafa—by now known universally as Moose—their home represented middle-class security. Every Wednesday evening, George, Moose, and Moose’s girlfriend, Marilyn, worked as chess instructors at the education center that the Hassabis parents now ran. One day, Demis showed up for a barbecue in the family’s garden. Already in charge of his own gaming studio, he cut a distant and impressive figure.



* * *



			• • •

			In 2002, his last year at high school, Suleyman was among a handful of classmates admitted to Oxford or Cambridge.[17] Suleyman opted for Oxford, and his chosen field of learning was philosophy and theology. The choice reflected his predicament as a British Muslim. The terrorist attacks of September 2001 had unleashed a wave of Islamophobia, and Suleyman believed in Muslim solidarity more passionately than ever. But he was also gravitating toward a secular vision of Islam, and Oxford pushed that process further. He remained dedicated to social justice, but he doubted the existence of God. He loved the post-racial culture of the mosque, but he rejected the gender inequality and the condemnation of gay people. His freethinking eclecticism was obvious at a glance. He wore pink corduroy trousers held up by suspenders and a traditional flat cap on a head of flowing curls. He smoked a pipe and sported Ellesse sneakers.

			During Suleyman’s first spring at Oxford, the United Kingdom backed America’s invasion of Iraq, and the predicament of a modern-minded British Muslim became all the more excruciating. On the one hand, Suleyman wanted urgently to do something to help his community.[18] On the other hand, he was not going to side with the medieval clerics who had perpetrated the 2001 attacks, nor did he sympathize with Iraq’s brutal dictator. That summer, observing a teenage rite of passage for young Brits, he backpacked around Europe with three non-Muslim friends; while the others honored the true purpose of such journeys, which is to drink, Suleyman joked and played cards and refused to touch alcohol. He had the affect of a carefree undergraduate, and yet he stood apart. His tough London adolescence had felt like real life. Oxford was a bubble.

			Toward the end of his second year at university, Suleyman bumped into one of his friends from that summer trip around Europe. He told the friend that he was done with libraries and books and intellectual abstractions. He was going to drop out of Oxford.

			“I remember being absolutely flabbergasted,” the friend recalled later. Nobody ever dropped out unless they were in a serious mess. Especially for someone from an underprivileged background, Oxford was a magic escalator.

			“I remember thinking, ‘Oh my God, you’ve just ruined your whole life,’ ” the friend went on. “I was like, ‘Hey, you got the golden ticket.’ ”[19]

			I asked Suleyman what he thought about this golden-ticket warning.

			“I always had nothing, so I was fearless when it came to flipping the table. I was like, ‘Why am I studying church patristics when I should be changing the world right now?’ ”[20]

			Quitting Oxford for London in the summer of 2004, Suleyman hopscotched from one job to another. Together with George Hassabis, he started yet another business, this time selling milkshakes at the market in Camden, not far from Elixir’s second office. To satisfy his appetite for social justice, he teamed up with a friend who had founded a nonprofit called the Muslim Youth Helpline, which offered counseling to depressed or confused Muslims. His comrades at the helpline came from what Suleyman described as “chaotic, crazy-ass backgrounds,” some of them even more extreme than his—crushed families, drug addictions, mental demons, to the extent that, a couple of years later, one helpline employee set himself alight in a park in North London.[21] But the helpline provided Suleyman with a chance to come to terms with his identity. It offered a way to be both Muslim and secular, Muslim and modern—in fact, Muslim and British. Around this time, Suleyman completed his separation from his parents’ faith, progressing from agnosticism to a decisive atheism.

			Toward the end of 2009, Suleyman decided that his career needed a reboot. The Muslim Youth Helpline had failed to satisfy his yearning to bring about social change, and two subsequent jobs had not fulfilled him, either. He had worked at the London mayor’s office, hoping to improve society on a larger scale, but had found government work to be bureaucratic. He had cofounded Reos Partners, a conflict resolution consultancy, aspiring to overcome divisions by opening people’s minds, but it turned out that collective therapy seldom dissolved enmities. Searching for a better way to catalyze societal progress, Suleyman’s attention fastened on a more powerful force. He had recently become aware of Facebook, the social network that had sprung out of nowhere, attracting by that point a community of some 132 million monthly users. In its capacity to shape ideas and change societies, the platform dwarfed anything that Suleyman had seen before. If Facebook continued to grow at the same pace, it would soon exceed the cultural heft of Islam or Christianity.

			Pondering these magnitudes, Suleyman made up his mind. If he truly aspired to make an impact on the world, he should become a technologist.



* * *



			• • •

			For a twenty-five-year-old Londoner with no university degree, a future in tech seemed like a stretch. But Suleyman knew of someone who could help: George Hassabis’s brother, Demis.

			Since that fleeting barbecue meeting a few years before, Suleyman had struck up a relationship with the older Hassabis. Demis had exited Elixir with a few million pounds, and in 2007 Suleyman had proposed a business partnership. Hassabis would provide capital; Suleyman would purchase apartments; these would be rented out, and the two would split the proceeds.[22] The partners discussed their plans over a few lunches near University College London, where Hassabis was studying for his PhD, and Suleyman talked about what he was reading. In contrast to Hassabis, who loved books about science, Suleyman devoured volumes on politics, sociology, and complexity theory, logging every title that he went through.

			In December 2007, the two friends met for lunch at a steakhouse, right by the Smithfield meat market where livestock had been slaughtered since the tenth century. There, with the ghosts of medieval London swirling around them, the two twenty-first-century idealists got talking, and Hassabis asked Suleyman about his latest reading. Suleyman reached into his pocket and pulled out a slim volume: Owning Your Own Shadow, by the Jungian analyst Robert A. Johnson.

			The book was about the unlit underbelly of the human ego. It asked readers to understand their shadows: to acknowledge the harsh sides of their personalities and the darkness that they cast on those around them.

			Hassabis said that sounded interesting.

			“Oh, you should take it,” Suleyman offered.

			Hassabis brushed the book aside, saying that this sounded like the sort of thing that Suleyman should be reading.

			Years later, feeling he had been plunged into darkness by Hassabis’s shadow, Suleyman recalled this exchange.

			“The irony of that is ridiculous,” he said, with a grimace.

			“Surreal,” he added, almost shuddering.

			Then he conceded, “I mean, Demis was partly right. It was actually what I needed.” A dozen years later, when Suleyman’s career veered temporarily off track, his own shadow had a lot to do with it.

			I looked across the restaurant table at the success story in front of me. The teenager who had grown up without a home had recently been named the head of AI at Microsoft. Of course he hadn’t pulled off this transformation without wrestling with demons. How could he not have a shadow?

			“Maybe you both needed that book,” I suggested. “Maybe most of us need it.”

			“We all need it,” Suleyman replied. “At least I acknowledged it.”[23]



* * *



			• • •

			When they were not discussing books, Suleyman and Hassabis played poker. Together with Demis’s younger brother, George, they would meet up at the Vic, an iconic casino on the noisy Edgware Road in London. The Poker Room on the second floor stayed open, alarmingly, twenty-four hours per day, and played host to a steady stream of tournaments. Demis would wear a pair of outsized shades that concealed his expression and gave him a badass Blade Runner appearance.

			On July 15, 2010, Suleyman met the Hassabis brothers at the Vic for one of their sessions. George and Moose were soon bounced from the tables, but Demis came in fifth, pocketing almost two thousand dollars.[24] A disappointed George went home, returning to the group house that he shared with Moose and a few others. To celebrate Hassabis’s winnings, Demis and Moose found a restaurant table and ordered chocolate cake and vanilla ice cream.

			Pumped up on dopamine and sugar, Hassabis let Suleyman in on a secret.[25] His performance that evening proved that he could master poker if he tried; but, he confided, he had higher uses for his energy. For the past several months, he had been plotting a stealth AI company, whose mission was not just to invent AI, but rather to go after AGI, artificial general intelligence. Hassabis already had a plan, a brilliant cofounder, and a list of potential collaborators. He just needed an investor.

			Playing off what Suleyman had told him over the course of their lunches—that he wanted to leverage technology to drive social change—Hassabis stated the obvious. If Suleyman was truly interested in improving the world, artificial general intelligence was the best possible vehicle for him. An infinity machine would have infinite potential.

			“We saw technology as a force multiplier,” Hassabis recalled of this discussion. “Charities, consultancies, the London mayor, whatever: You put one unit in, you get one unit out. The goal was to put one unit in and get a million units out. Otherwise, how are you ever going to do enough? That resonated with Mustafa.”

			The way Suleyman remembers it, part of him wondered whether Hassabis’s vision was even remotely realistic. Hassabis liked to talk up his track record building machine learning for games, but the real world was vastly more complicated than any game, and driving societal change was difficult. Economies and societies turned on fights and emotions and who said what to whom. No artificial intelligence, however powerful or general, could comprehend, let alone shape, the billions of potential permutations.

			A vigorous debate ensued between the scientific visionary and the social activist. It was Ender versus Ender this time, and the more the two missionaries challenged each other on the substance, the more they bonded at a deeper level. Both were articulate and forceful, willing to follow ideas to their logical extremes; even when they were at loggerheads, they were nonetheless a pair of kindred spirits. And while their professional experiences were different, they were complementary, too. Hassabis was imagining a technology that would have huge impact on the world. Suleyman had sought to understand how the world needed to be impacted.

			Suleyman could see the opportunity in front of him. Of course, Hassabis’s vision was audacious and his mission might fail. But a voice was whooping inside Suleyman’s head: “Wow! Amazing!”[26]

			Two days later, Suleyman followed up with an email. He congratulated Hassabis on his poker winnings and pointed him toward a Wired magazine profile of Sergey Brin, the cofounder of Google. According to the article, Brin was pouring part of his $15 billion fortune into computational medicine, hoping to drive a revolution in the pace of drug discovery. Perhaps Brin was the sort of billionaire who might fund an AGI company?[27]

			Hassabis emailed back. “Very cool article,” he said approvingly. And then he proposed a collaboration. He was gearing up to pitch a different billionaire at the next Singularity Summit, in August; he had the outline of a business plan, but it needed fleshing out, and the summit was approaching. Might Moose have time to help draft the document?





Chapter 5




				Founding DeepMind

			 			On August 14, 2010, the Singularity Summit got underway in San Francisco. Ben Goertzel, the Baby WebMind promoter, showed up with his resplendent hair, looking, as one observer said, as though he had been blown off course on his way to the Glastonbury Festival. A Canadian inventor named Steve Mann, who described himself as a cyborg, wore a black woolly hat and computer-enhanced eyeglasses. A biophysicist called Gregory Stock proclaimed that “science has slammed the evolutionary process into fast forward.”[1] To associate with this fraternity was to invite ridicule: An earlier summit had been mocked as “the Bay Area coming-out party for the tech-inspired philosophy called transhumanism.”[2] But Shane Legg and Demis Hassabis had eagerly accepted speaking slots. Mustafa Suleyman had come along for the ride. He was sleeping on a couch in Hassabis’s hotel room.

			Hassabis eyed his fellow conference-goers warily. Asked by a journalist if he called himself a “singularitarian,” he responded politely, “Maybe it’s because of my British side, but it’s a bit Californian.”[3]

			The DeepMind trio were out in force because they were desperate for money. In the months since he had persuaded Legg to be his cofounder, Hassabis had rattled his tin at the investors who had backed Elixir. Not one was prepared to back him. An AGI company was too far out: It was both technically daunting and commercially dubious. Hassabis secured a promise of some money from his MIT supervisor, Tomaso Poggio, not least because Poggio’s wife, a psychologist, had told her husband that whatever that electrifying English guy did, they should absolutely back him.[4] But Poggio was good for only £100,000—about $150,000. The closest Hassabis had come to landing a real investor was an eccentric financier named David Gammon. With Suleyman as his new wingman, Hassabis had spent hours courting Gammon over lunches in a London pub. The financier seemed open to making this unusual bet because his motives were themselves unusual.

			“There is a deeply religious aspect to AGI,” Gammon explained to me later. “It’s really finding God’s algorithm.”

			I asked Gammon to elaborate.

			“The architect of the universe is what we may call God,” Gammon answered. He had swept-back hair and the military bearing of an English country gentleman.

			“You know, I believe. I have a very strong faith. I really believe the universe and the world advances. And you have to keep pushing.”[5]

			Hassabis’s main hope at the Singularity Summit lay in another believer, the Catholic contrarian Peter Thiel. By 2010, Thiel was already a legend, famous for founding the original digital payments company, PayPal; the original software-first defense company, Palantir; and for being the earliest investor in Facebook, a bet from which he had already reaped north of a billion dollars. In 2008, a start-up named SpaceX had endured its third consecutive rocket-launch failure. Two days later, Thiel’s Founders Fund swept in, investing $20 million in the company.

			Thiel was also a Singularity enthusiast. A competitive chess player, he had been thrilled when the chess program Deep Blue defeated the reigning human champion, Garry Kasparov. It was only a matter of time, Thiel reasoned, before AI dominated most cognitive tasks at the heart of the information economy.[6] The way he saw things, this could only be a good thing. The world urgently needed technological advance to ward off economic stagnation; indeed, the very survival of the free-market system might depend on an AI breakthrough.[7] Following this line of reasoning, Thiel financed the Singularity gatherings, believing they might generate some wacky but high-potential bets. It would only take a single start-up hit for his investment to pay off multiple times over.

			Hassabis, Legg, and Suleyman showed up at the conference hall at the Hyatt Regency hotel in San Francisco. They scanned the room for Thiel: He was supposed to be scouting for AGI start-ups, and they were desperate to be scouted. But Thiel was nowhere to be seen. Apparently, he had paid for the proceedings but felt no need to attend them. “That’s so strange!” Suleyman remembers thinking.[8]

			Legg knew that at the Singularity Summit the previous year, Thiel had thrown an after-party for the conference speakers. He would do the same this time. That would be the chance to get his attention.

			That evening, the gang of three showed up at Thiel’s home near the Golden Gate Bridge, on the northern tip of the San Francisco Peninsula. Sure enough, Thiel was there, already surrounded by a crowd of supplicants. The interlopers from London felt awkward. “We were standing around sheepishly and wondering how to approach him,” Suleyman remembered. “We were irrelevant nobodies. He was a titan.”[9]

			For the second time that day, Legg’s experience of the Singularity scene proved useful. Through his PhD work and his trip to the Singularity Summit the previous year, he had befriended Eliezer Yudkowsky, one of the high priests of the community. Now Yudkowsky walked Legg and Hassabis over to meet Thiel. “These are some of the smartest guys in the whole field of AI and they’re starting a really ambitious company,” Yudkowsky said.[10]

			Hassabis was ready with his lines. “I was preparing for that meeting for a year,” he said later.[11] Instead of pitching Thiel with yet another start-up story—and doing so in the middle of a crowded party, with thirty seconds in which to blurt above the noise—he hooked Thiel with chess, observing that there was a deep tension between the bishop and the knight, with the two pieces carrying the same value yet possessing vastly different capabilities.[12] Sure enough, this gambit was enough to open up the board. After a brief back-and-forth, Thiel invited Hassabis and Legg over to his home the next day to explain their ambitious venture.

			When the duo showed up to make their pitch, Thiel greeted them in his workout gear; he was still sweating. His butler brought him a Diet Coke. He had a grave expression.[13]

			Hassabis explained his vision for a company that would build powerful AI, drawing on the latest insights from neuroscience and capitalizing on the explosion in computing power.

			“This might be a bit much,” Thiel thought to himself. Still, Eliezer Yudkowsky’s endorsement meant a lot. Thiel had known Yudkowsky for half a dozen years, and DeepMind was the first company that he had recommended.[14]

			Hassabis kept talking. New machine-learning methods were just starting to work. Between them, Hassabis and Legg knew everyone in the field. What’s more, Hassabis had entrepreneurial experience, having built Elixir. He had won the five-game Mind Sports Olympiad on five occasions.

			Thiel began to think this project was A-plus on the science, and maybe F on the business model. But he also had a further thought. Hassabis was an extreme case of what venture capitalists call an “authentic” entrepreneur: not a mercenary who starts with a desire to get rich from a start-up, then casts around for a plausible idea; rather, a missionary who feels compelled to work on a particular challenge, then starts a company as a way of tackling it. The good thing about missionaries is that they never quit: Even if they have to work around the clock and pay themselves nothing, they will keep obsessing about the problem. “I always think that people aren’t really entrepreneurs in the abstract, but there’s maybe one great company that somebody has in them,” Thiel reflected. “It was Demis’s destiny to build this one.”[15]

			Thiel told his visitors to come back in a few weeks to pitch to his partners at Founders Fund. He seemed curious, but wary.



* * *



			• • •

			The DeepMinders returned to London, and Hassabis and Suleyman worked on the last revisions to the business plan. The document ran to some thirty pages, ranging from high-concept futurism to the specific milestones that DeepMind would reach before its next funding round. It explained why artificial general intelligence was necessary; why it would prove possible to build; and why DeepMind’s approach to the challenge was superior to that of its rivals.

			The first part of the plan, on why AGI was necessary, offered a statement of the technology’s power. It quoted Bill Gates: “If you invent a breakthrough in artificial intelligence, so machines can learn, that would be worth ten Microsofts.” The plan combined that statement with a theory of necessity. Society faced problems of unprecedented complexity, from stabilizing capitalism, which had blown up in the financial crisis of 2008, to feeding an expanding population. Progress on these challenges was depressingly limited, reflecting a phenomenon known as the “ingenuity gap”—Suleyman had borrowed this phrase from a book of the same title. As the business plan explained it, the human brain had limited storage capacity; humans had limited lifespans; grouping humans together resulted in diminishing returns because big organizations are sluggish. In sum, the intricacy of society’s most pressing challenges lay beyond the reach of human capabilities.

			“AGI is the solution to this problem,” the plan stated boldly.

			Next, the plan explained why the moment was right for an AGI company. A chart showed the capability of supercomputers exploding upward to 1020 calculations per second by 2025, a hundred thousand times more than at the time of writing. Just as fiber optic cable and high-performance routers had enabled the internet in the 1990s, accelerating semiconductor progress would fuel the AI revolution. Meanwhile advanced imaging technology was making it possible for neuroscientists to peer inside the brain, yielding an increasingly detailed picture of its workings—a picture to which Hassabis’s PhD had contributed. The insights from this scholarship were ignored by the majority of AI developers; with almost sixty thousand neuroscience papers appearing annually, extracting the gems was impossible for nonspecialists. By mining and indeed contributing to this literature, DeepMind would have an advantage.

			“The human brain is composed of a number of distinct parts, each with its own anatomical structure and algorithmic capability,” the business plan explained. “While these components are powerful in isolation, the real genius of the brain lies in the way in which they have been deeply integrated together to produce general intelligence.”[16]

			Perhaps most audaciously, DeepMind asserted that its ultra-ambitious conception of AI made progress more likely. Other AI research sought to maximize the chances of success by focusing on narrow tasks: training a system to recognize images, for example. In contrast, DeepMind was out to build agents, not merely systems, the difference being that agents would be more general and proactive. Rather than being engineered by humans to master a single finite task, agents would learn broadly and autonomously, mastering a wide range of problems as they interacted with their environment. The jump in complexity was vast. Rather than building the digital equivalent of a house, DeepMind aspired to build a city.

			To realize their ambition, Hassabis and his colleagues would have to teach agents complex skills such as a mastery of concepts, the business plan continued. To endow agents with this facility, DeepMind would leverage its expertise in neuroscience, and specifically in research identifying a set of complex interactions in the hippocampus and the prefrontal cortex, which appeared to transform memories into broader abstractions. The challenge of turning intuitions from this literature into a machine-learning architecture was immense, the business plan conceded, but the alternative of ducking the challenge was hopeless. AI systems that merely matched one type of symbol (the image of an apple) with another type of symbol (the word “apple”) were not connecting with the real world: They didn’t really know anything. “In a system that describes symbols solely in terms of other symbols, it is not clear where the meaning resides.” To use a favorite AI expression, such machines could never be truly intelligent because they were not “grounded” in reality.

			Fifteen years later, with the benefit of hindsight, not all DeepMind’s prophecies look accurate. Insights from neuroscience proved useful during DeepMind’s early days, but not after 2015 or so. The question of whether AI systems need to be “grounded” is still hotly debated. Large language models such as ChatGPT or Gemini are not directly taught concepts, yet these systems exhibit an impressive grasp of how the world functions. A feeling for concepts somehow emerges as a by-product of statistical mastery, bypassing DeepMind’s ambition to program conceptual understanding explicitly.

			And yet, despite these debates and details, DeepMind’s road map was prescient. The computational power driving AI models grew almost exactly in line with the business plan’s projection.[17] More to the point, the prediction that it would be possible to build human-level AGI by around the year 2030 seemed outlandish in 2010. But as of 2026, and allowing for the fact that the definition of AGI remains fuzzy, DeepMind’s forecast appears to have been just slightly conservative.



* * *



			• • •

			In September 2010, Hassabis and Suleyman appeared before a strange kind of investment committee. David Gammon, the religious investor, declared himself ready to commit capital, but he would only go forward if DeepMind did things his way. Entrepreneurs seeking his support were required to visit his home in Cambridge and pitch to Gammon, his artist wife, and his three teenage sons. Each family member would get an equal say on whether to invest. “I said to Demis, if you can’t explain this to my youngest son, Cameron, you’re not going to get his vote,” Gammon remembered.

			There was a painfully large gap between the grand science of the DeepMind business plan and an invitation to chat with a middle schooler. But Hassabis and Suleyman complied. If they refused to humor wacky investors, they might not raise any capital at all: Their project was itself wacky. The visit to Cambridge went smoothly; Hassabis won over all five family members. “I couldn’t have got this off the ground without David Gammon,” Hassabis recalled. “But can you imagine going to pitch to a fourteen-year-old? I mean, I’m a serious scientist.”

			A few weeks later, Hassabis and Suleyman returned to California. Gammon was planning to kick in a few hundred thousand pounds, but DeepMind needed a lot more than that. Hassabis remained desperate for Thiel’s money.[18]

			If Gammon was eccentric in a certain way, the world of Peter Thiel felt even more unsettling. As part of the get-to-know-each-other process, Thiel’s lieutenants arranged for the visitors to meet three other Founders Fund start-ups. The most successful was Palantir, the software-first defense contractor that was helping US forces to track terrorist networks. The DeepMind visitors squirmed: To Suleyman, a human-rights-oriented opponent of the Iraq War, a defense contractor was by definition suspect. “I was scared that Palantir was building surveillance apparatus, and that we would be pushed to develop algorithms for it,” Suleyman said later. A second Founders Fund protégé, a military-robotics venture, alarmed Suleyman even more: The first thing you saw when you showed up at its office was a gun mounted on a pair of caterpillar treads. “This was not the vision of AI that we were trying to build,” Suleyman recalled with a shudder.

			The third start-up was disconcerting for a different reason. Named Halcyon Molecular, it embodied the Singularity spirit: Its mission was to extend human lifespans massively by applying AI to medicine. The coming collapse in the cost of gene sequencing would generate reams of genetic data, and the data would be analyzed by powerful AI. Life expectancy would rise in lockstep with Moore’s Law.[19]

			Hassabis and Suleyman were all in favor of ambition, but Halcyon seemed borderline crazy. “We thought it was loopy,” Suleyman recalled. “So capital intensive. So speculative.

			“Part of me was like, that’s brilliant because we are in the same bucket. But part of me was like, who’s making the decisions here?”

			The decision maker, it turned out, was a charming, voluble, midthirties futurist by the name of Luke Nosek. An engineer and friend of Peter Thiel’s since the formation of PayPal, Nosek was another booster and financial backer of the Singularity Summits. He was also the Founders Fund partner responsible for the team’s most far-out wagers, notably SpaceX and Halcyon.

			“I always wanted to bring about a positive singularity for humanity, or at least prevent a negative one,” Nosek told me, his words tumbling out in a torrent of excited energy. But then, abruptly, he turned quiet. The silence went on for a few moments.

			“Sorry, I just lost my train of thought,” he resumed.

			“The singularity is just such an intense concept that that’s what it causes people to do!” he added, now beaming again. “It causes people to lose their ability to think sometimes!

			“I would say if it doesn’t affect you emotionally, and if it doesn’t affect your thinking at all, well then you’re doing something wrong!

			“You’re not truly visualizing how transformative a superhuman intelligence would be!”

			When Hassabis and Suleyman visited Halcyon, Nosek was there to greet them. A year or so earlier, he had assumed the role of company president, declaring, “Of all the Founders Fund companies that have…the potential to change the world—Facebook, SpaceX, Palantir—Halcyon is the one with the chance to do so in the most profound way possible.”[20] But when he got talking with Hassabis, Nosek fell head over heels, again. “It was like a lightning bolt,” he told me.

			“Here was the first person who actually seemed really, really competent, really, really brilliant, and dedicated to building AGI. I had met people before who had the same goal, but I didn’t believe that they could do it.

			“When you are early in a particular technology, it’s probably just not possible to build something with it,” Nosek continued. “And so then you are going to meet people who are just crazy, just dreamers. But when I encountered Demis, it became clear immediately: ‘Oh yes, we should definitely invest! And I need to join the board of this company!’ ”

			Two years earlier, when he had backed SpaceX, Nosek had pulled off the contrarian investment of a lifetime. The company’s value had since shot up more than tenfold, and it was just getting started. Now Nosek saw similarities between SpaceX and DeepMind. Back in 2008, Nosek had grasped SpaceX’s potential by ignoring the apparent craziness of its mission—to build a private rocket company. Instead, he had focused on a shift in the technological backdrop that rendered the hitherto impossible just about conceivable. In the case of SpaceX, the shift was that cheap, off-the-shelf aerospace components had become available, offering a chance to outcompete the government’s NASA space program, which relied on ultra-expensive, bespoke components. In the case of DeepMind, the shift was that algorithmic breakthroughs such as deep learning might unlock the potential of ever more powerful computing. Nosek’s SpaceX wager had also been a statement of faith in its founder, Elon Musk, who was visionary and driven. Likewise, this British computer-scientist-neuroscientist-chess-master guy exuded similar missionary voltage. “His mantra was AGI, AGI, AGI,” Nosek recalled of Hassabis. “And speaking with him almost made your brain break.”[21]

			Nosek had never before pushed to join the board of a start-up outside the United States. Nor would he normally have joined a board in cases where his fund’s potential investment was tiny. But when it came to DeepMind, Nosek was far too excited to follow standard procedures. He was not going to pass up the chance to witness the coming of the singularity.

			“Peter was agnostic about whether we needed a board seat,” Nosek recalled of Thiel. “He was like, ‘Well, we’ll see what happens.’

			“And I said, ‘We’ll see what happens?! What do you mean, we’ll see what happens?!’ ”

			A gap opened up between Thiel and Nosek. As a general matter, Thiel doubted that going on boards was a good use of his partners’ time. Start-ups should be left to sink or swim. The art of venture capital, he liked to say, was to back contrarian ideas, not coach company founders.

			Thiel and his partners also disliked the fact that DeepMind was in London. It was almost an article of faith that any start-up worth backing would be within forty-five minutes of Stanford University; the Founders Fund team joked that investing in Britain was like investing in Somalia. But Nosek respected Hassabis’s argument that London would be the best place for attracting undervalued European talent. If AI worked, the mother of all recruitment battles would break out on the West Coast; meanwhile, under the radar, DeepMind would hoover up the best scientists in Europe. Besides, Nosek could see that if he wanted to get along with Hassabis, he had better let him get his way. Hassabis was a British patriot who bristled at the presumption of American preeminence. “I feel like British culture represents a lot of good values, and I wanted to show that you could build a deep-tech company in Britain,” Hassabis said. “I guess I was rooting for the underdog.”

			If it had not been for Thiel’s contrarianism, the gap between Nosek and the rest of the partnership might have doomed DeepMind. Most venture partnerships decide on investments by voting; if a handful of the partners see hair on the deal, the deal will be rejected. But Thiel had taken the unusual position that collective decision-making should be avoided. The way he saw things, if investments were chosen based on voting, the Founders Fund portfolio would consist of middle-of-the-road start-ups to which nobody objected. Given that all the profits in venture come from a few improbable moon shots, this sort of consensus portfolio would deliver mediocre performance. Following this logic, Thiel had empowered his partners to go with their guts. If Nosek wanted to back DeepMind, he should be allowed to do it.

			Thanks to Peter Thiel’s contrarianism and Luke Nosek’s lightning-bolt infatuation with Hassabis, the die had been cast: DeepMind was in the money.



* * *



			• • •

			In December 2010, Founders Fund wired $2.3 million to DeepMind. For this rather modest investment, Team Thiel assumed ownership of a bit less than half the company.[22] The terms were not so different from the ones that Hassabis had been offered by the hard-drinking London venture capitalists when he had founded Elixir. But this time he couldn’t tell the venture investors to get lost. There was no other capital available.

			The equity split among the gang of three reflected Hassabis’s dominance. He owned nearly as many shares as Founders Fund; more tellingly, he owned a whopping nine times more than Legg, his scientific cofounder. Explaining this lopsided apportionment, Hassabis said, “DeepMind was my idea and I was the driving force behind it.” Besides, Hassabis was ready to work initially without drawing a salary, since he had a cushion from Elixir. He brought CEO experience to DeepMind; and to set the company’s direction, he believed he needed to own as many shares as possible. However much he disliked the idea of dominating others, he was determined to control his quest for superhuman intelligence.

			Legg, for his part, was too laid-back to fight for a bigger portion of the pie. “I figured if DeepMind was going to be successful, then whatever I had was still going to be quite a lot. So it was fine,” he said later.[23]

			Meanwhile Hassabis owned fully fourteen times more shares than Suleyman, the uncredentialed latecomer of the three. But, having been invited in on a temporary basis to help with the drafting of the business plan, Suleyman had worked and negotiated hard enough to earn the title of cofounder.[24] His willingness to sleep on Hassabis’s couch on their visit to San Francisco had signaled what was to come. Suleyman put himself at the center of the action at every opportunity.

			DeepMind opened its first office in an attic on Russell Square, an elegant London landmark laid out during the Napoleonic Wars, when the president of the United States was Thomas Jefferson. The British Museum was just a couple of streets over, and University College London was an easy walk away; Hassabis and his colleagues sometimes went to the Gatsby cafeteria for lunch, hoping to recruit restless researchers. Hassabis warmed to the location for other reasons, too: The London Mathematical Society was next door, and Hassabis liked to imagine that Alan Turing’s spirit was still there, even as DeepMind built on his foundations.[25] If you wandered past the Mathematical Society, you came to a pedestrian crossing where, on a humid morning in September 1933, the Hungarian physicist Leo Szilard had conceived the idea of a nuclear chain reaction.

			Hassabis recalled that chain-reaction scene from the opening pages of The Making of the Atomic Bomb, a classic history of the Manhattan Project. “I used to think about Szilard quite a lot,” he told me.

			“Obviously, we are building AGI to be positive in the world, but AGI is definitely momentous in the same way that the bomb was.”

			I recalled that Szilard was one of the few nuclear physicists of the 1930s to anticipate that his specialty would empower humankind to destroy itself.[26] The rarity of Szilard’s foresight distinguished the bomb from artificial intelligence. In the case of AI, worries of human annihilation were commonplace among the pioneers, not least because the pioneers were steeped in the story of Los Alamos.[27]

			“I would think about the stakes as I crossed the road,” Hassabis went on. “Even though our office was a tiny attic, we were working on something pretty significant.”

			I said I was struck by Hassabis’s memory for stories, and his capacity to see himself in them.

			“Look, I have a very vivid imagination,” Hassabis answered. “That’s why I studied imagination for my PhD. I can imagine people in situations and viscerally empathize with how it must have felt. It’s something I just do naturally.

			“When I was at Cambridge, I used to get a late-night kebab from a van in Market Square. And at one or two in the morning, Cambridge is peaceful, and I walked down King’s Parade, thinking of all the incredible people who had walked down that street, that same exact street, probably looking pretty much as I saw it, because the university buildings and the cobblestones had been there for centuries.

			“Isaac Newton, Alan Turing, all my heroes. I could feel them in the bones of the stone, their intellect and vision. They were almost calling out to me.”

			“And Russell Square had a little bit of that character?” I wondered.

			“Yes. Because I could feel Szilard.

			“It’s like visiting a Buddhist school, where the monks have meditated and prayed for hundreds of years and their efforts are layered on top of each other and together they have left a residue in the rocks, so that there is a sort of physicality around you. Cambridge is definitely like that, and to a certain extent, Russell Square is, too.

			“And maybe we’ve added our own little piece to the charm of Russell Square,” Hassabis concluded.

			Of course, when he opened his office at the end of 2010, Hassabis had yet to make history. All he had was a room for some desks, another for meetings, an area that could be fitted out as a kitchen, and a large closet for the computer servers. His challenge was to populate those desks with the world’s most talented people.

			For the first several months, hiring topflight scientists to DeepMind proved as hard as raising capital. Recruits needed to believe in the possibility of AGI; that ruled out most academic researchers.[28] But recruits had to be credentialed too: The eccentric Singularitarians had ample belief, but Hassabis was not about to staff his Manhattan Project with a crew of flaky dreamers. To the contrary, he aspired to hire PhD scientists in the mold of David Silver; indeed, the DeepMind business plan had listed Silver as a core member of the founding research group. But although Silver had returned from Canada to a prestigious postdoctoral fellowship at University College London, he had still not forgotten the trauma of Elixir. The most he would offer DeepMind was some part-time consulting, and when Hassabis compensated him with a grant of DeepMind shares, Silver had a neuralgic reaction. Feeling that his independence might somehow be compromised, Silver insisted on giving the shares back. The decision would cost him a small fortune.[29]

			Hassabis also tried to hire Ilya Sutskever, a Geoff Hinton protégé and later a cofounder of DeepMind’s archrival, OpenAI. Sutskever was an exceptional talent, and a messianic believer in deep learning. Hinton regarded him as the only one of his students who had more good ideas than he had. But even though Hassabis stretched DeepMind’s pay scale in an attempt to get Sutskever on board, he could not offer him enough to be persuasive.[30] Part of the trouble was that nobody believed in the future value of DeepMind stock. Hinton and the other prestigious figures in the field presumed that a research team with no revenues would do interesting science for a couple of years and then go out of business.

			To boost the chances that top postdocs might risk signing on, Hassabis hit on a new strategy. He offered stipends to leading AI professors, recruiting them as senior advisers in the hope that they would encourage their disciples to see DeepMind as a worthwhile prospect. But even this strategy proved fraught. Geoff Hinton was happy to accept an advisory position: Having met Hassabis at MIT, Hinton realized he was a force of nature.[31] Rich Sutton, David Silver’s PhD adviser and the academic father of reinforcement learning, also accepted a DeepMind affiliation. But when Hassabis attempted to recruit Yann LeCun, a distinguished AI pioneer at New York University, LeCun kept his distance. “Frankly, my original opinion before meeting Demis was, this is yet another company that claims AGI is just around the corner and it’s complete BS,” LeCun said bluntly.[32]

			In the first half year of DeepMind’s existence, the sole PhD scientist to sign on full time was Dharshan Kumaran, Hassabis’s childhood chess friend and later his collaborator at University College London.[33] Kumaran’s credentials as a neuroscientist were impeccable, but a neuroscientist was not going to be the person to build machine intelligence. Then, in September 2011, DeepMind’s fortunes turned. An ebullient Dutch computer scientist named Daan Wierstra became the first AI expert to take the risk of joining the three founders.

			A close friend of Shane Legg’s from graduate school, Wierstra shared the enthusiasm for neuroscience-inspired AI that animated Legg and Hassabis. His life as a postdoctoral researcher in Switzerland was comfortable and well paid, but he chafed at the way that academics thought small, and he disliked their tendency to regard colleagues as rivals rather than teammates. The prospect of joining a mission-driven start-up excited Wierstra so profoundly that he accepted a significant pay cut.[34] Of course, he also received stock. But he assumed it would be worthless.[35]

			During his first weeks in London, Wierstra wondered what on earth he had been thinking. By now Hassabis had hired a handful of engineers from the video game world, but the office still felt empty. “There was no furniture, a few boxes lying around,” Wierstra recalled; in order to keep his spirits up, he set about filling the dead space with his own energy. He persuaded colleagues to embrace a convention known as Formal Thursday: DeepMind’s jeans-and-sneakers gang would dress up in suits, inverting Casual Friday. Unsuspecting job candidates who showed up for interviews confronted a sartorial sensibility that looked like something out of Turing’s time. “We had to tell them, ‘It’s a joke! Really a joke!’ ” Wierstra remembered.[36] Meanwhile, Wierstra took to showing up in the office and announcing cheerily, “Let’s build Terminators.” Eventually Hassabis took him aside and asked him not to alarm people.



* * *



			• • •

			In December 2011, DeepMind raised a second round of capital from Founders Fund. This time Thiel’s outfit kicked in $7.9 million, and the Skype cofounder Jaan Tallinn provided a further $2 million or so. Extending the pattern of DeepMind’s earlier backers, Tallinn’s motives for investing were not conventional or commercial. DeepMind’s mission was insanely dangerous, in his view. He invested in order to press for safety.

			Hassabis kept Tallinn at arm’s length and carried on hiring. By now he was not merely recruiting talent; he was building a platform on which talent could flourish. This involved drawing on ideas that he had been marinating since Cambridge. In most entrepreneurial ventures, the goal is to turn a known technology into a product: This is an engineering challenge. At a deep-tech start-up such as DeepMind, the goal is to invent the technology itself: This is a scientific challenge. Scientific start-ups are harder and riskier than engineering ones, because you can’t be sure that success is even possible. Before Apollo 11 landed on the moon, nobody could be certain that a moon landing could be pulled off; after Apollo 11, imitators benefited from the proof that such landings were doable. And because scientific start-ups are pushing the frontiers, they must be staffed and structured in a special way. At engineering outfits, you need pragmatic problem solvers who will do anything to get a specific product built. At scientific start-ups, you need blue-sky thinkers who wander the unknown—although you also need somehow to direct those wanderings.

			Hassabis had three ideas on what the DeepMind platform needed. The first was conviction. Nobody could say how AGI was going to be built. But Hassabis insisted that it could be built; the existence of the human brain proved that general intelligence was possible. Moreover, Hassabis understood that his sense of conviction had to permeate his research team—otherwise morale would flag and nobody would achieve anything. In the early days of DeepMind, when prestigious figures such as Yann LeCun derided AGI ambition as crazy, every scientist at the company needed to have faith AGI was possible.

			“We only wanted hardcore believers,” Shane Legg remembered.

			“We would go to conferences and tell people, ‘We are starting an AGI company and we are trying to build real AI systems with general intelligence.’

			“Eighty percent of people would roll their eyes at us. I mean, literally roll their eyes and turn around and walk away. We figured that this was a very efficient way to discover who we should be talking to.”[37]

			The second thing DeepMind needed was time. Venture investors’ patience is finite, but the vistas of science stretch into the future unpredictably. With this in mind, Hassabis set out to extend DeepMind’s research runway by generating revenues from side projects. In 2011, he assigned a small team to come up with a commercial video game. In early 2012, he revived his old ideas on recommendation algorithms. By now, deep-learning systems were starting to recognize images, and Suleyman took the lead on hiring a team to apply this technology to fashion retailing. A shopper could input an image of a dress, then get back recommendations for dresses with similar shapes, patterns, colors, and styles. It was a way of searching for visual ideas without summoning the words to describe them.

			The third thing that DeepMind needed was a culture that brought out the best from its scientists. With his habit of collecting ideas from everywhere—movies, books, chance acquaintances in the university bar—Hassabis understood instinctively how to find the special quality in each team member. “He just sees it. He talks to each person at the right level. He knows immediately what’s good about each individual,” Wierstra marveled.[38] To imprint this magpie facility on his fledgling firm, Hassabis hired a cadre of program managers—“glue people,” as they were sometimes called—whose job was to nurture the talent, compensating for social deficiencies. Brilliant researchers might be incapable of administrative coordination, of oral communication, or even of looking colleagues in the eye. DeepMind would be a place where such shortcomings were irrelevant.

			“Look, we have people who are so socially awkward that they lock themselves up in the bathroom for hours on end,” Wierstra explained. “But then they come out of that bathroom with a brilliant insight.

			“If you can find these people and be gentle to them and mother them, you get something great which other companies are missing.”

			I remarked that the researchers were almost all men; that the mothering program managers were often women; and that the resulting gender dynamic troubled some of Wierstra’s colleagues.[39]

			“They’re all men, but many are very awkward men,” Wierstra responded. “So yeah, I’m sure it felt uncomfortable to some people. On the other hand, these men had felt uncomfortable about themselves all their lives. And we created an institution for them to thrive in.

			“There’s a law of comparative advantage. You don’t have to struggle with your social skills. You shine at what you’re good at.”[40]

			Bit by bit, the Russell Square premises filled, then overfilled. The conference room became an overflow desk space, with people staring silently at terminals—Helen King, the first project manager to join DeepMind, recalls that the hush was so intense that she could hear the water clicking through the ancient heating pipes. To preserve this library environment, phone calls and company meetings were shifted out into the garden square. When the weather was bad, the DeepMinders did phone calls from the closet with the computer servers, or from the rickety stairwell, which involved tolerating colleagues who clambered past on their way to the company’s sole bathroom. Trevor Back, a newly minted PhD in computational astrophysics who worked on the fashion-recommendation project, recalls interviewing job applicants one after another with the servers whirring by his head. Every hour or so he would emerge, rush out into the square, gulp down some air, and hurry back inside again.[41]

			In September 2012, DeepMind finally outgrew the Russell Square office and moved into a nearby space on Bernard Street. Almost two years had passed since the first fundraising, and DeepMind was on its way. Now it had to demonstrate that it could build something exciting.





Chapter 6




				Atari

			 			By the fall of 2012, when DeepMind acquired its new office, the energy in the AI world had shifted decisively. The futuristic Singularity Summits had been pushed off to the sidelines, and a series of projects from Geoffrey Hinton’s Toronto lab were capturing the field’s attention. Starting in 2010, speech recognition systems began to work, and in October 2012 a soft-spoken Hinton protégé named Alex Krizhevsky showed up at a conference in Italy and announced something astonishing. Working from his bedroom at his parents’ home, Krizhevsky had trained a deep-learning system that smashed all previous records in computer vision: In a competition called ImageNet, devised by the pioneering Stanford computer scientist Fei-Fei Li, his model was nearly twice as accurate as the next one.[1] Hinton immediately formed a company with Krizhevsky and his charismatic collaborator, Ilya Sutskever. Such was the excitement that, after just two months, the trio sold their outfit, consisting of nothing but themselves, to Google for $44 million.

			Hassabis had seen this coming. As an undergraduate in the mid-1990s, he had understood the shortcomings of symbolic systems that were limited to deduction. Real AI—a computer that could understand messy phenomena such as images or speech—would have to learn by generalizing from copious examples: It would have to think inductively. Back then, as a student, Hassabis could not imagine how such an inductive system would work. The foundations of deep learning had already been laid, but their significance was still unclear: The world’s largest computers were puny relative to human brains, and there was too little data to train models on. But by 2010, one of the premises for DeepMind, and indeed its name, was that deep learning was on the cusp of a breakthrough. With ImageNet, Hassabis was vindicated.

			Hassabis did not merely anticipate Hinton’s success. He had a strategy to surpass it. As he had stressed in his business plan, the road to AGI would involve more than just replicating the various components of the human brain; the components would have to be integrated. The progress in image recognition was therefore just one piece of the puzzle. The larger challenge was to combine deep learning, which would solve challenges such as computer vision, with reinforcement learning, which would deliver other facets of intelligence, including the ability to hatch plans and think strategically. To deliver on this premise, the business plan promised a “Deep Learning Agent” that would master games without being told what the rules were. This sort of model would experiment with millions of possible actions, observe their consequences, and discover what worked. By dint of trial and error, it would induce successful strategies.



* * *



			• • •

			At the time of the ImageNet breakthrough, DeepMind was courting an AI scientist named Vlad Mnih, a Ukrainian-born Canadian who would be key to the company’s ambitions. Mnih was another soft-spoken Hinton protégé: He had a handsome, brooding presence, like a moody hero in a Russian novel. But although he was a Hintonite, Mnih was less tribal than many of his colleagues. For the most part, Hinton’s deep-learning group in Toronto barely communicated with the premier center for reinforcement learning at the University of Alberta, where David Silver did his PhD. Mnih was an exception. After taking undergraduate classes from Hinton, he had completed a master’s degree in Alberta before returning to Toronto for his doctorate. Steeped in the teachings of both deep learners and reinforcement learners, Mnih wanted to blend the two techniques. He regarded the failure to combine them as a huge missed opportunity.

			In Toronto, Hinton would say of deep neural networks, “This is how the brain works.” In Alberta, Richard Sutton, the luminary of reinforcement learning, would say of RL agents, “This is how the mind works.” The two professors had similar ambitions, and each had discovered a promising approach. “When you hear things like that, it’s like, ‘Why aren’t you guys working together?’ ” Mnih said.[2]

			There were reasons for the Toronto–Alberta division. The reinforcement learners loved developing mathematical proofs showing that their systems worked in theory, even if they were difficult to build in practice. The deep learners were the opposite: They loved building systems that worked in practice, even if there was no elegant theory to explain them. A deep neural network was a mysterious black box: impressive when measured by its outward results, opaque when it came to its internal functioning.

			Alex Krizhevsky’s winning ImageNet entry illustrated this paradox. The software encoded millions of connected decision-making centers known as artificial “neurons.” Every time the system was shown a photograph, the neurons in the first layer processed the pixels, looking for the simplest visual cues—edges, lines, patches of color—much as the human eye begins by noticing contrasts of light and dark. The next layer of the neural network pieced these fragments together into more meaningful shapes: curves, circles, textures. Further into the network, neurons began to pick out recognizable parts of an object—the outline of a paw, for example. Finally, the deepest layers of the system assembled these parts and identified the image: cat, dog, and so forth.

			The key was to make the neurons work together. When the system was shown an image, each neuron in the first layer took in pixels and turned them into numbers, much as David Levy’s program had done for chess pieces. The neurons multiplied the numbers by a variable known as a “weight,” added in another variable known as a “bias,” and then fed the result through a mathematical filter that determined what sort of signal to send to the next layer of neurons. Each layer of the network repeated this process, until eventually the final layer spat out the name of the object in the photograph. If the system got the name wrong, it would adjust the weights and biases in its neurons: With around sixty million of these “parameters” to play with, it nudged them iteratively this way and that, eventually landing on the magic combination of settings that allowed it to match inputs (photos) correctly with outputs (words). These parameters, once discovered, amounted to an algorithm that cracked the challenge of vision. They made sense of the patterns in an infinity of pixels. A primitive version of an infinity machine had been willed into existence.

			As a practical matter, Krizhevsky’s program performed splendidly. But its precise mechanisms were obscure. At no point during the training had a programmer provided the system with rules—a cat has four legs and a tail, and so forth. Instead, the model had iterated its own way to the right combination of parameters. A human observer could not tell why any given weight or bias had settled at a particular value, and the complex interactions among the millions of variables defied human understanding. Tweaking a weight in one layer of the system would change the signal transmitted to the next, and the ripples would flow through multiple layers, with nonlinear effects that boggled the imagination. Because of the black-box nature of these networks, the scientists who built them often sounded like surprised parents. Look, my child can say so many more words than just a week ago! As with a toddler who acquires language by listening to an adult’s voice, the internal workings of a deep-learning system were impossible to fathom. But the system’s performance was a strong sign of intelligence.[3]

			One day when Mnih was a graduate student in Alberta, he asked his supervisor, a reinforcement-learning theoretician named Csaba Szepesvári, why he did not take advantage of the advances in neural networks. Hinton had recently published his landmark 2006 paper on deep belief networks. Surely, Mnih urged Szepesvári, this was exciting stuff. For anybody working on AI, new opportunities beckoned.

			“I know that in practice neural nets work,” Szepesvári confessed. “I just can’t prove anything about them, so I don’t use them.”[4]

			Mnih might have been tempted to dismiss the reinforcement learners as a blinkered bunch, except that they were plainly on to something. Deep learning took you only so far: It could recognize patterns and make sense of data, but it could not create agents that interacted with their environments. This set a limit on what deep learning could achieve, since much human learning occurs through trial and error. By dropping an object, a child learns about gravity. By saying “please” and getting what she wants, she learns the value of good manners. Reinforcement learning equips machines to do the same: to act, and to learn by acting.

			Unlike deep learning, which involved layered neural networks, reinforcement learning was a conceptual framework rather than a computational architecture. RL researchers described their systems in general terms. Like David Levy’s chess system, an agent would require a “value function,” which estimated the rewards that would accrue from a particular environmental state. It would require a “policy,” meaning a way of deciding what to do next. It might also be equipped with a “model,” allowing it to predict how the environment would change based on its actions. The computational methods that would give life to these abstractions were sometimes left unspecified, and might be crude: The “policy” could be as simple as a lookup table showing what action to take in any given state, for example. But all these elements of reinforcement learning were designed to achieve one thing. Complex environments allow for an infinity of possible actions; to learn by trial and error, the system needs a way of knowing which actions are worth trying. In order to tame infinity, in other words, an infinity machine has to develop algorithms that narrow the search for the best action.

			Relative to deep learning, with its mind-boggling nonlinearities and impressive practical results, reinforcement learning seemed theoretical and primitive. But to Mnih and other believers in RL, the promise of agents that could learn from experience remained thrilling. Whereas deep learning depended on the availability of training data—human-labeled cat photos, for example—reinforcement learning held out the hope that an AI could collect its own data by acting in the world and observing the consequences of its actions. In principle, there was no limit to the scope of such actions. An RL system could learn anything.



* * *



			• • •

			Completing his master’s degree in Alberta in 2008, Mnih returned to Toronto, joining Hinton’s group and occupying a desk in a converted supply closet.[5] There he encountered the mirror image of Csaba Szepesvári’s reluctance to engage with the other tribe’s methods.

			“What do you want to work on?” Hinton asked his new PhD student.

			Mnih responded that he wanted to combine reinforcement learning with deep learning.

			“I’ve tried that. It doesn’t work,” Hinton counseled him.

			Mnih mentioned his ambition to a few other colleagues. One deep learner after another urged him to drop it. “Once you become a reinforcement learning researcher, it’s a separate community and we’ll never hear from you again,” he was told firmly.

			Chastened, Mnih spent his PhD years building deep-learning programs to interpret satellite images: It was a classic Hintonite project. His models took in the pixels, detecting edges and colors, and gradually learned to recognize objects in the photographs—industrial buildings, oil tankers, signs of deforestation. The systems worked impressively, and Hinton suggested that the two of them should start a company together. But Mnih hated the idea of pitching investors.

			In the summer of 2012, Mnih presented his PhD findings at an AI conference in Scotland. The conference was dominated by sober projects like his; futuristic schemes to build artificial general intelligence were nowhere on the agenda. But at the reception the first evening, the tone suddenly shifted. Two conference participants showed up at the party and announced that they were building AGI. They had a start-up in London. They were looking for recruits who believed in the mission.

			Mnih’s first thought was that this pair sounded crazy. Hinton had warned his students to steer clear of overexcitable Singularity types, with their goofy, let’s-build-Terminators mindset. This AGI duo, who introduced themselves as Shane Legg and Daan Wierstra, appeared to fit that profile.[6] But, as it happened, Mnih had an older brother named Andriy, who was also an AI scientist. Andriy had done a stint as a postdoc at University College London, where he had met Shane Legg. Now he assured Vlad that these AGI promoters were not as sketchy as they seemed. They talked AGI, but they were also real scientists.

			The younger Mnih agreed to have coffee with Legg and the Terminator-building Wierstra.

			What do you want to work on, the DeepMinders asked him?

			Mnih gave the answer that usually got him a disdainful look: “I want to try combining neural nets with reinforcement learning.”

			“That’s what we’re doing!” the pair answered delightedly. In Switzerland, where Legg and Wierstra had done their PhDs, combining the two approaches was actually encouraged. Besides, neuroscience strongly suggested that reinforcement learning would be a necessary complement to deep learning. After all, the reward signals in reinforcement learning resembled the dopamine signals in the human brain. If the brain was the template for artificial general intelligence, RL would be indispensable to building it.[7]

			Mnih began to think that these crazy guys might know something. He had bounced between Toronto and Alberta trying to combine his two research passions. Perhaps he should bounce himself to London.

			Besides, Mnih realized, the ambition to build AGI might sound hubristic, but it came with an advantage. In his experience, the culture of academia could be both boringly cautious and terrifyingly competitive: boring because it pursued incremental advances, terrifying because scientists cut each other’s throats to be the first to publish. Legg and Wierstra were promising the opposite experience: the thrilling pursuit of the big leap, and the near absence of rivals. “They were like, yeah, we are going to do stuff where there is no competition because no one thinks it’s possible,” Mnih recalled. “And if it works it will be massive.”[8]

			A few weeks later, Mnih was invited to a video interview with Hassabis. In advance of the conversation, Hassabis sent over a link to his Wikipedia page. Reading it, Mnih discovered that Hassabis had been a chess prodigy, a superstar video game designer, and the five-time winner of the Mind Sports Olympiad. Now he felt intimidated.

			Mnih dialed into the video call, unsure what to expect. Almost immediately, he was captivated. For one thing, Hassabis was surprisingly approachable. “I remember being struck by how humble he was and how easy it was to connect,” Mnih said later. For another, Mnih found Hassabis’s neuroscience perspective refreshing. “If you’re entrenched in academic computer science, you’re going to be thinking about the next practical step. But if you come at it from neuroscience, you understand the end point of intelligence.”[9]

			Mnih also recognized in Hassabis that contagious conviction, a quality he had learned to appreciate during his time with the deep learners in Toronto. Precisely because there was no theoretical proof that neural nets would work, it mattered enormously that charismatic lab mates like Hinton and Sutskever insisted that they absolutely would work: confidence substituted for theory. Similarly, Hassabis had evidently been determined to pursue AI since his teen years: He was utterly committed to the mission. “It’s this thing, you have to believe,” Mnih reflected.

			I recalled a line from the Life Story movie, which had inspired Hassabis to apply to Cambridge. “I’m one of the believers,” says Watson, the codiscoverer of DNA. “Blessed are they who believed before there was any evidence.”

			Mnih fully expected that DeepMind would go the way of most start-ups and soon be out of business. But by the end of the video call with Hassabis, he had decided to join anyway.

			“I remember talking to Demis and being like, ‘You know what? I am really a scientist,’ ” Mnih said. “This guy, he’s so passionate about building his company, raising money, doing whatever it takes. I just want to go and work for him.” If Mnih passed up this opportunity and took a postdoc appointment at a university, he would be stuck in the academic peloton, frustratingly boxed in. If he joined these out-of-the-box characters at DeepMind, he would be speeding down a road that stretched all the way to the frontier, and nobody would jostle him.



* * *



			• • •

			Mnih packed up his life in Toronto and moved to London in May 2013, joining a steadily expanding research team at DeepMind’s new office on Bernard Street. The day he began, David Silver also became a full-time employee, overcoming his inhibitions after finding that the hours he spent with kindred spirits at DeepMind were more rewarding than the ones spent at his university laboratory.[10] Silver had by now established himself as an authority on reinforcement learning, but the other newcomers at Bernard Street demonstrated DeepMind’s commitment to intellectual diversity.[11] Two recruits worked on statistical methods for quantifying uncertainty and incorporating probabilities into models.[12] Two had worked on deep learning at New York University under Yann LeCun.[13] Others, including Wierstra, were focused on the intersection between artificial intelligence and human intelligence. A computational psychologist named Chris Summerfield had signed on, working alongside Dharshan Kumaran, in DeepMind’s fledgling neuroscience unit. For decades, disparate computer scientists, statisticians, psychologists, neuroscientists, physicists, and biologists had experimented with AI: The field was so balkanized that it barely existed. Now, at last, DeepMind was unifying it.

			By the time Mnih arrived in London, DeepMind’s eclecticism seemed somewhat contrarian. The excitement about neural networks had intensified further: Without drawing from other branches of AI, deep learning seemed poised to deliver progress on tasks ranging from medical diagnostics to translation.[14] But DeepMind stuck to its interdisciplinary vision. Whatever the progress in deep learning, the approach essentially promised systems that matched one thing onto another—speech to text, images to text, and so forth. With its emphasis on agentic and general intelligence, DeepMind aspired to something more: an agent that could make plans and achieve goals in multiple environments.[15]

			The question was, what sort of environments? Shane Legg, whose doctoral work had defined intelligence, took the position that DeepMind should build its own metrics to gauge the progress of its agents. Hassabis, who shouldered the burden of fundraising, believed that DeepMind’s advances would appear more credible if measured against an external yardstick. David Silver agreed with Hassabis’s view. DeepMind should not be both the test-setter and the test-taker. External yardsticks were better.[16]

			Not long after Mnih arrived, the DeepMind team resolved this argument. They hit on the perfect environment for testing an agent: the suite of video games designed in the 1970s and 1980s by the pioneering company Atari.[17] Given the primitive state of video graphics in that era, the computing power required to crack Atari would be affordable. Given that Atari had released dozens of games, an agent would have plenty of opportunities to prove it could be general. And given that most Atari games featured a constantly updating score, the agent would have the feedback it needed to learn how to play better. Besides, as Hassabis noted, DeepMind’s potential investors had grown up playing Atari favorites such as Space Invaders and Breakout.[18] An AI system that mastered these classics would be instantly appealing.

			The DeepMind brain trust divided into teams, each pursuing a distinct approach to the Atari challenge. Unlike in symbolic programming, there would be no human guidance on how to win a point, how not to lose a life, or what losing a life even signified. The AI system would get only the raw pixels on the screen, a joystick with which to move the cursor, and a running tally of the score. Like a human gamer trying out a fresh release, it would process the pixels, experiment with the joystick, and develop strategies through trial and error.

			At first, several methods showed promise. One researcher tried breaking a game into its constituent tasks and designing a separate algorithm to deal with each of them.[19] This worked reasonably well, but handcrafted algorithms for dealing with specific tasks could not generalize to multiple Atari environments. DeepMind’s probabilistic duo took a different tack, creating a reinforcement-learning agent that began with a model of how the games worked, then increased its confidence if trial-and-error play confirmed its hypothesis. This second experiment also yielded progress; but when the feedback indicated that the initial model was wrong, the system misfired as it tried to generate a new hypothesis.[20] A third team adopted a similar approach, but rather than providing its reinforcement-learning agent with a brittle probabilistic model, it equipped it with a more flexible neural network. To begin with, this group consisted of Vlad Mnih and Koray Kavukcuoglu, a Turkish alumnus of Yann LeCun’s group in New York who would later become DeepMind’s research director. Later, David Silver joined, adding advice on reinforcement learning.

			Mnih set about training a deep-learning system to interpret the raw pixels on the Atari video screen, providing the agent with a perceptual input. Then he bolted on an established reinforcement-learning approach known as Q-learning—the Q stood for “quality.” The idea was that, by playing randomly, the agent would learn the quality of any action in any given state of the game: If you move the cursor left when the ball is heading to the left side of the screen, paddle and ball will connect and you may get a point, meaning that this state-action pair has a positive Q-value. Over millions of training runs, the agent would try out multiple possible actions in myriad game-states, recording each result in a database known as a Q-table. In theory, if the system tried out every possible configuration, it would fill out every square in the table and its training would be done. It would know the highest-quality action in every conceivable state of the game. It would play at superhuman level.

			Of course, trying out every possible permutation would have taken decades. To shortcut the challenge—to solve the problem of induction—Mnih added in some more deep learning. As the agent collected experiences, each one consisting of the state of the game, the action taken, and the reward that resulted, these were fed into a neural network. The network then performed the sort of learning exercise at which it excelled. Just as image-recognition systems examined labeled cat photos, eventually learning to recognize an unlabeled cat, so Mnih’s system examined images of state-action pairs that were labeled as having won a point, eventually inducing which other state-action pairs would win points. The trial-and-error marathon needed to fill out the Q-table was dramatically shortened.

			Mnih also confronted a challenge that hearkened back to Hinton’s reservations about combining reinforcement learning and deep learning. A basic RL agent will often gather similar experiences as it explores one part of its environment: Think of a game-playing agent experiencing one section of a maze, for example. In standard deep learning, in contrast, the system starts with a full plate of curated data—labeled photos, for example. It then studies a random sample of these photos, representing the full variety of images in the set. The randomness is crucial.

			To see why this is so, imagine an image-recognition system that receives an ordered stack of photos. All the cat photos are on the top, then there are trees, then dogs, then lions, and so forth. Next, consider three scenarios.

			In the first scenario, the system studies the photos in order. The first batch consists entirely of cats, so the model concludes that all images should be labeled cat, irrespective of their content. Early impressions count: Once the system becomes convinced of its cats-always view, it has difficulty shedding it. By studying a subset of the photos without randomizing the selection, the system has landed itself in trouble.

			In the second scenario, the ordered stack of training photos is shuffled just slightly. The first batch now shows a mixture of cats and trees, so the model performs better. But only marginally better. It learns that photos showing branches should not be labeled cat. But it still concludes that all pictures with eyes, feet, or a tail deserve the cat label.

			The only way the system can succeed is with the third scenario: The ordered stack of photos is thoroughly shuffled. Now the AI is exposed to every variety of not-cat: dogs, lions, furry blankets, and so forth. The diversity allows the AI to understand what distinguishes cats from other objects.

			Mnih pondered how to save his Atari agent from getting caught in the first and second scenarios. As the agent collected experiences, it went through periods when it was stuck in one corner of the Atari board, generating a run of state-action-reward data that captured only a microcosm of the game’s possibilities. If the agent tried to learn from these unrandomized and unrepresentative experiences, it would never master Atari.

			To get around this obstacle, David Silver proposed a new riff on an old idea in reinforcement learning. Back in the 1990s, RL scientists had experimented with a technique called memory replay: To extract maximum learning from limited data, experiences were stored in a buffer and the agent learned from them repeatedly.[21] Silver now suggested that memory replay might be useful in a different way. Rather than learning from experiences as they came in, the agent would store them in its memory for a while, then sample from them randomly.

			Silver’s idea appealed to Hassabis. During his PhD work, Hassabis had studied how humans store memories in the hippocampus, then replay them during sleep, so that salient events are gradually lodged in the neocortex.[22] Silver was proposing something analogous for the Atari system.

			Mnih liked Silver’s idea for a different reason. From the start of the Atari project, he and Koray Kavukcuoglu had aimed to bridge the Alberta–Toronto divide by turning data from reinforcement learning into something that deep learning could handle. Storing game experiences in a memory buffer would allow the neural network to take samples at random, avoiding the learn-as-you-go mode that caused deep learning to malfunction. To Silver, the memory buffer built on ideas in reinforcement learning. To Hassabis and DeepMind’s neuroscientists, the buffer was playing the part of the hippocampus. To Mnih and Kavukcuoglu, the goal was to turn correlated game-playing experiences into the sort of randomized teaching materials required for deep learning.[23]

			Memory replay soon boosted the performance of Mnih’s systems, and whichever way you looked at it, the success marked an inflection point. Silver’s vision had been vindicated: Since completing his PhD, his goal had been to prove that an RL agent could learn successfully from raw data.[24] Hassabis’s vision had been vindicated, too: Breakthroughs in artificial intelligence did indeed mimic the interactions between segments of the human brain. Mnih’s long-standing ambition had also been realized: The disparate traditions of Alberta and Toronto were being fused together.



* * *



			• • •

			On Sunday July 7, 2013, Mnih sat at home in his London apartment, watching the Wimbledon men’s tennis final. “I was so nervous, I almost couldn’t watch,” Mnih remembered vividly. He loved the British underdog, Andy Murray, and winced every time his opponent, the top-seeded Novak Djokovic, took a point off him. “In Wimbledon finals, every point matters,” Mnih recalled in an intense voice. “I often have to look away,” he added.

			To ease the stress, Mnih got up from time to time and wandered over to his laptop. He tapped the keyboard and refreshed the screen to check on his Atari agent. One of the nice things about AI was that you could leave the office for the weekend and the system would diligently continue training.

			Mnih’s agent was busy playing its own rackets game, Pong, which was Atari’s very first creation. When the company started out, its business model was to install game machines in bars. Because of this distribution channel, Pong had to be so simple that even the inebriated could play it.

			Mnih’s agent, while diligent, was still performing abysmally. Just occasionally, it got lucky and won a point. Usually, it lost 21–0. A typical rally consisted of the ball advancing steadily toward one part of the screen while the agent’s paddle bobbed about indifferently in some entirely different quadrant. The system resembled a toddler who turns circles by a tennis court, lost in her own imaginary world while her parents focus on their topspin. Now and again the toddler sticks out her racket and makes contact with the ball by accident.

			After peering at a screenful of statistics showing his agent’s performance, Mnih returned to Andy Murray. The match was going Murray’s way. But when Djokovic threatened to break serve, Mnih covered his eyes.

			Eventually Mnih rose again. He tapped on his keyboard, studied the summary statistics on the screen, and saw something surprising. The agent had just lost another game, but this time the score was 21–4. The statistical probability of randomly winning four points was minuscule.

			Excited, Mnih toggled from the summary statistics to a live shot of the Pong play. He wanted to see whether the four points were for real. Perhaps they had been generated by some malevolent bug in the score-tallying system?

			Mnih watched as the ball traced a path across the screen. This time, as if by magic, the agent moved its paddle toward it. The next rallies were the same: The agent went after the ball, even if it didn’t always hit it. All of a sudden, the oblivious toddler was behaving like an eight-year-old with her first tennis coach.



* * *



			• • •

			Once Mnih’s agent started to win points, it improved exponentially. Equipped with memory replay, the system became superhuman at Pong and at another ball-and-paddle game, Breakout. But the more complex Atari environments still eluded it. For example, a game called Seaquest offered players multiple routes to success: Your submarine could destroy other submarines; it could rescue a diver; it could secure extra oxygen, which would not win points, but would allow it to play longer. Mnih’s agent embraced the first strategy, firing off torpedoes with gusto, but it ignored the other two. After merrily zapping its enemies for a while, the agent would realize that something was amiss, then it would abruptly switch to doing nothing.[25]

			Thanks to his doctoral research, Mnih knew a lot about coaxing performance out of neural networks. But this Seaquest problem related to the reinforcement-learning part of the model. He turned to David Silver.

			“How do you debug reinforcement-learning agents?” Mnih asked him.

			Silver had learned from his PhD supervisor, Rich Sutton, to put himself into the shoes of his agents. “If you are viewing the agent from a human perspective, you won’t understand it,” Sutton would say. “You have to be the agent. You have to experience its experiences.”

			In this case, Silver said, Mnih should examine the agent’s Q-table. “Look at the data that it’s living and breathing,” he counseled.[26]

			Following Silver’s advice, Mnih pulled up the agent’s Q-table on his screen. He could immediately see the source of the problem. For some reason, the agent had been generating higher and higher estimates of the rewards that would flow from actions that had succeeded previously. Hence its monomaniacal zeal for firing off torpedoes.[27]

			Pondering this glitch, Mnih realized that it reflected another clash between supervised learning and reinforcement learning. The goal of a computer-vision system was to predict how photos were labeled. Every time it answered right, it would get a simple, standard-size reward, and that round of the training would be over. But a reinforcement-learning agent had no equivalently neat task. Its objective was to maximize rewards over the course of a game, but the quantity of possible rewards was unspecified, as was the duration of the gameplay.

			With no upper limit to its success, the Seaquest agent could let its imagination run wild. When it hit on a point-scoring strategy such as torpedoing a rival sub, it pictured itself repeating this action over and over, so that the expected value of its strategy shot upward. What’s more, this ebullience fed on itself. Every time the model repeated an action, it would remember its sunny estimate of the expected value from last time, then it would lather on some extra optimism. The result was an unstable upward spiral of expectations: The agent was like a dreamer who finds a couple of hundred-dollar bills on the sidewalk and leaps to the conclusion that he will reap millions of dollars if he walks for a month—and then, having imagined earning the millions, extrapolates further and conjures billions. The dreamer in this analogy would probably give up scouring the sidewalk after a day, no richer, but with sore feet. Likewise, when the Seaquest agent’s cognitive bubble burst, it suffered a crisis of confidence.

			To solve this problem of spiraling expectations, Mnih broke the feedback loop between the agent’s playing and its learning. He did this by equipping his agent with two neural networks, so that he could separate the two functions. The first network assumed the role of the player, responsible for choosing actions in the game: It was expressly not allowed to learn, meaning that the weights and biases in its network were fixed at the initial setting. Meanwhile, the second network served as the observant coach, watching the player’s actions, assessing the results, and adjusting its parameters accordingly. Then, after a suitable period of study, the adjusted parameters in the coaching network were transferred to the playing network. The “suitable period of study” was the crucial element.

			To see why this was so, consider a human tennis coach. As she watches a tennis player, she forms a hypothesis about how he could perform better, but she lets him play on for a while, allowing time for further observation. If the player wins two points with a serve-volley combo, the coach may think, “Oh, I should tell him to do that more often.” But if she keeps on watching, she will see the player win with lobs, drop shots, and big forehands from the baseline, and she will build a richer plan about the advice she ought to provide, perhaps even concluding that the serve-volley combo is among the less successful strategies. Hypotheses based on induction must be open to revision, in other words. A bit of patience—a suitable period of study—turns premature and counterproductive coaching advice into something valuable.

			The same idea applied to Mnih’s Seaquest system. If the playing network won points by zapping a few subs, the coaching network would register that this action brought in rewards, but it wouldn’t communicate its excitement to the playing network or tell it to restrict itself to a torpedo-only strategy. Unburdened by those premature instructions, the playing network would continue to experiment with trial-and-error actions, eventually discovering that it could also do well by saving divers and sourcing oxygen. As these additional reward sources were uncovered, the watchful coaching network would take note, grasping that Seaquest is a game of multiple strategies. Eventually, after a suitable period of study, the rich wisdom from the coaching network would be transferred to the playing network. With the problem of spiraling expectations thus solved, Mnih’s system began to master Seaquest.[28]

			Memory replay had shown that AI systems would perform better if they mimicked the relationship between the hippocampus and the neocortex. The playing/coaching separation established that dividing an AI system into discrete, brain-like regions could empower stronger agents. Hassabis’s business plan had promised fundamental breakthroughs in neuroscience-inspired AI. Three years on, he was delivering.



* * *



			• • •

			In December 2013, Mnih showed up at Harrah’s Lake Tahoe Hotel & Casino, on the western edge of Nevada. He was not there to gamble. The hotel played host to the Neural Information Processing Systems (NIPS) conference, the world’s biggest machine-learning gathering. Wearing a gray sweater, its sleeves rolled up to the elbows, Mnih stood in front of a room so packed that it probably violated fire regulations.

			The talk was a sort of coming-out party for DeepMind. For the first three years of its existence, the firm had stayed under the radar: Its website consisted of a black screen, a logo, and no further information. But now the company had something exciting to show off: the system it had recently dubbed the Deep-Q Network—DQN to the initiated. Word of the network’s accomplishments had leaked, and professors and power brokers gathered to listen.

			Mnih took the audience through a series of slides, culminating with videos of his agent navigating Atari games with astonishing precision. In Seaquest, the agent demolished a series of enemy subs, then went up to the surface to get oxygen, then returned to demolition. In Space Invaders, the agent went after the mothership, the target that generated five times more rewards than zapping infantryman adversaries. In boxing, it pummeled the opposing avatar against the ropes so that it had nowhere to escape to.

			The boxing demo got an appreciative laugh. Perhaps strangely, given the AI community’s on-and-off anxiety about Terminator risk, the audience was amused by DQN’s display of ruthless violence. But the grand finale came with the game of Breakout, which involved batting a ball at a wall of bricks, gradually destroying them. The agent had figured out the old trick for winning with maximum efficiency: First cut a tunnel through the bricks, then send the ball through the tunnel so that it ricochets off the back wall, zapping multiple bricks without the player having to do anything.

			“The room went completely silent,” David Silver remembered. “For every game, the same agent had learned something completely different. People were just blown away. It was a turning point.”[29]

			Looking back on this triumph, Silver noted how Hassabis had grown since the experience with Elixir. In both cases, Hassabis had announced a maximalist ambition, but in the case of DeepMind, he had also figured out a ladder that led to his destination. At Elixir, he had plunged his company straight into making the most complex video game ever, and the overreach had doomed the project. At DeepMind, the ultimate goal was even grander, but Hassabis had let people tinker while he was building out the scientific team, not setting a demanding goal for them. Then, once the team had assembled, Hassabis had shown exquisite judgment. In choosing the Atari challenge, he had understood that the moment to fuse deep learning and reinforcement learning had arrived. The result was another ImageNet moment—not just for vision, but for agents.





