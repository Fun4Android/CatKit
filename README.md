# CatKit
<p align="center">

Android <strong>kit</strong> for <strong>cat placeholders</strong>
</p>
<p align="center">
<img src="https://raw.github.com/cesarferreira/catkit/master/extras/images/catkit_logo_trimmed.png?raw=true" width="100%" />
</p>

## Usage

With Density-independent Pixels:
```java
CatKit.with(context)
        .dp(200, 200)
        .into(targetImageView);
```


With Pixels:
```java
CatKit.with(context)
        .px(500, 300)
        .into(targetImageView);
```

Memory Policy:
```java
CatKit.with(context)
        .dp(200, 200)
        .memoryPolicy(MemoryPolicy.NO_CACHE)
        .into(targetImageView);
```

## Install


Add the dependency to your `build.gradle`
```groovy
dependencies {
  compile 'com.cesarferreira.catkit:catkit:0.3.0'
}
```



## Contributing

1. Fork it ( https://github.com/cesarferreira/catkit/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
