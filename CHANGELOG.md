# Change Log


## 0.3.0

- add support for multiple Logstash versions: 6.8, 7.2, 7.5
- add "logstash.version" configuration setting to choose Logstash version (for completion)
- add "Set Logstash Version" command (shortcut: Ctrl+Shift+L) to change Logstash version setting
- index template completion: add analyzers, tokenizers and filters completion
- index template completion: add new index settings for Elasticsearch 7.5
- add common options in completion for Logstash outputs
- add '[tags]' possible value in 'if' snippet


## 0.2.0

- add completion for Elasticsearch index template json files, based on a json schema, both for Elasticsearch 6.x and 7.x


## 0.1.0

- provide document formatting and document range formatting on Logstash pipeline configuration
- fix some cases where completion didn't work
- fix lint issues


## 0.0.3

- provide completion and documentation based on Logstash 7.2
- fix example indentation in tooltip documentation
- remove "createSnippet" method duplicates


## 0.0.2

- add documentation display when hover on a section, plugin or option
- files matching `logstash-*.conf` are automatically associated to `Logstash` language
- fix generated snippets that have an option value containing some “s”


## 0.0.1

- provide completion on Logstash sections, plugins and options
