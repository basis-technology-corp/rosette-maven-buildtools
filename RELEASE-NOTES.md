# Release Notes

## 7.1.0 - 20260211
- PMD:  Replace `UnnecessaryLocalBeforeReturn` with `VariableCanBeInlined`

## 7.0.1
- Permit references to Babel Street in header

## 7.0.0 - 20230510
- Add `site` and `clean` lifecycle defaults to `pluginManagement`

## 6.0.0 - 20230316
- Add `pluginManagement` section to stop pulling in old plugin versions in downstream projects.
- PMD:  Replace `BooleanInstantiation` with `PrimitiveWrapperInstantiation`.
- PMD:  Replace `EmptyStatementNotInLoop` with `UnnecessarySemicolon`.

## 5.0.0 - 20221104
- PMD:  Replace `PositionLiteralsFirstInComparisons` with `LiteralsFirstInComparisons`
- Nexus Staging:  Replace `https://oss.sonatype.org` with `https://s01.oss.sonatype.org`
- Upgrade plugin versions.

## 4.0.0 - 20200728
- https://github.com/basis-technology-corp/rosette-maven-buildtools/pull/3
- PMD:  LoggerIsNotStaticFinal to ProperLogger
- Remove reference to parent pom.  Deployment configuration moved in to pom.

## 3.0.0 - 20191023
- TBD

## 2.0.0 - 20190411
- TBD

## 1.0.0 - 20151203
- Change GAV from `com.basistech:buildtools` to `com.basistech:open-source-buildtools` and reset version.

## 14.1.0
- TOOLS-702: set `<property name="throwsIndent" value="4"/>`

## 13.1.0
- WS-472: change PMD rules to avoid warnings with PMD plugin 3.5.
