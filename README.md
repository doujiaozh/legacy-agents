# Legacy Agents

> AI agents for operating systems that Microsoft abandoned.
>
> Win3.1 ¡ú Win98 ¡ú Win2000 ¡ú WinXP ¡ú Win7

## The collection

| Era | Repo | Platform | Approach |
|---|---|---|---|
| 1992 | [win31-agent](https://github.com/doujiaozh/win31-agent) | Win 3.1 | Python 3, Win3.1 *visual style* |
| 1998 | win98-agent | Win 98 SE | Python 2.7, real Win98 |
| 2000 | [win2000-agent](https://github.com/doujiaozh/win2000-agent) | Win 2000 | Python 2.7/3.x, TLS 1.2 challenge |
| 2001 | [xp-agent](https://github.com/doujiaozh/xp-agent) | Win XP | Python 3.4, pure stdlib |
| 2009 | [open-research-agent](https://github.com/doujiaozh/open-research-agent) | Win 7 | pydantic 1.x + httpx |

## The philosophy

Modern AI stacks assume modern OS. This collection proves they can run on 20-year-old machines ¡ª with the right workarounds.

## The core loop

Every agent does the same thing:

    Input topic ¡ú Search Bing ¡ú Call LLM ¡ú Output Markdown report

Only the platform constraints differ.

## License

MIT