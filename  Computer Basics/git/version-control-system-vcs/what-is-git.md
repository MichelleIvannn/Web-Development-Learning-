# What is Git

### Snapshots, Not Differences

* The major difference between Git and any other VCS (Subversion and friends included) is the way Git thinks about its data.
* Conceptually, most other systems store information as a list of file-based changes
* _delta-based_ version control
  * think of the information they store as a set of files and the changes made to each file over time

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption><p>Storing data as changes to a base version of each file</p></figcaption></figure>

***

### Git Differences&#x20;

* Git thinks of its data more like a series of snapshots of a miniature filesystem.
* Git basically takes a picture of what all your files look like at that moment and stores a reference to that snapshot.
* Git thinks about its data more like a **stream of snapshots**.

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

***

### Nearly Every Operation Is Local

*
