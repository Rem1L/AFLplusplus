1. 避免重复的execution和crash (考虑删除，似乎不再有意义)
2. 若变异后代出现crash,则下调队列条目perf_score (似乎应该直接disable entry)
