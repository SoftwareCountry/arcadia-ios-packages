# Arcadia iOS packages

A collection of packages we can approve for usage based on experience.

## How to use

Add the [link](https://raw.githubusercontent.com/SoftwareCountry/arcadia-ios-packages/main/collection.json) to `collection.json` to the Xcode [package collections section](https://swiftpackageindex.com/package-collections).

## How to update

The `collection.json` is generated using [swift-package-collection-generator](https://github.com/apple/swift-package-collection-generator/blob/main/Sources/PackageCollectionGenerator/README.md).
Update `package.json` according to the format documentation, then run:
```sh
swift run package-collection-generate path-to/packages.json path-to/collection.json
```

## More documentation

[Swift package collections documentation](https://swift.org/blog/package-collections/)
