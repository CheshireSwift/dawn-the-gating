# Dawn: the Gating

MtG fan set in the setting of Dawngate.

Folder for each rarity, plus Unfiled for cards that don't really have a rarity yet. Cards are MtG JSON format, but in YAML, and we aren't too worried about missing fields (if they render correctly in http://swift.swifteagle.co.uk/magic-proxy/ then it's probably fine), plus we're a bit lenient on things like em-dashes (the proxy generator will transform hyphens in the type line automatically).

Travis build runs on master commits and PRs to verify all YAML is valid.
