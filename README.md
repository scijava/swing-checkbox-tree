# Swing Checkbox Tree

A check box tree package based on John Zukowski's [CheckBox Node Tree
Sample](http://www.java2s.com/Code/Java/Swing-JFC/CheckBoxNodeTreeSample.htm)
code. 

You can mix and match `DefaultMutableTreeNode` and `CheckBoxNodeData` node
types. It also allows check box nodes as non-leaf nodes.

It uses a `JCheckBox` + `JLabel` in a `JPanel` to differentiate between
clicking on a check box (to check/uncheck a node) versus a label (to select a
node).

* _License:_ [BSD-2](https://github.com/scijava/swing-checkbox-tree/blob/master/LICENSE.txt)
* _Dependencies:_ None
* _Maven Central:_ [org.scijava:swing-checkbox-tree](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22org.scijava%22%20AND%20a%3A%22swing-checkbox-tree%22)
* _Simple example:_ [CheckBoxTreeSample](https://github.com/scijava/swing-checkbox-tree/blob/master/src/test/java/org/scijava/swing/checkboxtree/CheckBoxTreeSample.java)
* _Complex example:_ [WatchEventsFrame](https://github.com/imagej/imagej/blob/ee3c360949/ui/swing/plugins/src/main/java/imagej/ui/swing/plugins/debug/WatchEventsFrame.java)

The latter example also has code for recursively toggling subtrees in response
to boxes being checked or unchecked (see the `treeNodesChanged` method).

See also
[this question on StackOverflow](http://stackoverflow.com/a/12866094/1207769).
