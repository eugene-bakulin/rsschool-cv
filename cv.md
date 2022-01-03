# Eugene Bakulin
## Contacts
* Phone: +7 927 6874294
* E-mail: [bakulin.eugene@gmail.com](bakulin.eugene@gmail.com "e-mail")
* Discord: Eugene Bakulin#9666
## Briefly about myself
My purpose is to move forward and take a new kind of activity. Perseverance is one of my strong features.  
I have a nine years of work experience as engineer in machine building undustry, but now I feel an urgent need in something new.
## Skills
* HTML, CSS
* Java (university course of calculation methods)
* JS
* GIT
* VSCode, IntelliJ IDEA
## Code example
This is the realization of binary search:
```let n = prompt("Please enter the upper bound of search array","");
let item = prompt("Enter the number for search");
let arr = [];
function binarySearch(){
    for (let i=0; i < n; i++) {
        arr[i] = i+1;
    }
    let low = 0;
    let high = arr.length-1;
    while (low <= high) {
        let mid = Math.floor((low + high) / 2);
        if (arr[mid] == item) {
            return arr[mid];
        } else if (arr[mid] > item) {
            high = mid - 1;
        } else {
            low = mid + 1;
        }
    }
    return -1;
}
binarySearch();
```