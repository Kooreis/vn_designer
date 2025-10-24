# vn_designer
Visual authoring tool that designs sensible simple .json files for usage in creation of visual novels, skipping the hassle of overwhelming game creation engines.
"""
Through Flask, lets you:
- Visualize your dialogue tree as a graph.
- Manage ID->name "Variables" (Background, Ending Screen, Dialogue, Soundtrack, etc.) so you can avoid extra bloat data-wise when actually utilizing your tree in code.
- Create/Edit/Delete dialogue nodes with guided, multi-entry forms (asks to add more when relevant).
- Auto-saves to a JSON file at:
    Windows: C:\Users\kreis\Downloads\VisualNovel\visual_novel.json
    Other OS: ~/Downloads/VisualNovel/visual_novel.json
Run:
    pip install flask
    python vn_designer.py
Then open http://127.0.0.1:5000 in your browser.
"""
