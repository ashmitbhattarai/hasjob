Hi {{ post.company_name }},

This is regarding your job listing on Hasjob titled "**[{{ post.headline }}]({{ url_for('jobdetail', hashid=post.hashid, _external=True) }})**".

Your listing has been temporarily de-listed by moderator {{ post.reviewer.fullname }}, who left the following comment. Please [edit the listing]({{ url_for('editjob', _external=True, hashid=post.hashid, key=post.edit_key) }}) and correct the indicated issue. A warning notice will appear on your listing until you edit it:

-----

{{ post.review_comments }}

-----

[Hasjob][jb] is a service of [HasGeek][hg]. Write to us at support@hasgeek.com if you have suggestions or questions on this service.

[jb]: https://hasjob.co/
[hg]: https://hasgeek.com/
