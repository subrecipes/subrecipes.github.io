### Micropractices

Micropractices are narrow scoped best practices that have a 5000 character limit. They consist of a title,  pitch, tags, and the best practice content written in markdown. The title, which is search indexable, is a creative name for the micropractice. For example, the practice of wrapping dumb ReactJS components in smart higher order components could have the title 'Containerization'. The pitch, which is also search indexable, is a one sentence generalization of the problems a micropractice solves, and the mechanism for how those problems are solved.

Micropractices also come with first class support for updates through a standard versioning system. All updates fall under either a patch, minor, or major update, and these version changes have different affects across the application. For example, patch update alongside a reference to a perspective would create a patch cocontributor.

### Stars

Like most other content sharing platforms, stars are used to signify important micropractices. Starred micropractices are store in a user's My Starred section so that they're easy to access for reference. Currently only lifetime stars per micropractice are supported, but in the future, stars will also be shown as either a weekly or monthly total to showcase the timeliness of the micropractice \(Just because a micropractice has a lot of stars does not mean it's current\).

### Caveats

Caveats are used to point out limitations of a micropractice. Although it might seem intuitive to keep caveats in the content of a micropractice, separating them into their own entity ensures that the character micropractice character limit is used exclusively for explaining how the micropractice works. Caveats are written and added to a micropractice page by the original micropractice author, and updates to caveats are treated as updates to the micropractice. They can be patch, major, or minor, depending on the significance of the change. It is conceivable that a major caveat could warrant a major version update.

### Perspectives

Perhaps a euphamism for the common _issues_ section featured in many online version control platforms, perspectives are a way of informing the author and future readers about missing, inaccurate, or debatable information. Perspectives provide an opportunity to expand on either the support or the caveats of a micropractice, or to point out relevant changes to the content. Just like issues, perspectives are opened and closed based on when their contents are deemed irrelevant. For example, if a reader opens a perspective on a micropractice that is missing a specific limitation, if the original micropractice author agrees, they can add a new caveat to cover that scenario. Once the caveat is added, the perspective is longer necessary, and can be closed. 

### Tags

Like Medium, Stack Overflow, and many other programming resources, microservices can have tags that points to specific subject matter within the developer ecosystem. They can be anything from a technology, to a library. Naetorp tags are also highly coupled with points, and so instead of total points per user, there is total points per tag per user, and point ranks per tag.

### Cocontributors

Users can become major, minor, or patch cocontributors of micropractices by providing insights that respectively lead to major, minor, or patch updates to a micropractice. Users use perspectives and perspective comments to illustrate these insights, and they are added as cocontributors when the micropractice author publishes an update and references a perspective or perspective comment. Multiple users can be added as cocontributors through the same update.

