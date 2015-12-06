Sample:

```
{
  wallPost: [ 727171 ],
  album: [{owner: 727171, id: 213265917}]
}
```

- wallPost: list of users/groups, where we should post photo as wall post.
  - use (id) for user, and (-id) for group. E.g. `727171` is a user, `-1231435` is a group.
- album: list of albums, where we should add photo.
  - owner: user/group, who owns the album
  - id: album id
