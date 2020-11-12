%title: AFRINIC DBWG Update - ZAPF 5
%author: Ben Maddison
%date: 2020-11-12

-> # The AFRINIC Database Working Group

-> ## Rechartering and other news

---

*Disclaimer:*
All views, predictions and errors are mine alone

---

-> # Database? What database?

The `WHOIS` is the public source of information on
Internet number resources in the AFRINIC service region

^
- administrative data (`org`, `person`, `role`, etc.)
^
- allocations data (`aut-num`, `inet(6)num`)
^
- operational / security data (`mntner`, `domain`, etc.)
^
- routing data (`as-set`, `route(6)`, `route-set`, etc.)

---

-> # the Database Working Group
-> ## Background

From the [AFRINIC website](https://www.afrinic.net/committees/database-wg):

> "The purpose of the AFRINIC Database Working Group (DBWG)
> is to provide a channel for discussion between AFRINIC staff,
> technical community members, and other stakeholders,
> regarding the implementation of AFRINIC's WHOIS service." 

^
... Not much of a *working* group

---

-> # the Database Working Group
-> ## Background (cont.)

[Mailing list](https://www.afrinic.net/committees/database-wg) established 2016 (?),
primarily as a means for AFRINIC staff to communicate
operational information to community members.
^

Very low traffic until the last ~18 months.

---

-> # the Database Working Group
-> ## Background (cont.)

1st in-person meeting of the WG held at AIS'19 in Kampala, UG

^
- Frank Habicht selected as co-chair
^
- Several items brought up for discussion and feedback 
  by community and staff members

---

-> # the Database Working Group
-> ## Current status

Most recent meeting held remotely September 2020.

Several items concluded:

^
- Attribute re-ordering
^
- RRDP in production
^
- IRR GUI interface
^
- Various data inconsistencies addressed

---

-> # the Database Working Group
-> ## Current status

Most recent meeting held remotely September 2020.

Still under discussion:

^
- Various issues relating to stale/un-referenced objects
^
- Changes to the `changed:` attribute to improve utility
^
- Database authentication improvements
^
- `domain` object size limits
^
- Database user manual overhaul
^
- Ben Maddison (me :-)) selected as acting-co-chair

^
*Big increase in interest* over only ~1 year

---

-> # the Database Working Group
-> ## Current status

Most recent meeting held remotely September 2020.

Substantial discussions around "process":

- Does the WG publish "policies"?
- Does the WG have any powers to direct staff activity?
- How is a proposal adopted as a "work item"?
- How does the WG group take decisions?

^
The current published description says *nothing*

---

-> # the Database Working Group
-> ## Re-chartering

These questions cannot be answered without agreement on
the purpose and powers of the WG.

A small group was formed to work on an initial draft:

- Frank Habicht (co-chair)
- Ben Maddison (acting co-chair)
- Yogesh Chadee (AFRINIC staff)
- Simon Seruyinda (AFRINIC staff)

---

-> # the Database Working Group
-> ## Re-chartering (cont.)

Open process: all discussion and drafting to be undertaken
in public

Open questions:

- Should the WG be empowered to "instruct" operations
- What form should the output of the WG take?
- What should the scope of interest be?
  - WHOIS only?
  - RPKI operations?
- How should interactions and overlap with the PDWG work?
- How should proposals become work items?
- How should co-chairs be appointed?

... and plenty more ...

---

-> # the Database Working Group
-> ## Re-chartering (cont.)

*Why do I care?*

^
- Routing security:
  Operators need to be able to ensure that information
  is *trustworthy* and *accurate*
^
- Peering operations:
  - Reliable query operations
  - Well defined APIs
^
- Debugging / abuse handling

---

-> # the Database Working Group
-> ## Getting involved

- Join the [mailing list](https://lists.afrinic.net/pipermail/dbwg/)
^
- Ask questions
^
- Suggest issues / work items / areas of interest

^
-> **It's your database**

---

-> # FIN

-> Questions?

-> (slides available on [github](https://github.com/benmaddison/zapf5-dbwg))

---
