## Community Bonding + Week 1 Report

Hey!

The community bonding period is officially over. It was one of the most resourceful periods and scarier for the starter ;)
But, Thanks to mentors for getting me started with the project.

### Here's an update about my work till today:

=> Setup an `AOSP container`, thanks to @cdesai for helping with the setup.

=> Went through Gradle Build documentation. [1]

=> Majority of the focus was on `Kotlin` since it being a one of the crucial reason for all  blockers, so here's what I did till now:

1.  Fixed Jline3, and it's uploaded (resides in NEW queue). (Thanks to @_hc for the upload).

2.  Most of kotlin work was done by m36 last year, but the changes were made directly to the source. Therefore, I packaged it from scratch, and converted m36 commits to patches. (Thanks for the help @m36)

3.  The kotlin package is fixed with various errors and the debian/* is corrected to meet Debian Standards.

### Other work apart from the Project:
  
=> Filed an ITP for kazocsaba-imageviewer and sent an RFS to the java-team.

=> Update for Kotlin is pushed. [3] (Thanks @andrewsh for the publishing it)

### What's to be done for the upcoming week?

=> Researching about kotlinx-* libraries, kotlin currently depends upon three kotlinx libraries, co-routines, serialization, and metadata-jvm, we need these jar files to reduce the dependency.

=> Look forward to documenting all the Kotlin Updates, maintaining the wiki page.

In the upcoming weeks, if we manage to get a workaround to the circular dependencies, we might have Kotlin in Debian soon enough!


Thanks and regards,

Samyak Jain

(samyak-jn[m])

[1] https://docs.gradle.org/current/javadoc/index.html

[2] https://salsa.debian.org/samyak-jn/kotlin

[3] https://java-team.pages.debian.net/gsoc-kotlin-blog/2020/06/01/kotlin-update/
