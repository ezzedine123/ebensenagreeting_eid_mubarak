import { useState, useMemo } from "react";
import EntranceScreen from "@/components/EntranceScreen";
import GreetingCard from "@/components/GreetingCard";
import GoldParticles from "@/components/GoldParticles";
import AudioControl from "@/components/AudioControl";

const BG_THEMES = [
  // Gold/Obsidian (original)
  "linear-gradient(-45deg, hsl(40,20%,4%), hsl(40,20%,8%), hsl(43,30%,10%), hsl(40,20%,4%))",
  // Deep Emerald
  "linear-gradient(-45deg, hsl(160,30%,4%), hsl(160,25%,8%), hsl(150,35%,12%), hsl(160,30%,4%))",
  // Royal Navy
  "linear-gradient(-45deg, hsl(220,40%,5%), hsl(220,35%,9%), hsl(210,40%,13%), hsl(220,40%,5%))",
  // Burgundy
  "linear-gradient(-45deg, hsl(350,30%,5%), hsl(350,25%,9%), hsl(340,30%,12%), hsl(350,30%,5%))",
  // Deep Purple
  "linear-gradient(-45deg, hsl(270,30%,5%), hsl(270,25%,9%), hsl(260,30%,13%), hsl(270,30%,5%))",
  // Warm Bronze
  "linear-gradient(-45deg, hsl(30,30%,4%), hsl(25,25%,8%), hsl(20,35%,11%), hsl(30,30%,4%))",
];

const Index = () => {
  const [name, setName] = useState<string | null>(null);

  const bgGradient = useMemo(() => {
    const idx = Math.floor(Math.random() * BG_THEMES.length);
    return BG_THEMES[idx];
  }, []);

  return (
    <div
      className="min-h-svh flex items-center justify-center p-4"
      style={{
        background: bgGradient,
        backgroundSize: "400% 400%",
        animation: "goldGradient 15s ease infinite",
      }}
    >
      <AudioControl playing={!!name} />
      {name && <GoldParticles />}
      {!name ? (
        <EntranceScreen onStart={setName} />
      ) : (
        <GreetingCard name={name} />
      )}
    </div>
  );
};

export default Index;
