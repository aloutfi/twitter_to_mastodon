# Migrating from Twitter to Mastodon, a developer's guide

**Disclaimer**: the ecosystem of tools to interact with Twitter is changing rapidly. If something no longer works submit an issue and I will triage it.

## Rationale

The open-source software community has been a cornerstone of Twitter's appeal since the company's inception. Twitter's infrastructure & operations rely on many systems that benefit or depend on open-source. 

Twitter as a platform is changing. Their recent reversal of 3rd party client support represents a paradigmatical shift in policy that does not favor open-source software. It was a slap in the face to the developers who created & maintained these clients and the community that supported them.

It is expected that Twitter will continue to monetize its functionality at the expense of its various communities, disenfranchising once-loyal users and making the idea of migrating to a different platform more appealing. We already see this trend with many prominent figures in the open-source community migrating to Mastodon.

My primary use case of Twitter has always been discovering new techniques, tools, platforms, languages, frameworks, and trends within the open-source community. If these conversations happen in places other than Twitter, it is in my best interest to participate in them.

At the time of writing this, the argument of needing to decide between Twitter or Mastodon is a false dichotomy. Twitter operates at a much larger scale and is its own class of supersystems.  Further analysis will need to be done on the health of Twitter's user base and whether there is a trend of exiting Chapel Perilous.

This collection of scribbles represents the ongoing body of work and research into the viability of Mastadon as a platform to replace my primary use case of Twitter.

## Process

If you are longtime Twitter user like me, you probably have some questions:

1. [WTF is Mastodon?](https://docs.joinmastodon.org/) 
2. How do I choose my server?

   - Tooling to run analysis of current follower lists:

     - [Fedifinder](https://github.com/lucahammer/fedifinder)

     - [Debirdify](https://github.com/pruvisto/debirdify)
3. How do I automate the migration of my followees?

   - initial
     - [Twitodon](https://twitodon.com/)

   - continuous
     - [Fowler's approach](https://twitter.com/martinfowler/status/1616074839537684480)
4. How do I notify my followers of my migration?

   - disseminating my new handle to followers on Twitter
   - As my followers join Mastodon
5. How do I keep my migration organized?
   - see the [checklist template](https://github.com/aloutfi/twitter_to_mastodon/blob/main/checklist_template.md)
   - `cp checklist_template.md checklist.md`

6. What is some cool tech built around mastodon?
   - See my [Mastodon Migration GitHub List](https://github.com/stars/aloutfi/lists/mastodon-migration)



## Future questions

- Mastodon: how will the system evolve to and operate at the scale necessary to reach critical mass?

- Security concerns for Mastodon
  - Mod access to direct messages
    - This scares users away, particularly in the financial sector (mods being able to see market speculations)
- What other open-source offerings from Twitter (that are utilized by 3rd party developers) that are at risk?

- Health & trends of userbase for Twitter & Mastodon
  - Active Users
  - Web Traffic