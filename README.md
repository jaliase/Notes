# How to add a line in a file using bash if the line already doesnt exist
`grep -qxF '<your-line>' <file> || echo '<your-line>' >> <file>`
