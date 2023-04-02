# sonarqube-rule-japanese
- SonarQubeルールの日本語訳
- 今のところJavaのみ
- 対象SonarQubeバージョンは9.9-Community

## 適用方法
### Java
```
cd Java
jar -uf ${sonar-java-pluginのjarパス} org/sonar/l10n/java/rules/java
```