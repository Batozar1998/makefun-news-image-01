# 13 Nov 2026: The World Today

A magazine front page summing up Friday 13 November 2026 in one image. A
night-side globe lit by city lights crowns six vignettes, one per story:
the US Senate summoning ex-NVIDIA CEO Jensen Huang and Commerce Secretary
Lutnick; Zelensky meeting US envoys as Europe joins the Ukraine peace
talks; Ukraine firing nearly 1,200 drones at Russia; the US downing two
Iranian drones near Bahrain; the FAA lifting a nationwide ground stop;
and the global Microsoft 365 outage entering its second day. Every label
is a verified event of that day. Two of the six — the FAA ground stop and
the Microsoft outage — happened late in the day, after the house's own
reference images were drawn, so this cover tells the whole day, not just
its morning.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
# writes out/entry.png (a byte-for-byte copy of entry.png)
```

Python 3.13, standard library only, no network. Running it twice writes
identical bytes.
