#TwoLevelExpandableRecyclerView

Library to create two level expandable RecyclerView.

Example you can find in *twolevelexpandablerecyclerview.example* module.

### Implementation

Two use this library you need to extend *TwoLevelExpandableAdapter* and override a couple of methods there.

Also you need to provide *ViewHolders* for top and second level of list hierarchy. Both of them must be child of *ViewHolderWithSetter*

### Gradle Dependency

    dependencies {
        compile 'org.kaerdan:twolevelexpandablerecyclerview:1.0'
    }

### License

The Apache Software License, Version 2.0