# Göktuğ's [\#FediTips](https://toot.cat/tags/FediTips) No. 003 (Blocks and reports)

You've probably seen that fediverse is "federated" and there are these
"instances" that use different "server software" over a "protocol" that
may remind you you're a bit thirsty.

That may get complex quickly, but a simple way to put it is, the
"fediverse" is a bunch of social media websites that know how to talk to
each other, so users on these servers which we call "instances" can
interact with users on other instances.

Each instance is a bit like a park or a workplace in some capacity: they
host people that usually have something in common. If you're at the park
you want some fresh air, if you're at a concert venue, you want music,
and if you're at work, you want to help your bosses earn those last few
dollars before they can afford the yacht. Similarly in fediverse,
instances are where people that are likeminded to a varyingg degree,
depending on the individual instance, congregate.

It inevitably follows that not all users will want to interact with all
other users, and not all instances will welcome all sorts of users. You
don't want a botany instance dominated by techies talking tech. You
don't want grifters and fascists in any sane instance. Or sometimes you
just don't like some other user.

The mechanism we use for this is blocks. There are two kinds of blocking
available in the fediverse: user blocks and domain blocks. A synonym for
the latter is "instance block".

As a user, you can block other users. This is not a perfect block, as
they will still be able to see your public posts on your profile and
user RSS feed (whereas your "unlisted" posts can be seen on your public
timeline, but can't be accessed through RSS). They won't be able to
interact with you in most cases tho. The imperfection here is that this
block is leaky, and some server software, like Pleroma, do not respect
these leaky Mastodon blocks. E.g., if X and Y are on mastodon, and X
blocks Y, Y can't reply, favorite, boost, etc. X's posts. But if Y is on
Pleroma, they can keep responding to your public toots after a block,
tho you won't get a notification.

You can block domains too. If you as a user block a domain, it's kinda
equivalent to blocking the entire userbase of that domain. Same caveats
as above apply.

An instance can block another instance. This is different in that
varying levels of blocking are available. An instance can be just cut
out completely because they are a terrible instance, but an instance
that's not that egregious but does worse at moderation for example can
be "silenced". In that case people there can follow people on your
instance and interact, but some other ties are obstructed and you may
not see their posts in public timelines and threads.

You can go to /about/more on your instance, and most probably they
maintain there a list of blocked, silenced, etc. instances. Some
instances, e.g. toot.cat, will list why each instance is blocked. In
general, a large block list is a positive sign for a healthy community,
as there are some very unpleasant---to say the least---instances on
fediverse, as well as some very great ones. I will later elaborate on
how to pick a good, well moderated, nicely federated instance in another
tips post.

Lastly, there are other ways of maintaining a healthy network, which
I'll list here but explain in detail in a later post. First of all, you
can "mute" someone. This means you and them can follow each other and
interact, but their toots don't show up on yout timeline, even if
someone you follow boosts them. You can futher block notifications from
them, so if they reply to you or favourite a toot of yours, that won't
generate a notification for you.

You can hide someone's boosts, so that toots they boost will not appear
on your timeline. This may be useful e.g. when you're following an
account whose posts you like, but they may be boosting way too many
other toots. Or stuff you don't like. Or whatever reason really. A good
moment to mention that nobody has the right to judge you for who you
follow, unfollow, block, mute, etc. It's a nice part of the nicer parts
of fediverse that, regardless of the reason, these sorts of decisions
are respected and do not tend to lead to hostility like in "why did you
block me on Twitter" etc.

And, last of these features I'll mention is more a hack than a feature.
If someone is following you but you don't want them to follow you
anymore, you have two options. First is, of course you can just block
them, and the follow relationship will be ended and be impossible to
recreate unless you unblock. Another option is to block the person, but
then unblock them immediately. This will mean that they can interact
with you, but aren't following you anymore, that relationship is always
ended by the block.

In closing, I'll suggest that you "lock" you account in your account
settings. This does not make your account private, instead it means that
people can't just follow you willy nilly. They'll have to send a "follow
request", which you can accept or decline. I suggest that, unless your
account is anonymous or you are a politician or something, you make sure
that you pick your followers well, because that means when you post
followers-only, only people you can trust to some extent will see these
posts. It's a nice thing to have. We'll talk more about this and similar
stuff next week, as the topic will be "toot privacy".

Later\!
