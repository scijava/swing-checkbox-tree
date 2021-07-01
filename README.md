[![](https://img.shields.io/maven-central/v/org.scijava/swing-checkbox-tree.svg)](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22org.scijava%22%20AND%20a%3A%22swing-checkbox-tree%22)
[![](https://github.com/scijava/swing-checkbox-tree/actions/workflows/build-main.yml/badge.svg)](https://github.com/scijava/swing-checkbox-tree/actions/workflows/build-main.yml)

# Swing Checkbox Tree

A check box tree package based on John Zukowski's [CheckBox Node Tree
Sample](http://www.java2s.com/Code/Java/Swing-JFC/CheckBoxNodeTreeSample.htm)
code. 

You can mix and match `DefaultMutableTreeNode` and `CheckBoxNodeData` node
types. It also allows check box nodes as non-leaf nodes.

It uses a `JCheckBox` + `JLabel` in a `JPanel` to differentiate between
clicking on a check box (to check/uncheck a node) versus a label (to select a
node).

* __License:__ [BSD-2](https://github.com/scijava/swing-checkbox-tree/blob/master/LICENSE.txt)
* __Dependencies:__ None
* __Maven Central:__ [org.scijava:swing-checkbox-tree](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.scijava%22%20AND%20a%3A%22swing-checkbox-tree%22)
* __Simple example:__ [CheckBoxTreeSample](https://github.com/scijava/swing-checkbox-tree/blob/master/src/test/java/org/scijava/swing/checkboxtree/CheckBoxTreeSample.java)
* __Complex example:__ [WatchEventsFrame](https://github.com/imagej/imagej/blob/03a616522d31d9a1777880778cbd11f12f28e3e2/ui/swing/commands/src/main/java/imagej/ui/swing/commands/debug/WatchEventsFrame.java)

The latter example also has code for recursively toggling subtrees in response
to boxes being checked or unchecked (see the `treeNodesChanged` method).

See also
[this question on StackOverflow](http://stackoverflow.com/a/12866094/1207769).
