/* Default Theme */
html.default {
  --background: #ffffff;
  --foreground: #000000;
  --card: #f5f5f5;
  --primary: #030213;
  --secondary: #ececf0;
}

/* Space Theme */
html.space {
  --background: #1a1a2e;
  --foreground: #f0f0f0;
  --card: #2c2c44;
  --primary: #8ab4f8;
  --secondary: #4e4e6a;
}

/* Desert Theme */
html.desert {
  --background: #edc9af;
  --foreground: #3e2f1c;
  --card: #f5e0c3;
  --primary: #d18b47;
  --secondary: #c8a77f;
}

/* Sky Theme */
html.sky {
  --background: #87ceeb;
  --foreground: #034c8c;
  --card: #b0e0e6;
  --primary: #1e90ff;
  --secondary: #4682b4;
}

/* Comic Theme */
html.comic {
  --background: #ffeb3b;
  --foreground: #212121;
  --card: #ffc107;
  --primary: #f44336;
  --secondary: #8e24aa;
}

/* Nature Theme */
html.nature {
  --background: #a3d9a5;
  --foreground: #1b3b1b;
  --card: #cde6c7;
  --primary: #2e7d32;
  --secondary: #81c784;
}

/* City Theme */
html.city {
  --background: #555555;
  --foreground: #eeeeee;
  --card: #666666;
  --primary: #bbbbbb;
  --secondary: #999999;
}

/* Apply variables to body & cards */
body {
  background-color: var(--background);
  color: var(--foreground);
}

.card {
  background-color: var(--card);
  color: var(--foreground);
  border: 1px solid var(--secondary);
  padding: 1rem;
  border-radius: 0.5rem;
}
