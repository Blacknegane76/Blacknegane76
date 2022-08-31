/* Don't use this */
if fruits.isEmpty {
    // do stuff here
} else {
    return
}

/* Use this instead */
guard fruits.isEmpty else { return }
// do stuff here

if let foo = foo {
    /// use safely unwrapped foo here
}
