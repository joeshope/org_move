# org_move
The purpose of this script is to run through Snyk Group to move organizations and place them within another Snyk Group. The desired organizations will be defined within the .txt file (example included).

# Usage

1. Clone this repository locally

2. Define your Snyk API token (You can find your token in your [General Account Settings](https://app.snyk.io/account) after you login to Snyk.)
<pre><code>export SNYK_TOKEN={API_TOKEN}</code></pre>

3. Create your Organization file. The example file can be used as a template. Each organization name should be placed onto a separate line within the .txt file.

4. Run the main.py script - define all required org(s) in the --orgs argument
<pre><code>python3 main.py --startgroup=ID123 --endgroup=ID456 --file=example.txt --dryrun(optional)</code></pre>
