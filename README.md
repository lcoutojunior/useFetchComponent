
# useFetchComponent

A simple improvement for fetching data to prevent memory leak. 

Sometimes the component still fetching and we change page, or call any other component, but the fetching didn't finished yet, so it will result in a Warning: "Can't perform a React state update on...".

