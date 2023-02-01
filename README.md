# Das ist ein Test
- 1
- 2
- 3
- 4

Das ist normaler Text

> Blockquote

[YouTube](yotube.com)

![Goofy](https://i.ytimg.com/vi/Ls2Hc1-XIjE/mqdefault.jpg)

´public class Node {

    private int _data;
    private Node _leftChild;
    private Node _rightChild;

    private Node _parent;

    public Node() { }

    public Node(int data, Node leftChild, Node rightChild, Node parent) {
        _data = data;
        _leftChild = leftChild;
        _rightChild = rightChild;
        _parent = parent;
    }

    public Node get_parent() { return _parent; }
    public void set_parent(Node parent) {
        _parent = parent;
    }

    public int get_data() {
        return _data;
    }

    public void set_data(int _data) {
        this._data = _data;
    }

    public Node get_leftChild() {
        return _leftChild;
    }

    public void set_leftChild(Node _leftChild) {
        this._leftChild = _leftChild;
    }

    public Node get_rightChild() {
        return _rightChild;
    }

    public void set_rightChild(Node _rightChild) {
        this._rightChild = _rightChild;
    }
}
´
