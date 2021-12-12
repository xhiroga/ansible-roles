# com.apple.dock

## Debug

```shell\
make --directory ./molecule/docker-image
molecule test
```

## Role Variables

See [vars](./vars/main.yml).

## Dependencies

- PlistBuddy
- plutil

## Note

[`com.apple.dock.plist` in this repository](./molecule/docker-image/com.apple.dock.plist) is not equal to original OSX one.  Some properties are removed.

## References

- [Dock \| Apple Developer Documentation](https://developer.apple.com/documentation/devicemanagement/dock)
