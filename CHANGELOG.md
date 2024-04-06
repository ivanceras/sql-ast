# Changelog

## 0.8.0
- Remove dialects except for GenericDialect
- remove transaction related query: commit, rollback
- remove set variable and show columns query

## 0.7.5
- update bigdecimal to latest version

## 0.7.4
 - Add IN to binary operator
 - Add Expr::ValueList

## 0.7.3
- Add Default variant in Value AST
- Expose Value in root crate

## 0.7.2
- add `json` to data_type

## 0.6.0 - Fork from sqlparser
- implement parsing of `IF NOT EXIST` on `CreateTable`

