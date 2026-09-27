# freeCodeCamp: Teacher and Classes

Glossary for the teacher and classes capability. Language only; no implementation detail.

## Language

**Learner**:
A person with a freeCodeCamp account who works through the curriculum.

**Teacher**:
A Learner who has switched on teacher mode on their own account. Teacher mode is self-serve and needs no approval. One account can be both a Teacher and a Learner.
_Avoid_: instructor, educator

**Class**:
A group of Learners that a Teacher sets up and manages, in order to follow their progress and review their work.

**Class member**:
A Learner who belongs to a Class.
_Avoid_: student, enrollee

**Invite**:
A Teacher's request for an existing Learner to join a Class. It becomes a membership only when the Learner accepts.

**Sharing consent**:
A Learner's permission, given per Class and revocable, for that Class's Teacher to see their learning data. Accepting an Invite grants it; leaving the Class or revoking it ends it.
_Avoid_: opt-in, Classroom Mode (the older, account-wide setting)

**Owner**:
The Teacher who created a Class. Can delete, archive or transfer it. Must transfer ownership or archive the Class before turning teacher mode off.

**Co-teacher**:
A Teacher added to a Class by its Owner. Has every Owner power except deleting, archiving or transferring the Class.
_Avoid_: assistant (no read-only role exists), instructor

**Join code**:
A code or link a Teacher shares so a Learner can join a Class without being looked up. Joining through it still requires Sharing consent.

**Assignment**:
A piece of curriculum a Teacher sets for a Class, from a single challenge up to a block, with a due date. The due date is informational: it marks work "late" and never blocks the Learner.

**Assigned item**:
A challenge covered by an Assignment. A Teacher sees a Class member's activity only on assigned items and only from the join date onward.

**Project review**:
A Teacher's decision on a Class member's submitted certification project: approved, needs-changes or rejected, with optional feedback. Exists only for Class members; it does not affect certification.

**Feedback**:
A Teacher's written comment to a Class member, attached either to a Project review or to an Assignment.

**Announcement**:
A message a Teacher posts to a whole Class.

**Archived Class**:
A Class frozen by its Owner. History stays; nothing changes and no progress record is deleted.

**Audit entry**:
A record that a Teacher viewed a Learner's project or detailed progress. Readable by that Learner and by the Class Owner, and by platform admins. Kept while the Class exists plus six months.

**Classroom Mode**:
The existing account-wide setting by which a Learner shares progress with the external Classroom app. It is separate from, and will be superseded by, Class and Sharing consent.

## Relationships

- A Teacher sets up one or more Classes.
- A Class has zero or more Class members; a Learner can be a member of several Classes.
- A Learner's data is visible to a Class's Teacher only while that Learner's Sharing consent for that Class stands.
- Class members are adults; there is no minor-specific handling.
- A Teacher's decision on a project applies only to Class members, never to Learners studying on their own.
