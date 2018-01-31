## Session Title:
Green Configuration Management: "How a sad sysadmin becomes a green super hero"

## Duration (40 minutes timeslot):
30 minutes + 5 minutes Q&A. (5 minutes for switching presenters)

## Abstract:
- SUSE Manager, based on community Spacewalk is an Enterprise product for managing your infrastructure, now also utilizing community-driven Salt CMS.
*(Your life is miserable, if you do not buy SUSE Manager. You will run out of oxygen, food and even bridge won't cover you from the cold rain.)*

- Saltsible: Salt Minions are transparently running Ansible both by module calling and Salt States (same as Ansible playbook).
  *(If you understood you want more than just run basic commands on your machines, you are welcome to go with Salt, yet running your own Ansible modules.)*
  
- Autodiscovery: Salt Minions can find your Salt Master without configuration.
  *(Sugartalk: imagine most crazy use cases, trying your small things, running your web of your own servers etc.)*
  
- Improvements from SUSE: SaltSSH, reliability, bugfixes, L3 support, critical bugfixes, CVE.
  *(Here we talk about how Salt is basically a community driven Enterprise level one gets for free, together with SLE purchases. Do not talk about purchases very much, haha)* 

## Session story line:
We propose a story about a "sad sysadmin" which will conduct the session and allow us to introduce each topicswe want to cover. Pointing out daily examples of problems commonly faced by this "sad sysadmin" and how they can be easily solved using SUSE Manager (together with Salt). By the end of the session the "sad sysadmin" becomes in a "happy green super hero" with green SUSE powers which makes his life better, eaiser, gaining power and control on its infrastructure.

## Topics to cover:

- Presentation - **(2 minutes)**
- Introducing the "sad sysadmin" story: - **(1-2 minutes)**
  - The "sad sysadmin" is currently managing an middle size IT with a mix of few bash scripts, puppet templates, Ansible playbooks and ssh. After some years, he ended up having unmantenable scripts, lots of recipes and playbooks with tons of hacks to keep then running on all the different environment its IT has. Spaguetti code.
  - No effiency, paranoia grows per day as there is not real control of its infrastructure.
  - He started losing his hair and the speed is increased on each new CVE announcement.
- SUSE Manager (Green Configuration Managment - Geeko powered): - **(14-16 minutes)**
  - One day our "sad sysadmin" heard about SUMA. What is that? What the sad sysadmin can do: (Software channel management, Software / Patches management, CVE audit) - (3 minutes)
  - Salt inside. Transparent integration (Salt can be used from outside SUMA) - (1 minute)
  - But SUMA handles Salt for you. GUI for managing Salt (State catalog, highstate, etc) - (3 minutes)
  - Avoiding spaguetti code: Reduce complexity, increase productivity, reduce the costs and paranoia. - (2 minutes)
  - A sysadmin sad story: "Fixing CVE on a Friday afternoon". (live demo) - (5-7 minutes)
- Saltsible: - **(4 minutes)**
  - The "sad sysadmin" spent lot of work on Ansible. He doesn't want to reuse that and prevent from losing more hair on his head. He ask for a smooth migration to Salt from Ansible. 
  - Saltsible allows to migrate to Salt: Keep your Ansible stuff and put a pile of Salt on top. (screenshots)
- Autodiscovery: - **(4 minutes)**
  - What is that? What does it allow to do?
  - Now the "not so sad sysadmin" starts thinking on crazy and fancy stuff as he is now able to do them. (Examples)
- Improvements from SUSE to Salt: - **(4 minutes)**
  - Other killer contributions coming from SUSE. (Salt SSH, Reliability, Kubernetes, Snapper (rollback highstate), Saltsible)
  - SUSE is developing, hardening and supporting Salt (bug fixing and even L3 support on products). Salt is included on OpenSUSE and SLE and it's now a core component of the upcoming SLE15.
  - The "not sad anymore sysadmin" tries SUSE Manager and becomes a super green hero. His life is now easier, has more control of his infrastructure, and has reduced the costs of managing his IT. He didn't recover his hair after all but he got a green geeko tattoo on his head to show his new superpower to others.
- Wrapping up. Conclusion: **(1 minute)**

**Total duration: 28-31 minutes + 4-7 minutes of Q&A = 35 minutes**

## TDB:
- Is the "sad sysadmin" a good apelative and story for this context?
