# Page 4

### 3.2 - Modifying The Metadata

_But Now I Want To Know How To Edit The Mod Metadata How Do I Do That?_

_**First You'll Have To Learn The Manifest Files Of Each Supported Modloader**_



{% tabs %}
{% tab title="Forge" %}
\
The Forge Mod Loader Mod Manifest File Is <mark style="color:red;">`mods.toml`</mark>\
This Is Our <mark style="color:red;">`mods.toml`</mark> File:\


{% code title="mods.toml" overflow="wrap" lineNumbers="true" fullWidth="true" %}
```toml

modLoader = 'lowcodefml'
loaderVersion = '[40,)'
license = 'MIT'
showAsResourcePack = false
mods = [
	{ modId = 'recycling', version = '0.0.7-alpha', displayName = 'Recycling', description = 'A Mod That Adds Some Recipes To Recycle', logoFile = 'recycling_pack.png', updateJSONURL = 'https://github.com/DEMnetwork/Recycling/raw/main/update.json', credits = '  ', authors = 'DEMnetwork', displayURL = 'https://modrinth.com/datapack/recycling' },
]
issueTrackerURL = 'https://github.com/DEMnetwork/Recycling/issues'
```
{% endcode %}

That Manifest File Contains The Mod\`s Metadata Such As:

* Display Name
* Mod ID
* Authors
* Issue Tracker
* License
* And More

And That FIle Is Important Without That File It Will Not Load The Mod!
{% endtab %}

{% tab title="Fabric" %}
Work In Progress
{% endtab %}

{% tab title="Quilt" %}
Work In Progress
{% endtab %}
{% endtabs %}
