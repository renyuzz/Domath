import React, { useState, useMemo } from 'react';

export default function App() {
  // 預設參數：A標(基準分)預設200，B標(倍率)預設0.80
  const [baseScore, setBaseScore] = useState(200);
  const [multiplier, setMultiplier] = useState(0.80);

  // 產生 0.60 到 0.81 的倍率陣列 (間距 0.01)
  const multipliers = useMemo(() => {
    return Array.from({ length: 22 }, (_, i) => (0.60 + i * 0.01).toFixed(2));
  }, []);

  // 計算B標結果 (保留小數點第一位)
  const handicapResult = (baseScore * multiplier).toFixed(1);

  return (
    <div className="min-h-screen bg-slate-100 dark:bg-slate-900 text-slate-800 dark:text-slate-200 p-4 font-sans flex justify-center items-start">
      <div className="w-full max-w-md bg-white dark:bg-slate-800 rounded-2xl shadow-xl overflow-hidden mt-6">
        
        {/* Header */}
        <div className="bg-blue-600 dark:bg-blue-700 p-6 text-center">
          <h1 className="text-2xl font-bold text-white flex items-center justify-center gap-2">
            <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round">
              <circle cx="12" cy="12" r="10"></circle>
              <circle cx="10" cy="9" r="1" fill="currentColor"></circle>
              <circle cx="14" cy="9" r="1" fill="currentColor"></circle>
              <circle cx="12" cy="13" r="1" fill="currentColor"></circle>
            </svg>
            保齡球 B標換算器
          </h1>
          <p className="text-blue-100 text-sm mt-2 opacity-90">快速計算 B標結果</p>
        </div>

        <div className="p-6 space-y-6">
          {/* 輸入區塊 */}
          <div className="space-y-4">
            {/* A標分數 */}
            <div>
              <label className="block text-sm font-medium mb-1">A標分數</label>
              <input 
                type="number" 
                value={baseScore} 
                onChange={(e) => setBaseScore(Number(e.target.value))}
                className="w-full p-3 bg-slate-50 dark:bg-slate-900 border border-slate-300 dark:border-slate-700 rounded-xl focus:ring-2 focus:ring-blue-500 focus:outline-none transition-all dark:text-white"
                placeholder="請輸入A標分數"
              />
            </div>

            {/* 倍率選擇 */}
            <div>
              <label className="block text-sm font-medium mb-1">倍率</label>
              <select 
                value={multiplier} 
                onChange={(e) => setMultiplier(Number(e.target.value))}
                className="w-full p-3 bg-slate-50 dark:bg-slate-900 border border-slate-300 dark:border-slate-700 rounded-xl focus:ring-2 focus:ring-blue-500 focus:outline-none transition-all dark:text-white appearance-none"
              >
                {multipliers.map(m => (
                  <option key={m} value={m}>{m}</option>
                ))}
              </select>
            </div>
          </div>

          {/* B標結果 */}
          <div className="pt-4 border-t border-slate-200 dark:border-slate-700">
            <h2 className="text-sm font-medium mb-3 text-slate-500 dark:text-slate-400 text-center">
               計算結果
            </h2>
            <div className="flex flex-col items-center justify-center bg-blue-50 dark:bg-blue-900/20 rounded-2xl p-8 border border-blue-100 dark:border-blue-800/50 shadow-inner">
              <div className="text-sm text-blue-600 dark:text-blue-400 font-medium mb-2">B標結果</div>
              <div className="text-6xl font-bold text-blue-700 dark:text-blue-300">
                {handicapResult}
              </div>
            </div>
          </div>

        </div>
      </div>
    </div>
  );
}
