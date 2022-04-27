# WikiApiary

[WikiApiary](http://wikiapiary.com/) is a wiki that tracks the performance and activity on hundreds of other MediaWiki websites. WikiApiary is largely powered by MediaWiki itself along with Semantic MediaWiki and dozens of related extensions. Additionally, there are bots that work in conjunction with the wiki to provide all of the additional services.

## Bots

There are multiple bots powering WikiApiary.

### Bumble Bee

[Bumble Bee](http://wikiapiary.com/wiki/User:Bumble_Bee) is the bot that collects statistics and general configuration information from the wikis in WikiApiary. Bumble Bee selects the wikis it will collect information from WikiApiary and stores the metrics in a separate MySQL database. This database is then pulled directly for charting metrics.

General information on versions and extensions being used are pulled and recorded directly into wiki pages in WikiApiary.

### Audit Bee

[Audit Bee](http://wikiapiary.com/wiki/User:Audit_Bee) serves a special purpose to prune things on WikiApiary and keep services healthy. The bot's tasks include making websites inactive (see Property:Is active) if they have not had any edits in 12 weeks.

### Welcome Bee

[Welcome Bee](http://wikiapiary.com/wiki/User:Welcome_Bee) welcomes new users.

### Notify Bee

[Notify Bee](http://wikiapiary.com/wiki/User:Notify_Bee) sends notifications to people that have requested them.
