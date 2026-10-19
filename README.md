# routewise
# RouteWise - Smart Route Optimization System

DSA project: Dijkstra (min-heap), A*, BFS, Held-Karp DP (multi-stop TSP), Kruskal + Union-Find.

## Run (Windows)
1. Open this folder in VS Code (File > Open Folder) - you must see `app.py` in the Explorer.
2. Open the terminal (Ctrl + `) and run:
   python -m venv venv
   venv\Scripts\activate
   pip install -r requirements.txt
   python app.py
3. Open http://127.0.0.1:5000

Shortcut: double-click `run.bat`, or press F5 in VS Code (choose "RouteWise: Web app").

## Other
- Command line version: python main.py
- Tests: python -m unittest discover -s tests -t .

## Deploy (Render)
Build command: pip install -r requirements.txt
Start command: gunicorn app:app --workers 1
