DEPLOY THIS TO RENDER (via GitHub)
====================================

1. Go to github.com → New repository. Public, any name (e.g.
   "aryan-portfolio"). Leave it empty — no README, no .gitignore.

2. On the empty repo's page, click "uploading an existing file" and drag
   in everything from this folder: index.html, robots.txt, sitemap.xml,
   and the media/ folder. Commit.

3. Send me the repo URL — I'll deploy it to your connected Render
   workspace and hand you back a live *.onrender.com link.

No command line needed for any of this — GitHub's web uploader handles it.

GETTING FOUND WHEN SOMEONE SEARCHES YOUR NAME
------------------------------------------------
Realistic picture first: "Aryan Malik" is a common name — there are
already other people's LinkedIn, Instagram and cricket-stats profiles
using it. Ranking #1 for the bare two words, fast, isn't something any
on-page fix guarantees. What IS realistic, and fairly fast:

  - Ranking well for the searches that actually identify you — "Aryan
    Malik MAIT", "Aryan Malik Rohtak", "Aryan Malik PAIMANA". Nobody
    else is competing for those yet.
  - The bare "Aryan Malik" query improving steadily over months as the
    site accumulates the signals below — not a switch that flips.

Already done, in the code:
  - Meta description and page content now mention Rohtak / MAIT / CSE
    in real sentences (not stuffed keywords) — this is what actually
    matches what people searching for you would type.
  - schema.org "Person" structured data is generated automatically from
    the same DATA object as the rest of the site — this is the single
    biggest on-page lever for a name search; it's how Google tells you
    apart from every other Aryan Malik.
  - robots.txt + sitemap.xml are in this folder, ready to go.

Three things only you can do, in order of impact:

  1. GET A DOMAIN WITH YOUR NAME IN IT. This matters more than every
     tag combined. aryanmalik.dev / .me / .in — roughly $10-15/yr.
     Point it at the Render site once deployed (Render → your service
     → Settings → Custom Domain). A onrender.com subdomain is a weak
     signal for a name search; a matching domain is a strong one.
     Once you have it, find/replace YOUR-DOMAIN-HERE in robots.txt,
     sitemap.xml, and the two commented-out lines near the top of
     index.html (canonical + og:url).

  2. LINK TO IT FROM PROFILES YOU ALREADY HAVE. Your GitHub bio,
     LinkedIn "Websites" field, X bio, resume footer — all pointing at
     the same URL. These are high-authority domains already; this is
     what actually tells Google "this URL = this person," and it's the
     highest-leverage thing on this list after the domain itself.

  3. SUBMIT IT TO GOOGLE SEARCH CONSOLE (search.google.com/search-console,
     free). Verify the domain, submit sitemap.xml. Without this,
     indexing can take weeks of waiting for Google to find it on its
     own; with it, usually days.

Search Aryan Malik + MAIT or + Rohtak once it's live and indexed — that's
the fair way to check it's working, before judging it against the bare
two-word search.
