# Regex

Material created for quick consultation of regex that I created and use frequently.

Regexes were used mainly with JavaScript and Java.

Javascript:

<code>\\gi</code>

Java:

*need to convert regexs to Java strings*

<code>\\gms</code>



| Pattern |                Regex               |
| :----: | :--------------------------------: |
|   CPF  |     `\d{3}\.\d{3}\.\d{3}-\d{2}`    |
|  CNPJ  | `\d{2}\.\d{3}\.\d{3}\/\d{4}-\d{2}` |
| Código de Barras | `\d{5}\.\d{5}\s*\d{5}\.\d{6}\s*\d{5}\.\d{6}\s*\d\s*\d{14}`|
| Data separa por barras   |  `\d{2}\/\d{2}\/\d{4}` |
| US Phone Number   |  <code>/^(1\s?)?((\([\d]{3}\))|[\d]{3})[\s\-]?[\d]{3}[\s\-]?[\d]{4}$/</code> |
