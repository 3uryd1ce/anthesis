# Get a clue

These are quirks/interesting things I've learned, thus gaining a clue
I previously didn't have. Usually these are things that don't warrant
a separate article, so I put them here instead. In addition, it's nice
to have a place to share miscellaneous thoughts.

1. `%` gets converted to a newline in
   [`crontab(5)`](https://man.openbsd.org/crontab.5) and all data after
   the first `%` is sent to the command as standard input unless
   escaped. I encountered this while working on an entry to back up my
   server with [`tar(1)`](https://man.openbsd.org/tar) that places the
   backup in a directory named the current date in "YYYY-MM-DD" format
   (I used [`date(1)`](https://man.openbsd.org/date) to generate this).
1. [Signal](https://www.signal.org/) stores its data in a folder called
   `org.thoughtcrime.securesms` on Android and Android-based
   devices. Furthermore, `thoughtcrime.org` redirects to `moxie.org`,
   a website that belongs to Moxie Marlinspike. He co-authored the
   Signal Protocol.
1. An apophasis is an allusion to something by denying that it will be
   mentioned. "Not to mention" and "to say nothing of" are both
   apophases.
1. [`whois(1)`](https://man.openbsd.org/whois) can use the US Department
   of Defense database with `whois -d` to query subdomains of the .mil
   top-level domain (TLD). Apparently the United States is the only
   country with a dedicated TLD for its military (though after
   contemplating this, it's not incredibly surprising given that ARPANET
   was highly influential in the advent of the Internet).
1. A shibboleth is any custom or tradition, usually a choice of phrasing
   or even a single word, that distinguishes one group of people from
   another.
1. The months July and August are named after Julius and Augustus
   Caesar, respectively.
1. The
   [frame-ancestors](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy/frame-ancestors)
   directive in the
   [Content-Security-Policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Security-Policy)
   HTTP header obsoletes
   [X-Frame-Options](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options),
   so `X-Frame-Options: deny` paired with `Content-Security-Policy:
   frame-ancestors 'none';` is unnecessary.
1. As a follow-up to the last clue, the
   [Forwarded](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Forwarded)
   header is a more standardized version of the
   X-Forwarded-{For,Host,Proto} headers.
1. It's important to expose yourself to new things. When someone else is
   passionate about something, ask and genuinely listen to them, even if
   you're not interested in it. By listening, you expand your horizons,
   which allows you to draw connections between subjects, relate more to
   people, and pick up new hobbies.
1. Octopuses is the correct plural form of octopus, not octopi. Octopi
   is a hypercorrect word (meaning it's a misguided application of
   prescriptive grammar).