# Tagify 💬

<p align="center">
  <img src="https://user-images.githubusercontent.com/37345795/205490455-f2794cab-7197-428d-8a53-b9b829f29e29.png"/>
</p>

<p  align="center">
<a  href="https://flutter.dev"  target="_blank"><img  height="39"  src="https://user-images.githubusercontent.com/37345795/205487266-9604e883-3bd3-45a5-b172-f4617d911ee3.png"  alt="Flutter Logo"></a> <a>&nbsp;&nbsp;&nbsp;</a>
<a  href="https://dart.dev/"  target="_blank"><img  height="39"  src="https://user-images.githubusercontent.com/37345795/205487289-bd04321b-3f3a-431d-9c29-7e8e4a22d43f.png"  alt="Flutter Logo"></a> <a>&nbsp;&nbsp;&nbsp;</a>
<a  href="https://firebase.google.com/"  target="_blank"><img  height="39"  src="https://user-images.githubusercontent.com/37345795/205487145-a7ad5e40-71e1-46d5-a828-ef82ee168885.png"  alt="Appwrite Logo"></a>
</p>

Tagify enables the user to create and manage groups with ease. It lets the user find the right set of people and communicate relevant information with them.
- After creating an account, users can assign themselves tags, for e.g. appdev, rajasthan, burger, etc.
- Say we want to address everyone who is in Rajasthan and likes Burger or is in Assam and likes Fish, then we can simply create a group with this logic: `(rajasthan AND burger) OR (assam AND fish)` which is equivalent to `(rajasthan & burger) | (assam & fish)` and a group with those people will automatically be made!
- To enter the logic for a group, we are using a bunch of buckets, there can be any number of buckets, and each bucket can contain any number of tags. The tags inside a bucket are `AND`ed, and then the buckets are `OR`ed together.

