# SearchEngine.ai
Search Engine for AI-ML Blogs
A minimalistic Python search engine for the latest AI-ML blogs from the top researchers, tech firms and varsities.<br>
<h3>Modules Used:</h3>
<ul>
  <li>FasAPI</li>
  <li>argparse</li>
  <li>bs4</li>
  <li>feedparser</li>
  <li>aiohttp</li>
  <li>asyncio</li>
</ul>
<h3>Steps:</h3>
<ul>
  <li>Add RSS links of blogs you follow to feeds.txt.(I've already added around 60)</li>
  <li>To download the content, do:<br>
    <code>python download_content.py --feed-path feeds.txt</code>
  </li>
  <li>To launch the app, do:<br>
    <code>python -m app.app --data-path output.parquet</code><br>
    Navigate to http://127.0.0.1:8000/
  </li>
</ul>
