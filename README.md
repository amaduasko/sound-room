# sound-room

Create Rooms, listen to something cool with your friends, choose who controls the flow...

const cb = useCallback(() => {
setVh(() => `${window.innerHeight}px`);
}, [setVh]);

useLayoutEffect(() => {
window.addEventListener('resize', cb);
return () => {
window.removeEventListener('resize', cb);
};
}, []);
