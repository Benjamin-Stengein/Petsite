<script setup>
import { 
  Card, 
  CardContent, 
  CardDescription, 
  CardFooter, 
  CardHeader, 
  CardTitle,
} from '@/components/ui/card'
import { Button } from '@/components/ui/button'
</script>
<template>
  <div class="min-h-screen bg-background text-foreground p-8 flex justify-center items-center">
    
    <Card class="w-[350px] shadow-xl">
      <CardHeader>
        <CardTitle>System Check</CardTitle>
        <CardDescription>the website works!?</CardDescription>
      </CardHeader>
      
      <CardContent>
        <p class="text-sm">
           can you see this
           <p class="text-m">yesyesyes</p>
        </p>
      </CardContent>
      
      <CardFooter class="flex justify-between">
        <Button variant="outline">yes?</Button>
        <Button>yes!</Button>
      </CardFooter>
    </Card>

  </div>
`</template>