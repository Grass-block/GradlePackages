# GradlePackages
Simple gradle-library package registry for my projects
### declear repository
```groovy
    maven {
        url = uri("https://maven.pkg.github.com/Grass-Block/GradlePackages")
        credentials {
            username = "Test" //your github id
            password = "Token" // your gpr token
        }
    }
```

### import dependency
```groovy
dependencies {
    implementation 'org.atcraftmc.qlib:qlib-configuration:1.3.2'
}
```

## Packages
### [AdvancedPluginMessenger](https://github.com/Grass-block/AdvancedPluginMessenger)
- implementation 'me.gb2022.apm:apm-remote:3.1.10'
- implementation 'me.gb2022.apm:apm-plugin:1.2.10'


### [QLib](https://github.com/Grass-block/QLib)
- 'org.atcraftmc.qlib:qlib-base:1.3.2'
- 'org.atcraftmc.qlib:qlib-task:1.3.2'
- 'org.atcraftmc.qlib:qlib-texts:1.3.2'
- 'org.atcraftmc.qlib:qlib-configuration:1.3.2'
- 'org.atcraftmc.qlib:qlib-command:1.3.2'

### [Commons](https://github.com/Grass-block/Commons)
- 'me.gb2022.commons:commons-nbt:1.0'
- 'me.gb2022.commons:commons-math:1.0'
- 'me.gb2022.commons:commons-container:1.0'
- 'me.gb2022.commons:commons-general:1.0'
- 'me.gb2022.commons:commons-event:1.0'
- 'me.gb2022.commons:commons-reflection:1.0'
