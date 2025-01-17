# React useEffect setInterval memory leak
This example demonstrates a common error when using setInterval within the useEffect hook in React.  Forgetting to clear the interval in the cleanup function leads to a memory leak, as the interval continues to run even after the component unmounts.

The solution shows how to correctly use setInterval with a cleanup function to prevent this memory leak.
