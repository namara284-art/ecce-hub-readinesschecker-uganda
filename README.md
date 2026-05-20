# ECCE AI Hub Uganda — Logical Menu Build

This build reorders the site navigation into the requested public-site flow:

1. Home
2. About
3. What to Expect
4. Use the Tool
5. Is My Centre Ready?
6. FAQs
7. Resources
8. Feedback
9. Support

The **Is My Centre Ready?** tool remains highly visible as:
- a large header button,
- a standalone menu item,
- and a large homepage tool card.

## Render settings

Build Command:

```bash
python -m pip install --upgrade pip setuptools wheel && pip install -r requirements.txt
```

Start Command:

```bash
python -m uvicorn app:app --host 0.0.0.0 --port $PORT
```

Leave Pre-deploy Command empty.
Leave Root Directory empty.
