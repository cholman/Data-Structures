insert:
    check if empty
    if empty put node at root
    else
    if new < node.value
        leftnode.insert value
    if >= rightnode.insert value

get_max:
if there's a right:
    get_max on right
else:
    return node.value

find:
if node is none
    return false
    if node.value == find value
        return true
    else
        if find < node.value
        if node.left
            find on left node
        else
            if node.right
                find on right node

forEach: