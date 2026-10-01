# Petty Court by Kaushik Immadisetty

<img src="assets/logo.png" width="96" alt="Petty Court logo">

A skill for ChatGPT and Codex that settles petty arguments with a dramatic, official court ruling. Every ruling picks a winner and gives the loser a ridiculous but harmless sentence.

```
⚖️ PETTY COURT IS NOW IN SESSION
📂 The case: The People v. The Roommate, in the Matter of One Unlabeled Slice
🔨 Ruling: The court finds for the plaintiff. Pizza ownership is established by who ordered it, not by handwriting.
🚨 Sentence: The roommate shall buy a replacement pizza and label it "PROPERTY OF THE VICTIM" in permanent marker.
📜 This ruling is final and cannot be appealed.
```

Try asking: *"My roommate ate my leftover pizza and said it didn't have a name on it."*

Petty Court is for entertainment only and is not legal, relationship or professional advice. It only hears petty cases. Disputes involving safety, abuse, serious money, legal matters or health get a short, kind redirect instead of a joke ruling.

## Layout

```
plugin.json                                          Plugin manifest and listing metadata
skills/petty-court-by-kaushik-immadisetty/SKILL.md   The skill
assets/                                              Logo and composer icon
PRIVACY.md                                           Privacy policy
```

## Building the upload ZIP

```bash
zip -rX petty-court-by-kaushik-immadisetty.zip plugin.json skills assets -x '*.DS_Store'
```

## Privacy

Petty Court collects nothing. See [PRIVACY.md](PRIVACY.md).

## Support

Open an issue at https://github.com/kaushikimmadisetty/Petty-Court-by-Kaushik-Immadisetty/issues
