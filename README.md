# README

[The open letter](https://save-nix-together.org/) is very vague at some points. It tries to outline some real issues that require years of context to fully grasp. Without having this necessary context - it is very hard to follow some of the points made, and evidence seems very poor.

This repository aims to list some key points that are easy to understand without all of the context. This is a compilation of damning evidence for Eelco's leadership, essentially.

## Open Letter

Links: [live](https://save-nix-together.org/), [WaybackMachine](https://web.archive.org/web/20240000000000*/https://save-nix-together.org/)

> Graham Christensen has [written on Twitter](https://twitter.com/grhmc/status/1778074264043655620) that he believes that military-technology companies should be allowed to participate in the community so that they don’t fork the project.

Anduril **is not** forbidden to contribute to Nix. People take issue with Anduril **sponsoring the main Nix community event**. This sponsorship isn't the same as just donating money. The sponsors of the main community event are understood to be very close to values of the project. Anduril, a military tech company, **does not** represent the values of the project.

This tweet is an attempt at sabotaging the discussion, as it purposefully misses the point.

> The CCC VOC (video operation centre) threatened to pull out of NixCon 2023 at the last minute over the Anduril sponsorship and effectively prevent the conference operating, and the NixOS Foundation lost a huge amount of good will over their management of this incident. The sponsorship was dropped after such intense public pressure as well as to mitigate potential contract risks with the university hosting it (due to zivilklausel).

This adds to the point above. The main sponsor of the main community event represents the values of the project. CCC VOC, as well as the host university, both don't share the values of Anduril - and so they had a major issue with Nix project embracing those values.

> Eelco holds onto hard power and blocks giving it away even if there is consensus on giving it away by other members of his *team*. This is corrosive to the team having psychological safety and agency to make decisions, as well as its ability to be independent from him. It cements him as the prime authority in the project by dismantling others.

To put it simply: he overrules the decision of CppNix by himself, despite having no more formal authority.

> Eelco ignored repeated calls to disclose anything about whether he has a conflict of interest with respect to Anduril, one of which follows:
>
> ![](https://save-nix-together.org/post-media/9ff794bc-48ea-4c9c-97f8-70199600ec0e.png)
>
> Graham claimed they have NDAs preventing them from disclosing whether they are entangled with Anduril.
>
> ![](https://save-nix-together.org/post-media/9bec220c-702b-42b2-acd7-f6115d36ca13.png)

NDA requires two or more parties to enter into a legally binding contract. That suggests that DetSys and Anduril were heavily considering partnership, at the very least. Being potential partners with Anduril already constitutes a conflict of interest, and it is not addressed at all.

Also, there are ways to answer the question about having a conflict of interest that don't breach NDA. You don't have to outright confirm or deny if you are working with Anduril - you can just say if you have conflict of interest or not. The fact that no one had done that, and the long history of Eelco dodging the question, suggests that the conflict of interest is definitely present.

## Response

Links: [live](https://determinate.systems/posts/on-community-in-nix/), [Archive](https://archive.is/lndrH), [WaybackMachine](https://web.archive.org/web/20240000000000*/https://determinate.systems/posts/on-community-in-nix/)

Eelco responds on DetSys website instead of using the community channels. This heavily implies what the primary audience is (DetSys investors, not NixOS community).

> First, I have had very little involvement in Nixpkgs and NixOS in recent years, having ceded their stewardship to other community members some time ago, and have no more influence over their direction than any other dedicated contributor.

The letter hasn't implied any involvement in Nixpkgs and NixOS. The letter discusses in excruciating detail Eelco's involvement in CppNix.

> Second, I am just one member of the five-member Nix team and hold no more formal authority than the others in determining the direction of the team.

This is a lie. Eelco is not *just* a member of the team - he is a team lead. This clearly means he holds more formal authority. This information is available on [official website](https://nixos.org/community/teams/nix/):

![Eelco is clearly stated as a Team lead of Nix team on nixos.org](./images/eelco-teamlead.png)

Also, Eelco is a **chair** of Foundation. "chair" as in "president". Implying most authority. This constitutes elevated authority - even if Eelco lacks enough authority as a teamlead, he can always weigh in as a chair of Foundation. This information is available on the [official website](https://nixos.org/community/teams/foundation-board/):

![Eelco is clearly stated as a chair of Nix Foundation on nixos.org](./images/eelco-chair.png)

> Third, I have not been a member of the RFC Steering Committee since new members were elected in January 2024.

Cool. The RFC process was established since Feb 11, 2017. [RFC 36](https://github.com/NixOS/rfcs/pull/36), which establishes RFC Steering Committee, was merged on Dec 25, 2018. This leaves a period of almost 2 years where Eelco had complete authority over the process.

Next, [RFC 43](https://github.com/NixOS/rfcs/pull/43), which establishes RFC Steering Committee rotation, was merged on Jun 11, 2019. This outlines a very clear procedure for changing members of RFC Steering Committee. Eelco was part of the RFC Steering Committee until January 2024 - for 4.5 years. As a member of RFC Steering Committee, he had a lot of associated formal authority.

Additionally, the infamous [RFC 49](https://github.com/NixOS/rfcs/pull/49) was open by Eelco himself. This clearly poses a conflict of interests: as a member of RFC Steering Committee, he is supposed to maintain unbiased perspective on the discussion at hand, but he is also an author of RFC and the major player in driving this discussion. This is also a major conflict of interests with being a lead developer of CppNix.

RFC 49 has done immeasurable damage to the Nix project. Flakes were merged upstream before the RFC even reached FCP. Eelco clearly abused his authority as lead developer of CppNix to push flakes, made a joke of the RFC process, and contributed to the degradation of the governance model. RFC was withdrawn, which suggests that community decided against the feature - but the community **had to** accept Flakes as an experimental feature, because it was already merged into CppNix. Flakes being merged against the RFC process and marked as "experimental" (and marketed as production-ready) caused multiple technical and governance issues: ridiculous amounts of regressions in Nix 2.4, motivating [RFC 68](https://github.com/NixOS/rfcs/pull/68), [RFC 106](https://github.com/NixOS/rfcs/blob/master/rfcs/0106-nix-release-schedule.md), [RFC 134](https://github.com/NixOS/rfcs/pull/134), [RFC 136](https://github.com/NixOS/rfcs/pull/136) and [RFC 158](https://github.com/NixOS/rfcs/pull/158).

Eelco had done such a poor job at managing RFC 49 and its consequences, that it is grounds enough to remove him from any positions of authority and temporarily embargo his contributions. He has not faced any responsibility for this, and held onto his authority. This has done a lot of damage to the community in general, and it's only now that we're starting to catch up with the thought that he should be held accountable for this disaster.

> Fourth, the NixOS Foundation in no way controls or governs the Nix community, which has, since its inception, demonstrated its ability to self-govern very well.

This is true. And this is a large part of the issue. Nix community has no authority. It is governed by implicit authority of long-time contributors (such as Eelco). So despite Foundation having no formal control - people with strong background in the community have informal control, and some of those people (like Eelco) are blocking doing it any other way.

> I strongly believe that we should not exclude any company from contributing to, participating in, or utilizing the Nix project in any way.

This intentionally misses the point. No one says anything about excluding Anduril from participating or contributing to the Nix project. People have a large issue with Anduril being a sponsor of the main community event. This is not simply "donating money", nor is it "contributing" - this is being direct associates and partners. If a company sponsors the main event - it is not "just using the project", it is driving its governance.

> My role, participation, and focus on the good work being done at Determinate Systems have been public knowledge since the company’s inception.

This is a lie. Quoting the letter:

> Although Eelco is supposedly a founder of Determinate Systems (we are unsure if this was the case as of the time of founding or if it was changed retroactively), there was a period of multiple months before Eelco disclosed his involvement in DetSys, at the very least not in a way that appeared in open board meeting minutes or on Discourse.

> The assertion that Determinate Systems “owns” Nix or seeks to exert outsized influence over the project, the community, or the foundation is patently false: I am the only member of the Nix team who works for Determinate Systems.

This is a lie. Quoting the letter:

> However, the reason for existence of the Determinate Systems installer appears to be that they [want to take responsibility for the stability of flakes](https://determinate.systems/posts/experimental-does-not-mean-unstable/) themselves. This is fine, however, it is questionably acceptable to do that while employing the *lead developer of CppNix* and saying nothing about how this will interact with the team’s decisionmaking autonomy.
> In effect, Eelco has privatized the release process of CppNix into DetSys by being in both CppNix and DetSys, the DetSys installer existing and *having* a release process, and by not fixing `nix upgrade-nix`, whether that is deliberate or not, such that the only way to get a working upstream CppNix is to rely on DetSys.
> Relatedly, the [Nix repo now depends on the DetSys installer](https://github.com/NixOS/nix/pull/10339) by his PR.

> Regarding alleged conflicts of interest, I want to be very clear.

What about the alleged conflicts of interest, by the way? No mention of Anduril being a business partner of DetSys? No mention of Anduril being an undesired sponsor of NixCon? No mention of Eelco expressing his opinion in favor of Anduril?

> I remain committed to creating a community where everyone feels seen, heard, and valued, and I will not let unfounded accusations detract from this important work. I encourage everyone reading this who feels that they have not been heard or feels displaced to join the Determinate Systems community as we continue working to make Nix as easy to use and as impactful as possible. Our code of conduct is available here, and you can join our Discord at https://determinate.systems/discord.

So if someone feels unsafe in the Nix community due to Eelco's mismanagement of the community - they are welcome to join the DetSys community. Not only is this absurd, it's also an outright confirmation that Eelco grossly mismanaged Nix community, and instead of owning up to those mistakes - focused on making his own.
