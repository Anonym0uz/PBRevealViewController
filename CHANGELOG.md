# CHANGELOG

## 0.3.6

* Git update and add a example.
* Bug fixes.

## 0.3.5

* Git update

## 0.3.4

* Add a toggle animation type: PBRevealToggleAnimationTypeSpring.

A transition that the side view move a little to right or left by the value of leftViewRevealOverdraw or rightViewRevealOverdraw before the main view push the left/right view until it is hidden.

## 0.3.3

* Bug fixes when resizing left/right view when leftPresentViewHierarchically and/or rightPresentViewHierarchically are set to YES. Rview handling of rotations.

## 0.3.2

* Bug fixes

* Add some properties:

If YES (default is NO) the left view controller will be ofsseted vertically by the height of a navigation bar plus the height of status bar.

```
@property (nonatomic) BOOL              leftPresentViewHierarchically;
```

If YES (default is NO) the right view controller will be ofsseted vertically by the height of a navigation bar plus the height of status bar.

```
@property (nonatomic) BOOL              rightPresentViewHierarchically;
```

## 0.3.1

Add documentation

## 0.3.0

The fisrt stable version.