# Göktuğ's [\#FediTips](https://toot.cat/tags/FediTips) No. 004 (Toot privacy)

(Sorry for the long toots without content warnings, I am not using them
because these toots are meant to be discoverable to newcomers. I'll make
sure that these are once a week things and not a constant harassment of
your timelines.)

The plan for this Sunday is to post this weeks fedi tip, brew me a nice
cup of coffee, and do some reading for my studies, so let me get going
with the plan.

The topic this week is related to the last week's topic which concerned
blocks and reports. We will be talking about another way of making
(almost) sure who sees your toots are who you intend them to see.

Besides blocks, the main tool for adjusting the audience of your
presence here on a toot-by-toot basis is the four-or-five levels of toot
privacy you can set, the number varying depending on the instance you're
on (we'll talk about it in detail in a bit).

First of all, how do you set toot privacy? Well, on the Mastodon web
application, it's the third button from left below the compose box, and
it's alt text is "adjust toot privacy". Probably as a homage to horrible
design, the icon of this button is un-annotated, and varies depending on
the setting, which sucks but you will get used to it. The icon will be
one of: a globe, an unlocked padlock, a locked padlock, or an envelope.
Luckily, each level is annotated in the menu that opens once you click.
On apps, it totally depends on the app, but it's often a similar looking
icon.

The broadest level of toot privacy is "public". This means two things:
your toot is available to public timelines, and it's also visible in the
RSS feed of your account. What are public timelines? It is what you see
when you check out the "federated" timeline, i.e., the toot is readily
visible to any instance that your instance hasn't defederated from. The
RSS feed means that these defederations are circumventable: any RSS
reader can see these toots, so you should consider them to be
essentially fully public. Even if the RSS feeds didn't include them, the
public website would, which is fully public, which reinforces the same
conclusion: public toots are public, in every sense of the world. Do not
rely on deferedations or instance/user blocks for their privacy.

The next stricter level is "unlisted". An unlisted toot is public, but
it's excluded from the RSS feeds, and invisible in public timelines.
Your followers will still see it, and can boost it, so it is essentially
a public toot but a bit more silent. Instead of using it for privacy, I
suggest you use unlisted toots when you want something to be seen by
your followers primarily, but not necessarily want it to be
followers-only either. Exclusion from RSS readers is a nice benefit, but
do not forget that public webpages can be scraped fairly trivially.

The actual level with any real privacy is "followers only". Only your
followers will be able to see a followers-only toot, and only they can
interact with it. It won't be on the RSS feed, not in the public
timelines. It's practically not available to be boosted as well. There
is a major caveat tho, which we will talk about in a bit.

The strictest level is "Direct". Direct toots will only be visible to
people who are explicitly mentioned in the toot itself by their
fediverse handles, e.g. `@ cadadr @ toot.cat` (without the spaces, of
course). This is similar to a DM on Twitter and IIUC some other
platforms, and this is when you want to talk to a fedizen, or a few,
directly.

Now, the caveat. What is the caveat? The caveat is that neither
followers-only nor direct toots are stored in such a way to disallow the
instance moderators from seeing them. It's a bit cumbersome as they
don't have an Admin UI for it, but they can see messages if they choose
to query the database directly. What this means is, at some level, you
have to trust your admins to not peek in your messages and be nasty with
them. More concretely, what this means is, use either of these privacy
settings very carefully, and if you really want or need a conversation
to be truly private, move the communication outside fediverse. I will be
talking about etiquette on fediverse later, but make sure that you read
your interlocutor(s)' profile(s) before either sending them a direct
toot to see if they have set any boundary about DMs, and make sure you
are <span class="underline">very clear with your intent</span> if you're
asking to move the conversation to a different medium, especially if you
haven't had a decent amount of interactions with them already here.
Failing these might result in the interaction coming off as
<span class="underline">very</span> creepy, and might result in a report
or block.

It's not unlike real life, you wouldn't just go up to a new acquaintance
or a stranger and offer them to have a private chat in the bathroom or
in the back alley, no? Same thing here.

Another etiquette thing I'll mention briefly but talk more about in a
later "etiquette" toot in this thread is that, changing the privacy
level of a thread. This means, e.g. replying to an unlisted thread with
a reply whose privacy is set to public, or vice versa, or similar. It is
generally advisable to make sure that the privacy level of your reply is
the same as the toot you are replying to (tho there are exceptions), and
to never reply with a toot whose privacy is less strict than the toot
you are replying to. Most likely that will be taken to be hostile.

Now, on top of these four levels of privacy, instances that use the
Glitch-soc and Hometown forks of Mastodon have an extra level of privacy
available to them, that's somewhere between unlisted and followers only:
local-only posting. A local only post is visible only to your peers at
your instance. In order to set this level, if you are on one of these
forks, you will have to click the three dots icon below the compose box,
whose title is "advanced options", and check the "local-only" checkbox.

Before concluding this, I wish to mention one idea that's been brought
up by several users in my circles, and is truly a sad omission from
mastodon: mutual-only toots, i.e. toots that are only visible to people
that are both in your followers and in your follows. Presumably these
are your fediverse besties, especially if yours is a "locked" account,
and having this as a level of privacy could be very useful. I can
remember several instances where I really wanted to be able to use this,
and several toots that I avoided posting because this was not available.
A truly unfortunate omission in a network that's supposed to avoid the
bad sides of the likes of Twitter and instead provide its users with
safe spaces to express themselves.

Last thing I'll touch upon is toot auto-deleters/purgers. I don't know
much about these tools myself, but when browsing profiles, you'll
encounter ones that say things like "my toots expire" or "toots expire
in X days" or "my toots are automatically deleted", etc. These users are
using services that go through their history, and delete toots that are
older than a certain age, or when the number of their public toots
exceed a quota determined by them. I don't know any of these tools well
enough to make a suggestion, so if you want to use them, you'll need to
find one, or maybe ask one of the users you encounter that say they use
them.

So this is it for this weekend. This one was particularly long, but if I
feel like any briefer would be too brief, and there wasn't a logical
point to break the topic into two, so, yeah. Sorry about that.

Next week, we'll talk about how to post accessible toots.
