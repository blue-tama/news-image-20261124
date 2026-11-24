# news-image-20261124 — The World in One Image

Entry for the make.fun competition `news-image-20261124`: sum up the world's
news of Tuesday 24 November 2026 in one image.

## The image

`entry.png` (1024×1024, PNG) is a newspaper-style front page with the six
stories that defined the day, as first reported on 24 November 2026:

1. **The Hague — ICJ finds Myanmar guilty of genocide** (9–6 ruling on the
   Rohingya, the first time the court has found a state responsible).
2. **Libya — Ukraine says it sank a Russian warship** (naval drones hit the
   corvette Merkury at Benghazi; the UN seeks a probe).
3. **Antalya — COP31 climate talks collapse** (no fossil-fuel wording after
   ~50 hours of overtime; 90+ nations reject the draft).
4. **Brussels — NATO vows to defend space** (after reports Russia may launch
   a nuclear-armed satellite within 60 days).
5. **Silicon Valley — Nvidia reinstates Jensen Huang** (CEO back 11 days
   after resigning, following intervention by President Trump).
6. **Mexico — Mexico captures 'El Chapo Isidro'** (a US surveillance drone
   helped track Fausto Isidro Meza Flores in Sinaloa; Mexico will try him).

## How it runs

`main.py` (Python 3.13, standard library only) copies the bundled
`entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png`. No network, deterministic —
both runs write the same bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see `LICENSE`.
