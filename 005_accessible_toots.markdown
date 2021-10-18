# Göktuğ's #FediTips No. 005 (Accessible toots)

Hello again\! Today we're talking about how to author accessible toots.
This may end up being longish as there's a lot to cover and the UI just
helpsn't.

Prefacing this with a disclaimer, I am an abled person. Pretty much only
accessibility problem I ever experienced is shortsightedness and
astigmatism, which are easily corrected away by glasses and doesn't
cause me any inconveniences or accessibility issues. So where I conflict
with the lived experience of disabled people, take their word over mine.
I'm sharing what I've learned through interacting with fellow fedizens,
so I'm a secondary source of information.

I want to start first and foremost saying that please don't infantilise
disabled fedizens. They don't need our pity, they just need us to stop
actively excluding them from the world in general and from fediverse in
particular. Also, while some people are permanently disabled, everyone
can have temporary disabilities that can even be something that's not at
all medical, so accessible posts make fediverse better for *everyone*.

With that outta way, let's start talking. First and foremost, the most
basic form of making your toots accessible is adding media descriptions
to images, videos, and sound recordings you post. This helps screen
reader users or deaf fedizens to be able to tell what's going on in your
posts. It also helps abled fedizens when the media fails to load or they
don't want to load it for some reason (file too big, recording too long,
etc).

Now some important notes regarding image descriptions. First of all, of
course apply to posts you boost the same standards you apply to your own
posts. You can either avoid boosting toots without media descriptions,
or provide a media description as a post on your own timeline or as a
reply to the toot you boosted, preferably in either case with a content
warning that reads something like "image description for last boost". I
personally avoid boosting such toots most of the time, and for the
occasional boost, I write a description in my timeline.

Another consideration is media description length. Once you start
writing these, it can be enticing to just write and write about stuff
you post, because it's really fun to describe things, especially
beautiful images. But don't get carried away, as too long a description
is often only as good as no description. On the flip side, if your
caption is just "image" or "meme lol", it's not only unhelpful but kinda
insulting if I'm honest, so try to hit a balance here. What I do is, if
there's text on image, I transcribe it, unless it's really really
irrelevant or in a script I can't type. When a long description is
warranted, I start with a summary line before elaborating, so people can
skip if they want.

Finally, re: media descriptions, keep in mind that not everyone can
write them. Some people have disabilities that make it difficult for
them to post media with descriptions, so be kind. Opting to be
principled about media descriptions shouldn't mean that you berate
people literally **can't**.

I want to conclude that part saying, again, don't infantilise disabled
people. Don't say "oh blind people are better off if they don't see
what's in this image", that's just one of the places where content
warnings are useful, and they don't need your protection otherwise. If
you don't want to write media descriptions, or can't, just don't, or ask
that someone do it, people are likely to help. Also, you can tag one of
the OCR bots at e.g. "@ OCRbot @ fedi.lynnesbian.space" (without
spaces), or use Mastodon's OCR, but the results are often less than
great and confusing. If you can, review their results and correct where
necessary.

Next point, emojis. Emojis don't pose much a problem on their own, but
they are when you string many of them together or abuse them. If you
string many of them together, the screen reader will read the full name
of each emoji so a string of 6 emojis can end up being read as 20-30
words. Emojis are also sometimes hard to tell apart for sighted folk as
well. I often do need to just hover over them to read the tooltip so
that I know what emoji it is.

An annoying form of emoji abuse is in your display names. Again, one or
two emoji in there is not a problem, but if you string many emojis, it's
bad for screen readers and bad for human eyes as well, especially
corrected ones like the pair of yours truly. In general, use emoji in
moderation as an enhancement, not as an alternative logographic writing
system.

In a similar vein, don't abuse unicode in your toots. This is e.g. when
people write "Unicode italics" using mathematical symbols, Greek or
Cyrillic letters etc. not for their intended purpose, but for emphasis.
If you write "hello" using so called unicode italics, the screenreader
will read

    MATHEMATICAL SANS-SERIF ITALIC SMALL H
    MATHEMATICAL SANS-SERIF ITALIC SMALL E
    MATHEMATICAL SANS-SERIF ITALIC SMALL L
    MATHEMATICAL SANS-SERIF ITALIC SMALL L
    MATHEMATICAL SANS-SERIF ITALIC SMALL O

because it has no clue to tell what's the right action to take there.
That's 30 words for your one italic word.

Similarly, don't abuse diacritics. Diacritics like á, ë, ğ, etc are part
of writing systems of human languages. But some people like to drown
English text in a crazy amount of diacritic marks as a joke, and it's
bot illegible and screenreader unfriendly. It's also kinda disrespectful
to languages whose writing systems have these diacritics, if I may add
someone whose language does this. They are not jokes, they are letters.

ASCII-art in toots is pretty annoying universally, so just don't do
that. Even for sighted people, it won't look the same everywhere, it'll
actually probably look completely borked everywhere other than your
screen, so just pretty please just don't do that. It will of course mess
up the screen reading, as the screen reader just doesn't have the
facilities to appreciate your magnum opus.

Use content warnings for media that are too flashy, loud, graphic, etc
because these can induce epileptic episodes, migraines, and PTSD
responses. Content warnings are not there to just hide spoilers or
potentially inflammatory text. They can be used diversely, including as
trigger warnings, and in general as a way to ensure that the viewer has
informed consent when viewing your content. I'll talk about scenarios
where this is necessary, preferable, not required but kind, etc. in a
later tip toot on fediverse etiquette, but a rule of thumb is, if you
believe someone out there could make without the sight of your media or
text, it's nice to help them to afford to view the content warning and
move away.

Last two points. Pen-ultimately (hehe) post your hashtags, and uncommon
compounds (say e.g. subreddit names like r/BadLinguistics) in
[\#CamelCase](https://toot.cat/tags/CamelCase) where every word starts
with a capital letter. It will help screenreaders tell apart the words,
because otherwise it doesn't have the means to tell a neologism is a
single word or a compound.

And, closing this post, a final way I know of of how to accomodate
screenreaders is to end your sentences with punctuation and start them
with capital letters. That will help screenreaders identify sentences
better and read them in a pace that makes where they begin and end more
obvious, leading to the screenreader producing them with better
articulation, intonation, etc.

So yeah, let's make sure that everyone is in on the fun. It's pretty
boring when some people have to sit the fun out because we are actively
excluding them. Some blame falls on the apps like Mastodon and Pixelfed
that make it not buttery smooth to add these descriptions (the latter is
a particularly bad offender sadly), but that's not a good excuse. Stand
up to status quo and except where you can not, make your toots
accessible for all fedizens that have permanent disabilities, temporary
disabilities, bad internet, mild accessibility issues, and just
everyone. You are already trying to make the society a better place by
opting out of centralised social media, so why not go the extra mile and
help make it as inclusive as possible, regardless of whether the
platforms dev comply wholeheartedly or not?

Credits:

The following ideas have come from fellow fedizens when I asked about
what to include in this post
(<https://toot.cat/@cadadr/106674039417157055>):

Media description length: [@charlag](https://birb.site/@charlag)

Disabilities that make writing media descriptions difficult:
[@bright\_helpings](https://mspsocial.net/@bright_helpings)

Camel case hashtags:
[@VictorVenema](https://fediscience.org/@VictorVenema)
