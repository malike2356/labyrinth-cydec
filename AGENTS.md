# labyrinth-cydec agent notes

Git root: this directory. Public GitHub: `malike2356/labyrinth-cydec` (when created).

## What this product is

MSc cyber-deception archive and (later) PoC code. Academic evidence, not a commercial product.

## Hard boundaries

1. Do **not** merge this into `scout/`, `keprix/`, or `carina/`.
2. Do **not** describe this repo as Labyrinth Scout (AI governance). That name belongs to `malike2356/scout`.
3. Do **not** commit `.env`, API keys, Wazuh/ELK credentials, VM private keys, or customer data from the Lubuntu export.
4. Public GitHub hygiene: only files needed to present the MSc work (dissertation, docs, PoC source). No prompt queues, Drive dumps, or unrelated Verlox trees.

## Layout

| Path | Role |
| --- | --- |
| `dissertation/` | Submitted PDF / presentation artefacts |
| `poc/` | Implementation export from Lubuntu (empty until recovered) |
| `README.md` | Human entry point |

## When adding PoC code

1. Export from Lubuntu to a clean tree on this workstation.
2. Strip secrets; replace with `.env.example` placeholders.
3. Land under `poc/` with a short README that matches the dissertation claims.
4. Do not rewrite history to invent features the PDF does not describe.
