Add your answers to the Algorithms exercises here.

Exercise I

    a. O(n^3)

    b. O(lg n)

    c. O(8 * n) sqrt(n) / 2 = n

    d. O(lg 2)

    e. O(n^3)

    f. O(n)

    g. O(n)

Exercise II

    a. function maxAlg(arr) {
        let max = -1;
        for (let i=0; i <arr.length; i++) {
            for (let 1 = arr.length - 1; --j) {
                if(arr[j] > arr[i] && max < (j-1))
                max = j - i;
            }
        }
        return max;
    }

Exercise III

    a. O(n^2)

    b. O(n log n)