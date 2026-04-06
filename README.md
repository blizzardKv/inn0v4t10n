```javascript
function innovate(mind) {
  if (mind.curious) {
    return { innovation: `💡 ${mind.idea}`, source: 'curiosity' };
  }
  return mind.bored ? null : undefined; // скука не рождает ничего
}
