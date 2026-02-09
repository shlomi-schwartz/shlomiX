# Postel's Law

Be liberal in what you accept, and conservative in what you send.

## Key Takeaways

1. Be empathetic to, flexible about, and tolerant of any of the various actions the user could take or any input they might provide.
2. Anticipate virtually anything in terms of input, access, and capability while providing a reliable and accessible interface.
3. The more we can anticipate and plan for in design, the more resilient the design will be.
4. Accept variable input from users, translating that input to meet your requirements, defining boundaries for input, and providing clear feedback to the user.

## Origins

Postel's Law (also known as the Robustness Principle) was formulated by Jon Postel, an early pioneer of the Internet. The Law is a design guideline for software, specifically in regards to TCP and networks, and states "TCP implementations should follow a general principle of robustness: be conservative in what you do, be liberal in what you accept from others". In other words, programs that send messages to other machines (or to other programs on the same machine) should conform completely to the specifications, but programs that receive messages should accept non-conformant input as long as the meaning is clear.

## Further Reading

- [Design Systems and Postel's Law](https://markboulton.co.uk/journal/2016-05-17.design-systems-and-postels-law/) — Mark Boulton
- [Robustness and Least Power](https://adactio.com/journal/14327) — Adactio
- [Your Website has Two Faces](https://alistapart.com/article/your-website-has-two-faces) — A List Apart
- [Design with Difficult Data](https://alistapart.com/article/design-with-difficult-data/) — Steven Garrity
- [Robustness Principle](https://en.wikipedia.org/wiki/Robustness_principle) — Wikipedia

## Related

- [Choice Overload](/choice-overload/)
- [Hick's Law](/hicks-law/)
- [Law of Pragnanz](/law-of-pragnanz/)
